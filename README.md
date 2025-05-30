# Gezinomi Kural Tabanlı Müşteri Segmentasyonu

Bu proje, Miuul tarafından sağlanan **miuul_gezinomi.xlsx** veri seti ile gerçekleştirilmiş kural tabanlı segmentasyon çalışmasıdır. Amaç, otel rezervasyon verileri üzerinden müşteri davranışlarını analiz etmek ve belirli segmentlere ayırmaktır.

---
## Proje Kapsamı

- Veri setinin incelenmesi ve genel bilgilerin çıkarılması
- Eksik ve aykırı değer analizi
- Özellik mühendisliği (feature engineering)
- SaleCheckInDayDiff değişkeni üzerinden segmentler oluşturulması
- Segment bazlı analiz ve çıkarımlar

---
## Kullanılan Teknolojiler

- Python
- Pandas, NumPy
- Jupyter Notebook

---
## Segmentler

- **Last Minuters**: Rezervasyonunu son dakikada yapanlar
- **Planners**: Ortalama sürede rezervasyon yapanlar
- **Early Bookers**: Tatilini çok önceden planlayanlar

---
##  Öne Çıkanlar

- Aykırı değerlerle başa çıkmak için *Winsorizing* yöntemi uygulandı
- Eksik veriler titizlikle analiz edilerek minimal bilgi kaybı ile temizlendi
- Segmentler arasında fiyat, sezon ve konsept analizleri yapıldı
- Müşteri profilleri üzerinden öneriler geliştirildi

---
## Öğrendiklerim

- Gerçek bir veri setinde veri temizliğinin önemi
- Segmentasyon için özellik mühendisliği uygulamaları
- Aykırı değerleri silmeden daha yaratıcı çözümler üretmenin etkisi
- Veri odaklı düşünmenin analitik bakış açısını nasıl geliştirdiği

---
## Gelecek Geliştirmeler

- Segment bazlı kişiselleştirilmiş kampanya öneri sistemi geliştirme
- Tahmine dayalı modeller ile müşteri davranışlarını öngörme (ML)
- Web arayüzü eklenerek görselleştirmelerin interaktif hale getirilmesi

---
## Teşekkürler

Bu süreçte hem teknik hem de analitik gelişimime büyük katkı sağlayan **Miuul ekibine** ve **değerli eğitmenimize** içtenlikle teşekkür ederim.

