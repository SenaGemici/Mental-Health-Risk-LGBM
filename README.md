# 🧠 Mental Health Risk Prediction with LightGBM

Bu proje, sentetik bir ruh sağlığı veri seti üzerinde **LightGBM** algoritması kullanılarak geliştirilmiş bir risk tahminleme çalışmasıdır. Projenin temel amacı, yaşam tarzı faktörleri ve aile geçmişi gibi değişkenlerin ruh sağlığı riskleri üzerindeki etkisini analiz etmektir.

## 🚀 Proje Özeti
- **Algoritma:** LightGBM (Light Gradient Boosting Machine)
- **Veri Seti:** Sentetik Ruh Sağlığı Risk Veri Seti (`mental_health_risk_dataset.csv`)
- **Odak Noktası:** Kategorik veri işleme, korelasyon analizi ve özellik önemi (Feature Importance).

## 🛠️ Yapılan İşlemler
1. **Veri Ön İşleme:** `object` tipindeki kategorik sütunlar, LightGBM'in yerel desteğinden faydalanmak için `category` tipine dönüştürüldü.
2. **Keşifsel Veri Analizi (EDA):** Değişkenler arasındaki ilişkiler korelasyon matrisi ile incelendi.
3. **Modelleme:** Veri seti eğitim ve test olarak ayrılarak LightGBM modeli eğitildi.
4. **Değerlendirme:** Model performansı için Confusion Matrix ve Classification Report oluşturuldu.

## 📊 Model Sonuçları
Sentetik veri yapısı nedeniyle model yüksek doğruluk oranlarına ulaşmıştır:
- **Accuracy:** %100
- **F1-Score:** 1.00

### Özellik Önemi (Feature Importance)
Modelin karar verirken en çok ağırlık verdiği değişkenler:
1. Haftalık Fiziksel Aktivite Saatleri
2. Ailede Ruhsal Hastalık Geçmişi
3. Uyku Kalitesi



