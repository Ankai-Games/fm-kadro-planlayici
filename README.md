# FM Kadro Planlayıcı PWA

Bu paket tablet üzerinden GitHub'a yüklenip ücretsiz yayınlanabilecek PWA sürümüdür.

## İçindekiler

- `index.html` — uygulamanın kendisi
- `manifest.webmanifest` — PWA ayarları
- `service-worker.js` — çevrimdışı çalışma dosyası
- `icons/` — uygulama ikonları

## Tablette test

1. ZIP dosyasını aç.
2. `index.html` dosyasını Chrome ile aç.
3. Uygulamayı dene.

## GitHub Pages ile yayınlama

1. GitHub hesabına gir.
2. Yeni repository oluştur: `fm-kadro-planlayici`
3. Bu klasördeki dosyaları yükle.
4. Repository içinde `Settings` → `Pages`.
5. Source olarak `Deploy from a branch` seç.
6. Branch: `main`, folder: `/root`.
7. Save.
8. Birkaç dakika sonra GitHub sana canlı link verir.

## Telefona/tablete uygulama gibi kurma

1. GitHub Pages linkini Chrome'da aç.
2. Menüden `Ana ekrana ekle` seç.
3. Uygulama ikonla açılır.

## Play Store yolu

PWA yayına çıktıktan sonra bunu Play Store'a koymak için sonraki aşamada:
- Bubblewrap / PWABuilder ile Android paketi üretilir.
- Play Console'a `.aab` olarak yüklenir.

Bu aşamada Android Studio'ya gerek kalmadan bulut veya PWABuilder üzerinden ilerleyebiliriz.
