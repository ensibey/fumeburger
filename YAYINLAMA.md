# Füme Burger QR Menü — Vercel'de Yayınlama

## Adımlar
1. https://vercel.com adresine gir, GitHub/Google ile giriş yap.
2. "Add New → Project" yerine en kolayı: https://vercel.com/new sayfasına bu klasörü sürükle-bırak
   (veya `npx vercel` komutuyla bu klasörden yayınla).
3. **Önemli:** Proje adını `fume-burger` yap → siten `https://fume-burger.vercel.app` adresinde yayınlanır.
   `qr-menu.png` dosyasındaki QR kod tam olarak bu adrese yönlendirir.
4. Farklı bir proje adı/alan adı kullanırsan söyle, QR'ı yeniden oluştururum.

## Dosyalar
- `index.html` — Tümü (tüm menü tek sayfada)
- `burgerler.html`, `tabak-lezzetler.html`, `citirlar.html`, `sicaklar.html`, `icecekler.html` — kategori sayfaları
- `style.css` — ortak tasarım (renk/fiyat değişikliği burada tek yerden yapılır)
- `qr-menu.png` — masalara/baskıya hazır QR kod (1230×1230 px, yüksek hata toleransı)

## Not
Fiyatlar Google Maps'teki menü fotoğraflarından alındı. Fiyat değişince `index.html` içinde
ilgili rakamı düzenlemen yeterli — site otomatik güncellenir (yeniden deploy gerekir).
