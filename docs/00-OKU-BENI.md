# KARBON HAT — YARIŞMA PAKETİ
> **24–25 Ekim 2026 · GO Bilişim Vadisi · 42 İstanbul Girişimcilik Kulübü**
> Bu paket, Karbon Hat fikrini yarışmanın istediği formata sokmak için hazırlandı: 5 dakika pitch, 3 dakika Q&A, 10 slayt, 90 saniyelik demo, 48 saatlik plan, jüri soruları ve teslim kontrolü.

## Paket içinde ne var?

| Dosya | Ne işe yarar? |
|---|---|
| `Karbon-Hat-Detayli-Anlatim.pdf` | Ürünü sıfırdan anlatan, kavram sözlüklü, çocuk diliyle açıklamalı 24 sayfalık PDF |
| `01-Urun-Ozeti.md` | Tek sayfada ürün: problem, çözüm, müşteri, iş modeli, skor |
| `02-Pitch-ve-Slaytlar.md` | 5 dakikalık konuşma metni + 10 slaytın içeriği ve konuşmacı notları |
| `03-Demo-Senaryosu.md` | 90 saniyelik demo: hangi ekran, ne tıklanır, ne söylenir |
| `karbon-hat-demo.html` | Tıklanabilir demo: RFQ → skor → toplam maliyet → dosya/QR |
| `04-Juri-Sorulari.md` | 30 zor soru ve 2–3 cümlelik cevaplar |
| `05-48-Saat-Plani.md` | Etkinliğin gerçek takvimine oturmuş saat saat plan |
| `06-Dogrulama-ve-Scorecard.md` | Görüşme soruları, kanıt seviyeleri, scorecard formülü |
| `07-Fiyatlandirma.md` | Fiyatlar, ARR senaryoları, birim ekonomi |
| `08-Riskler.md` | Risk register + öldürücü koşullar |
| `09-Teslim-Checklist.md` | 25 Ekim 15:45 teslim kontrolü ve sunum günü rolleri |
| `10-Kaynaklar.md` | CBAM/DPP tarihleri, kaynaklar, varsayım etiketleri |
| `11-Basvuru-Ozeti.md` | Tek sayfalık başvuru/one-pager |
| `12-Gorusme-Notu-Sablonu.md` | Alıcı/tedarikçi/doğrulayıcı görüşme notu şablonu |

## Bugün için 3 adım

1. **13:15'e kadar:** `01-Urun-Ozeti.md` + `06-Dogrulama-ve-Scorecard.md` oku; 2 alıcı + 2 tedarikçi görüşmesi yap.
2. **17:15 mentor checkpoint:** 1 sayfa ürün özeti + 3 kanıt + 1 risk götür.
3. **25 Ekim 15:45:** `09-Teslim-Checklist.md` ile deck + demo linkini teslim et.

## Claude'a sunum yaptırmak

1. `Karbon-Hat-Detayli-Anlatim.pdf` + `02-Pitch-ve-Slaytlar.md` dosyalarını Claude'a ver.
2. Şu prompt'u ekle:
   > “Bu iki dosyayı kullanarak 10 slaytlık Türkçe startup sunumu oluştur. Her slayt için başlık, 3–5 kısa madde, 50–80 kelimelik konuşmacı notu ve görsel önerisi ver. Ton: güven veren, iddialı ama abartısız. Renk: koyu lacivert + turkuaz. Sayıları `[A]` etiketiyle ver.”
3. Çıkan metni `02-Pitch-ve-Slaytlar.md` ile karşılaştır; uydurma sayı varsa sil.

## Etiketler

- `[A]` = varsayım; birincil görüşmeyle doğrulanmalı.
- `[K]` = kaynak/mevzuat; tarih ve kaynak `10-Kaynaklar.md` içinde.
- `[S]` = simülasyon/demo verisi.

## Dürüstlük notu

- Demo verileri simülasyondur; gerçek müşteri/LOI yoksa “var” denmez.
- Gerçek marka adları (EcoVadis, SAP, Coupa) yalnızca rakip bağlamında geçer; ortaklık ima edilmez.
- Fiyatlar ve pazar büyüklükleri varsayımdır; jüri önünde “bizim modelimizde” diye söylenmeli.
