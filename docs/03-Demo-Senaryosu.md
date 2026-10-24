# 03 · 90 SANİYELİK DEMO SENARYOSU
> Tek ekran, tek anlatıcı, tek “vay” anı. Gerçek GPU/veri yok; simülasyon olduğunu söyle.
>
> **Tıklanabilir demo:** `karbon-hat-demo.html` — tarayıcıda aç, “Tedarikçi bul” → “Seç” → “Dosyayı üret” → “Teslim edildi”.

## Akış

| Süre | Ekran | Ne tıklanır? | Ne söylenir? |
|---|---|---|---|
| 0–10 | Alıcı paneli | “Yeni RFQ” | “500 ton çelik, CBAM-ready, Q1 teslim.” |
| 10–25 | Tedarikçi listesi | 3 kart | “Üç doğrulanmış tedarikçi: skor, karbon, fiyat.” |
| 25–40 | Toplam maliyet | “Toplam maliyet” sekmesi | “C en ucuz fiyat ama CBAM ile en pahalı.” |
| 40–55 | Seçim | B’yi seç | “Toplamda en iyi B; dosyayı üret.” |
| 55–70 | Dosya | “CBAM + DPP dosyası” | “Fatura + sayaç + tedarikçi verisi; denetçi imzası.” |
| 70–85 | QR | QR’ı büyüt | “Gümrük okutur; kaynak ve audit trail görünür.” |
| 85–90 | Skor güncellemesi | “Teslim edildi” | “Gerçek veri skoru günceller; ağ öğrenir.” |

## Ekran ekran

### 1. Alıcı paneli
- Başlık: “RFQ oluştur.”
- Alanlar: ürün (çelik), miktar (500 t), varış (Almanya), termin (Q1), şart (CBAM-ready).
- Buton: “Tedarikçi bul.”

### 2. Tedarikçi listesi
- A: skor 92, 1,8 tCO₂/t, €620/t.
- B: skor 85, 2,1 tCO₂/t, €590/t.
- C: skor 78, 2,4 tCO₂/t, €570/t.
- Her kartta “doğrulanmış” rozeti + son doğrulama tarihi.

### 3. Toplam maliyet
- Fiyat + CBAM + lojistik + risk.
- C: €285k + €96k = €381k.
- B: €295k + €84k = €379k.
- A: €310k + €72k = €382k.
- Kırmızı uyarı: “En ucuz fiyat, en yüksek toplam maliyet olabilir.”

### 4. Seçim
- B seçilir.
- “Dosya üret” butonu.
- Küçük not: “Sözleşme/PO burada değil; biz uyum dosyasını üretiyoruz.”

### 5. Dosya
- Sol: fatura, sayaç, tedarikçi verisi.
- Sağ: CBAM + DPP özeti.
- Alt: “Doğrulayıcı: Akredite Denetçi A (simülasyon).”
- Buton: “QR oluştur.”

### 6. QR
- Büyük QR; yanında “Bu dosya 3 kaynaktan doğrulandı.”
- Audit trail: kim, ne zaman, hangi veri.

### 7. Skor güncellemesi
- “Teslim edildi” → B’nin skoru 85 → 87.
- Grafik: skor zaman içinde yükseliyor.
- Kapanış cümlesi: “Satın almadan önce skorla, sonra gümrükten geçir.”

## Demo öncesi kontrol

- [ ] Tarayıcı tam ekran; bildirimler kapalı.
- [ ] İnternet yoksa video yedek.
- [ ] QR ekranı okunur boyutta.
- [ ] Sayılar birbiriyle tutarlı (500 t × fiyat; CBAM €80/t`.
- [ ] “Simülasyon” etiketi görünür.
- [ ] 90 saniye prova; 80 saniyede bitir.

## Ne gerçek, ne simülasyon?

| Gerçek | Simülasyon |
|---|---|
| Skor mantığı ve ağırlıklar | Tedarikçi verileri |
| Toplam maliyet hesabı | CBAM sertifika fiyatı (€80/tCO₂ `[A]`) |
| Dosya akışı | Denetçi imzası |
| QR/audit mantığı | Gümrük okutma |

> Jüriye “demo verisi simülasyon” de; abartma. Güven, abartıdan değil, tutarlılıktan gelir.
