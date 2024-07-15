# Animasyonlu Veri Görselleştirme

Bu proje, bir bivariate Gaussian dağılımından veri simüle ederek ve bu veriyi zamanla değişen bir şekilde animasyonlu olarak görselleştirerek verilerin dinamik yapısını incelemeyi amaçlamaktadır. Bu proje, Python programlama dilinde Seaborn ve Matplotlib kütüphanelerini kullanarak gerçekleştirilmiştir.


## Gerekli Kütüphaneler

Aşağıdaki kütüphanelerin yüklü olduğundan emin olun:
- numpy
- seaborn
- matplotlib

## Başlangıç Parametrelerinin Belirlenmesi

Veri oluşturma için gerekli başlangıç parametreleri belirlenir. Verilerin sayısı, ortalama, kovaryans matrisi ve rastgele sayı üreticisi tanımlanır.

```python
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
from matplotlib.animation import FuncAnimation, PillowWriter

sns.set_theme(style="dark")

# Başlangıç parametrelerini belirliyoruz
n = 10000
mean = [0, 0]
cov = [(2, .4), (.4, .2)]
rng = np.random.RandomState(0)

## Sonuç
Bu proje, verilerin zamanla nasıl değiştiğini simüle eder ve bu değişimi animasyonlu bir grafik olarak gösterir. Oluşturulan animasyon "data_variation_animation.gif" adıyla kaydedilir ve çalışma dizininde bulunabilir. Bu şekilde, zamanla değişen verinizi animasyonlu bir grafik olarak paylaşabilirsiniz.

## Lisans
Bu proje MIT Lisansı altında lisanslanmıştır.

## İletişim
Proje ile ilgili sorularınız veya katkılarınız varsa, issue açabilir veya proje sahibi ile iletişime geçebilirsiniz.


