# Katkı Rehberi

Karbon Hat'a ilgi gösterdiğin için teşekkürler. Bu repo bir hackathon prototipi; amacımız fikri daha iyi test etmek, mevzuata uygun hale getirmek ve çalışan bir demoya dönüştürmek.

## Nasıl katkı verilir?

1. Repoyu fork'la.
2. Yeni bir branch aç: `feat/scorecard-model`, `fix/demo-mobile`, `docs/cbam-kaynak`.
3. Değişikliği yap; demo için `demo/index.html` yeterli (build yok).
4. Pull request aç; ne değiştirdiğini ve neden yaptığını yaz.
5. Büyük değişiklikler için önce issue aç.

## Öncelikli alanlar

- **Scorecard modeli:** Ağırlıklar, veri kalitesi, doğrulama seviyeleri.
- **CBAM/DPP araştırması:** Tarihler, kapsam, doğrulayıcı gereksinimleri, kaynaklar.
- **Demo UI/UX:** Mobil, erişilebilirlik, gerçekçi akış.
- **Görüşmeler:** Alıcı/tedarikçi/doğrulayıcı görüşme notları (`docs/12-Gorusme-Notu-Sablonu.md`).
- **Çeviri:** İngilizce README ve dokümanlar.
- **Test:** Tarayıcı uyumluluğu, klavye erişimi, hata durumları.

## Veri kuralları

- `[A]` = varsayım; hesaplama veya görüş.
- `[K]` = kaynak/mevzuat; link veya kaynak adı.
- `[S]` = simülasyon/demo verisi.
- **Uydurma müşteri, LOI, anket veya pazar verisi yok.** Görüşme yapılmadıysa “varsayım” yaz.
- Gerçek marka adlarını yalnızca rakip/bağlam olarak kullan; ortaklık ima etme.

## Kod stili

- Demo: saf HTML/CSS/JS; framework/build yok.
- Türkçe metin; teknik terimler İngilizce kalabilir.
- Erişilebilirlik: klavye ile gezilebilir, renk kontrastı yeterli, `aria` etiketleri.
- Gizli veri/API anahtarı commit etme.

## Commit mesajı

- `feat: ...`
- `fix: ...`
- `docs: ...`
- `refactor: ...`
- `test: ...`

## Sorular

Issue aç veya `docs/00-OKU-BENI.md` ile başla.
