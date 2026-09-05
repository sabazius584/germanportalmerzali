# Almanca Öğrenme Portalı

Tek sayfalık, JSON tabanlı Almanca çalışma portalı. Mobil arayüz, paragraf görünümü, test modu, kelime havuzu, çalışma geçmişi, yazdırma/PDF ve renk paleti özelliklerini içerir.

## GitHub Pages ile yayınlama

1. Bu paketin içeriğini yeni bir GitHub deposunun kök dizinine yükleyin.
2. GitHub'da **Settings > Pages** bölümünü açın.
3. **Deploy from a branch** seçeneğini seçin.
4. Branch olarak `main`, klasör olarak `/ (root)` seçip kaydedin.
5. Yayın adresi birkaç dakika içinde oluşur.

## Yerel çalıştırma

Service Worker nedeniyle dosyayı doğrudan açmak yerine yerel sunucu kullanın:

```bash
python3 -m http.server 8080
```

Ardından `http://localhost:8080` adresini açın.

## Dosyalar

- `index.html`: Ana portal
- `manifest.webmanifest`: PWA tanımı
- `sw.js`: Çevrimdışı önbellek
- `icon-180.png`, `icon-192.png`, `icon-512.png`: Uygulama ikonları

## Not

Portal çalışma içeriklerini kullanıcı tarafından seçilen JSON dosyalarından yükler. Google ses kaynağı ağ erişimi gerektirebilir; tarayıcı ses kaynağı cihaz desteğine bağlıdır.
