# Almanca Öğrenme Portalı

Mobil ve masaüstü uyumlu, JSON tabanlı Almanca okuma ve quiz portalı.

## Özellikler

- Almanca, Türkçe ve İngilizce okuma görünümü
- 10 soruluk quiz ve ilerleme takibi
- Kelime havuzu ve JSON yedekleme
- Sesli okuma
- Mobil paragraf kartı ve 240 ms yönlü geçiş
- Mobil çalışma arşivi ve test durum takibi
- Temiz yazdırma / PDF görünümü
- PWA desteği

## GitHub Pages ile yayınlama

1. Bu klasörün içeriğini GitHub deposunun ana dizinine yükleyin.
2. GitHub deposunda **Settings > Pages** bölümüne gidin.
3. **Deploy from a branch** seçeneğini seçin.
4. Branch olarak `main`, klasör olarak `/ (root)` seçip kaydedin.
5. Birkaç dakika sonra GitHub Pages adresiniz hazır olur.

## Kullanım

Portal açıldıktan sonra uygulamanın beklediği yapıya uygun `.json` çalışma dosyalarını **Dosya Aç** düğmesiyle yükleyin.

## Yerel çalıştırma

Service Worker nedeniyle dosyayı doğrudan açmak yerine basit bir yerel sunucu kullanın:

```bash
python3 -m http.server 8080
```

Ardından tarayıcıda `http://localhost:8080` adresine gidin.

## Dosyalar

- `index.html`: Ana uygulama
- `manifest.webmanifest`: PWA tanımı
- `sw.js`: Çevrimdışı önbellek
- `icon-180.png`, `icon-512.png`: Uygulama simgeleri
