# Almanca Öğrenme Portalı

Bu klasör GitHub Pages için hazırdır.

## Dosyalar
- `index.html`: Portalın ana sayfası
- `manifest.webmanifest`: PWA bilgileri
- `sw.js`: Çevrimdışı uygulama kabuğu
- `icon-180.png`, `icon-192.png`, `icon-512.png`: Uygulama ikonları

## GitHub Pages kurulumu
1. Bu paketteki dosyaların tamamını repository kök dizinine yükleyin.
2. GitHub'da **Settings > Pages** bölümünü açın.
3. **Deploy from a branch** seçeneğini kullanın.
4. Branch olarak `main`, klasör olarak `/ (root)` seçin ve kaydedin.
5. İlk yayından sonra sayfayı bir kez çevrimiçi açın. Sonraki açılışlarda uygulama kabuğu çevrimdışı kullanılabilir.

## Güncelleme notu
Yeni sürüm yüklediğinizde `sw.js` içindeki `CACHE_NAME` değerini değiştirin. Böylece eski önbellek temizlenir.
