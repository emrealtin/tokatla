# Can Yaman Tokat Simülatörü v1

Tarayıcıda çalışan, tek sayfalık eğlenceli bir tokat simülatörü.

## Özellikler

- Tokat butonuna basıldığında skor artar.
- Web Audio API ile anlık tokat sesi üretilir.
- Yüz görseli geçici olarak tepki (ağlayan yüz) verir.
- Sol/sağ el animasyonu ve yazı efektleri çalışır.
- Mobil cihazlarda dokunma (`pointerdown` / `touchstart`) ile ses tetikleme desteği vardır.

## Proje Yapısı

- `index.html`: Tüm HTML, CSS ve JavaScript kodu
- `images.webp`: Normal yüz görseli
- `crying-image.png`: Tokat sonrası tepki görseli
- `sudo.jpg`: Ek görsel dosyası

## Nasıl Çalıştırılır?

Bu proje herhangi bir build adımı gerektirmez.

1. Proje klasörünü açın.
2. `index.html` dosyasını tarayıcıda açın.
3. `Tokatla!` butonuna basarak oyunu oynayın.

## Mobil Ses Notu

Mobil tarayıcılarda sesin çalışması için ses motoru kullanıcı etkileşimi sırasında başlatılır. Bu nedenle ilk dokunuştan itibaren tokat sesi duyulmalıdır.

## Sürüm

`v1`
