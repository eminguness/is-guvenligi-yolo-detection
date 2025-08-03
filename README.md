# İş Sağlığı ve Güvenliği - YOLO Nesne Tespiti Projesi

Bu proje, YOLOv8 kullanarak iş sağlığı ve güvenliği uygulamalarında nesne tespiti yapmayı amaçlamaktadır.

## 📋 Proje Hakkında

Bu proje, inşaat sektöründe güvenlik ekipmanlarının (kask, yelek, vb.) otomatik tespiti için geliştirilmiş bir YOLO tabanlı nesne tespit sistemidir.

## 🚀 Özellikler

- YOLOv8 ile nesne tespiti
- İş güvenliği ekipmanları tespiti
- Eğitim sonuçları ve metrikler
- Jupyter Notebook ile analiz

## 📊 Eğitim Sonuçları

Model 10 epoch boyunca eğitilmiştir:

- **Final mAP50**: 0.365
- **Final mAP50-95**: 0.239
- **Precision**: 0.567
- **Recall**: 0.380

## 📁 Proje Yapısı

```
├── src/
│   └── is_sagligi_güvenligi.ipynb    # Ana analiz notebook'u
├── models/
│   └── best.pt                        # En iyi model (Git LFS)
├── results/
│   ├── results.csv                     # Eğitim metrikleri
│   ├── args.yaml                      # Eğitim parametreleri
│   ├── confusion_matrix.png            # Karışıklık matrisi
│   ├── PR_curve.png                   # Precision-Recall eğrisi
│   ├── F1_curve.png                   # F1 skor eğrisi
│   └── *.png                          # Diğer grafikler ve sonuçlar
├── docs/
│   └── Rapor.docx                     # Detaylı rapor
├── YoloResults/                       # Orijinal YOLO çıktıları
└── README.md
```

## 🛠️ Kurulum

1. Repository'yi klonlayın:
```bash
git clone https://github.com/eminguness/is-guvenligi-yolo-detection.git
cd is-guvenligi-yolo-detection
```

2. Gerekli paketleri yükleyin:
```bash
pip install -r requirements.txt
```

3. Jupyter Notebook'u çalıştırın:
```bash
jupyter notebook src/is_sagligi_güvenligi.ipynb
```

## 📈 Kullanım

1. `src/is_sagligi_güvenligi.ipynb` dosyasını açın
2. Model eğitimi ve test sonuçlarını inceleyin
3. Kendi verilerinizle test edin

## 📝 Gereksinimler

- Python 3.8+
- PyTorch
- Ultralytics (YOLOv8)
- OpenCV
- Jupyter Notebook

## 🤝 Katkıda Bulunma

1. Fork yapın
2. Feature branch oluşturun (`git checkout -b feature/yeni-ozellik`)
3. Commit yapın (`git commit -am 'Yeni özellik eklendi'`)
4. Push yapın (`git push origin feature/yeni-ozellik`)
5. Pull Request oluşturun



## 👥 İletişim

- **Proje Sahibi**: Emin Güneş
- **Email**: emingunes723@gmail.com

---


⭐ Bu projeyi beğendiyseniz yıldız vermeyi unutmayın!
