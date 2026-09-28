# 🎯 YKS Kontenjan ve Kayıt Analizi

> İlk tercihte yerleşip kayıt olan öğrenci istatistikleri ve ek tercihe esas kalan kontenjanlar

**[🔗 Canlı Demo →](https://serkankisin.github.io/yks-kontenjan-analiz)**

---

## 📊 Bu Araç Ne İşe Yarar?

Bu araç, ÖSYM YKS verilerini kullanarak:

- **İlk yerleştirmede kayıt olan** öğrenci sayılarını hesaplar
- **Ek tercihe esas kalan kontenjanları** gösterir
- **Üniversite, program ve şehir bazında** detaylı filtreleme sunar
- **Doluluk oranlarını** karşılaştırmalı olarak analiz eder

## 🗂️ Desteklenen Yıllar

| Yıl | Durum | Veri |
|-----|-------|------|
| 2026 | ✅ Aktif | Lisans + Ön Lisans |
| 2027 | 🔜 Planlandı | — |

> Her yıl yeni veriler eklenerek yıllar arası karşılaştırma yapılabilecektir.

## ✨ Özellikler

- 🎛️ **Gelişmiş Filtreleme** — Seviye, üniversite türü, şehir, fakülte, puan türü, dil, burs türü
- 🔍 **Akıllı Arama** — Program adı veya kodu ile hızlı arama
- 📈 **3 Farklı Görünüm** — Program listesi, üniversite toplamları, program toplamları
- 🏫 **Üsküdar Üniversitesi Odaklı** — Özel filtreleme ve sıralama seçenekleri
- 📱 **Mobil Uyumlu** — Her cihazda sorunsuz çalışır
- 🌗 **Karanlık/Aydınlık Tema** — Sistem tercihine uyum sağlar
- ⚡ **Hızlı** — Tamamen istemci tarafında, sunucu gerektirmez

## 📐 Hesaplama Yöntemi

```
Kayıt Olan = Kontenjan − Genel Ek Kontenjan
Boşalan    = Genel Ek Kontenjan
```

- Ek Kılavuz'da yer almayan programlarda boşalan yer olmadığı varsayılır
- Program bazlı görünümde farklı burs türleri tek satırda toplanır
- Oran sütunları yüzde (%) olarak gösterilir

## 🛠️ Teknolojiler

- **HTML/CSS/JS** — Tek dosyada, bağımlılıksız
- **ÖSYM Kılavuz Verileri** — Resmi veri kaynaklarından derlenmiştir

## 📝 Lisans

Bu proje açık kaynaklıdır. Resmi sonuçlar için ÖSYM kılavuzlarını esas alınız.

---

**Geliştirici:** [Serkan Kişin](https://github.com/serkankisin) · Üsküdar Üniversitesi Öğrenci İşleri Daire Başkanlığı
