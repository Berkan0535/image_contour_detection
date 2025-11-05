📘 README (örnek içerik)

````markdown
# Görüntüde Kontur (Sınır) Tespiti – OpenCV Uygulaması

Bu proje, OpenCV kullanarak bir görüntü üzerinde **gri seviye dönüştürme**, **eşikleme (thresholding)** ve **kontur tespiti** işlemlerinin nasıl yapıldığını gösterir.  
Kodlar, temel görüntü çözümleme kavramlarını uygulamalı şekilde öğretmek için hazırlanmıştır.

---

## 🧠 İçerik
1. Görüntünün gri seviyeye dönüştürülmesi  
2. Eşikleme (thresholding) işlemiyle ikili (binary) görüntü elde edilmesi  
3. `cv2.findContours()` fonksiyonuyla kontur tespiti  
4. `cv2.drawContours()` ile bulunan konturların görselleştirilmesi  
5. Görüntülerin `matplotlib` ile gösterilmesi

---

## 💡 Kullanılan Kütüphaneler
- `OpenCV (cv2)`
- `NumPy`
- `Matplotlib`

---

## 🚀 Çalıştırma
```bash
pip install opencv-python numpy matplotlib
````

Ardından Jupyter Notebook üzerinde çalıştırabilirsiniz:

```bash
jupyter notebook esikleme_ve_kontur_analizi.ipynb
```

---

## 🎯 Öğrenilenler

* Görüntü eşikleme ile nesnelerin arka plandan ayrılması
* Kontur bulma algoritmalarının mantığı
* Görüntü analizi için OpenCV’nin temel fonksiyonlarının kullanımı

---

## 📷 Örnek Görsel

Kodun sonunda yeşil çizgilerle tespit edilen nesne sınırları gösterilmektedir:

```python
cv2.drawContours(my_bgr_img, countur, -1, (0,255,0), 2)
```

