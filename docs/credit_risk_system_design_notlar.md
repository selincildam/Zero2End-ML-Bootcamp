## Credit Risk Model – System Design
Bir müşterinin kredi geri ödeme riskini ölçmek, karar almak ve bu kararları operasyonel hale getiren uçtan uca sistem.

---

## Database
Kredi riskinde kullanılan tüm müşteri, işlem ve başvuru verilerinin tutulduğu ana veri kaynağı.

### Customer
Müşteriye ait temel bilgiler.

- **Demografi:** Yaş, cinsiyet vb.  
- **Meslek:** Çalışma durumu, sektör  
- **Gelir / Maaş:** Aylık kazanç  
- **Varlık – Ev – Araba:** Finansal güç göstergeleri  
- **Hesap bakiyesi:** Mevcut likidite
- vb.

### Transaction
Müşterinin finansal hareketleri.

- Harcama, ödeme, gecikme gibi davranış verileri

### Input Tablosu (KKB & banka)
Modelde kullanılan özet ve türetilmiş değişkenler.

- **KKB Genişliği:** Kredi geçmişinin uzunluğu  
- **KKB Score:** Kredi notu  
- **BBE Score:** Bireysel Borçluluk Endeksi 
- **RL (Risk Level):** Risk seviyesi

### Başvuru Tablosu
Kredi başvurusuna ait bilgiler.

### Kullandırım Tablosu
Onaylanan kredilerin kullandırım detayları.

---

## Analizler
Model ve stratejinin performansını ölçen çalışmalar.

- **Onay / Kullandırım:** Kaç başvuru onaylandı, kaçı kullanıldı  
- **Geçiş Analizleri:** Müşterinin risk sınıfı zamanla nasıl değişti  
- **Geçiş Matrisleri:** Risk segmentleri arası geçiş olasılıkları  
- **Etki Analizleri:** Kural veya model değişimi sonucu ne oldu

---

## ML Modelleri
Risk ve değer tahmini yapan modeller.

- **Income Model:** Gerçek gelir tahmini  
- **Segmentasyon:** Benzer müşterileri gruplama  
- **PD Model:** Temerrüt etme olasılığı (Probability of Default)

---

## Strateji
Model çıktılarının iş kararına dönüşmesi.

- Limit, faiz, onay eşiği gibi kararların belirlenmesi  
- **NPL (Non-Performing Loan):** Batık kredi oranını yönetme

---

## Kurallar
Modeli tamamlayan karar mekanizmaları.

- **Regülâtif Kurallar:** Yasal zorunluluklar  
- **Uzman Kurallar:** İş bilgisine dayalı kurallar  
- **Modelden Çıkan Kurallar:** ML çıktısına bağlı eşikler

---

## Simülasyon
Farklı senaryolarda (eşik, kural, model) sonuçların önceden test edilmesi.

---

## Pazarlama
Risk + gelir odaklı büyüme.

- **Segment Bulma:** Hedef müşteri grupları  
- **Propensity:** Ürün alma olasılığı

---

## Danışmanlık
Kredi risk sistemlerinin tasarımı ve iyileştirilmesinde destek veren firmalar.

- McKinsey  
- Deloitte  
- Prometeia  
- vb.

