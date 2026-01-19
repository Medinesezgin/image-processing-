# Görüntü İşleme Uygulaması (PyQt5)

Bu proje, *Görüntü İşleme* dersi kapsamında geliştirilmiş, *PyQt5 tabanlı masaüstü bir uygulamadır*.  
Uygulama, BMP formatındaki görüntüler üzerinde temel ve orta seviye görüntü işleme işlemlerini *harici kütüphaneler kullanmadan (algoritmalar sıfırdan yazılarak)* gerçekleştirmektedir.

---

## 📌 Proje Özellikleri

Uygulama aşağıdaki görüntü işleme işlemlerini destekler:

- Gri seviye dönüşüm
- Binary (eşikleme)
- Histogram germe
- Parlaklık ayarlama
- Döndürme (Rotation)
- Kırpma (Crop)
- Yakınlaştırma (Zoom)
- Gauss bulanıklaştırma
- Ortalama (Blurring)
- Gürültü ekleme ve filtreleme
- Sobel kenar bulma
- Morfolojik işlemler (Erozyon, Genişleme)
- RGB ↔ Grayscale dönüşümleri
- Önizleme penceresi (orijinal / işlenmiş görüntü)

Tüm işlemler *piksel seviyesinde manuel olarak* uygulanmıştır.

---

## Kullanılan Teknolojiler

- *Python 3.x*
- *PyQt5*
- BMP görüntü formatı
- Harici görüntü işleme kütüphanesi kullanılmamıştır  
  (OpenCV, PIL, NumPy vb. yok)

---

##  Proje Dosya Yapısı
