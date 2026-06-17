# Maaş Kasa PWA Ana Ekran Sürümü

Bu paket telefonun ana ekranına eklenebilir PWA sürümüdür.

## En doğru kullanım

1. Bu klasörü bir hosting'e yükle:
   - Netlify
   - Vercel
   - GitHub Pages
   - kendi web hosting'in

2. Telefonda linki aç:
   - iPhone: Safari ile aç → Paylaş → Ana Ekrana Ekle
   - Android: Chrome ile aç → üç nokta → Ana ekrana ekle / Uygulamayı yükle

3. İlk açılıştan sonra offline çalışır.

## Neden direkt dosyadan ana ekrana eklenmez?

Telefonlar yerel HTML dosyasını genelde gerçek uygulama/PWA gibi kurmaz. Ana ekrana ekleme, manifest ve service worker'ın çalışması için dosyanın HTTPS linkinden açılmasını ister.

## Veriler

Veriler cihazdaki tarayıcı hafızasında saklanır. Telefon değişmeden önce uygulama içinden yedek al.
