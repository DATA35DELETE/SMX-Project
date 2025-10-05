<<<<<<< HEAD
# Stored Memory X (SMX)

## Hakkında

SMX porjesi, Web tabanlı bir elektronik bir taslak kitabı sunar. Yazar istenilen bir konu üzerine başlıklar, metinler, listeler ve tablo gibi imkanlarla klasik bir kitap yazmak yerine, daha modern ve daha dinamik bir kitap yazmış olur. Ayrıca SMX, genel olarak bir yazılım dilinin öğretici bir kitap yazmak üzerine kuruluğu olduğundan `pre` + `code`, Hljs ile de kodların renklendirmesini sağlar. Böylelikle daha renkli ve daha cazip kitaplar yazılabilir.

## Özellikleri

SMX projesini öne çıkan özellikleri şunlardır:

- Web tabanlı olup, internet tarayıcısına sahip olan tüm cihazlarda sağlıklı bir şekilde çalıştırılabilir
- Hljs ile yazılım dillerinin kodları renkli gözükür
- Hazır bir taslak sunar
- Arka plana fotoğraf/video konulabilir
- Düzenli bir çalışma ortamı sağlar
- `forker.exe` ile kolay bir şekilde proje forklanabilir

## Kurulum

```bash
git clone https://github.com/kullaniciadi/proje-adi.git
```

## Yapısı

```stylus
SMX
│   hljsLICENSE // Hljs'nin lisansı
│   LICENSE // MIT lisansı
│   main.css // Ana still dosyası
│   main.js // Ana javascpirt dosyası. Arka plana video eklemek için
│   README.md // Ana Markdown dosyası
│   READMEtr.md // Türkçe Markdown dosyası
│   X.roadMap.md // Elektronik kitap için yol haritası
│   SMXForker.exe // Otomatik elektronik kitap oluşturmak için araç
│
├───hljs // Highlight dosyaları
│       highlight.min.js
│       number.min..js
│       vs2015.min.css
│
└───Subjects // Dersler/Sayfalar
    │   demo.html // Sayfa taslağı
    │
    ├───img // Sayfalar için kullanılan fotoğraflar
    │   │   pp.png // Sayfa başlığı
    │   │   example.png // Örnek fotoğraf. Yapay zeka ile oluşturuldu
    │   │
    │   └───wallpapers // Duvar kağıtları
    │           example.png // Sayfa arka plan fotoğrafı. Yapay zeka ile oluşturuldu
    │
    └───vid // Sayfa arka plan videoları
            example.mp4 // Örnek video
```
=======
# SMX-Project
A new generation e-book draft.
>>>>>>> 260cd4a0988a4d7fdcfd25d5894ec2dacf9167ae
