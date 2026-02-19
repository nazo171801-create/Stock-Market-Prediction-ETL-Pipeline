## End-to-End Stock Market Prediction & ETL Pipeline

Bu proje, Nasdaq 100 endeksindeki hisse senetleri için uçtan uca bir veri işleme ve tahminleme hattı (pipeline) sunar.

## 🚀 Proje Özeti
Proje kapsamında Yahoo Finance üzerinden çekilen veriler büyük veri araçları ile işlenmiş ve makine öğrenmesi modelleri ile "Al-Sat-Tut" sinyalleri üretilmiştir.

### 🛠 Kullanılan Teknolojiler
- **Veri İşleme (ETL):** PySpark
- **Veritabanı:** PostgreSQL
- **Analiz & Modelleme:** Python (Pandas, Scikit-learn)
- **Veri Kaynağı:** Yahoo Finance API (yfinance)

### 📈 Uygulanan Adımlar
1. **ETL Hattı:** PySpark kullanılarak 10 yıllık tarihsel veriler çekildi ve temizlenerek PostgreSQL veritabanına aktarıldı.
2. **Özellik Mühendisliği:** Teknik göstergeler ve fiyat hareketleri kullanılarak model için girdiler hazırlandı.
3. **Modelleme:** **Random Forest** algoritması kullanılarak borsa trendleri tahmin edildi.
4. **Performans Analizi:** Strateji başarısı ROI (Yatırım Getirisi), Net Kar, Win Rate ve Beta metrikleri ile ölçüldü.

## 📊 Sonuçlar
- Model, belirlenen periyotlarda piyasa endeksine karşı performans takibi yapabilmektedir.
- Tüm tahminleme süreci PyCharm üzerinden otomatik bir pipeline olarak kurgulanmıştır.
