# SİNODER Web Sitesi

Bu depo, SİNODER için hazırlanmış tek sayfalık, duyarlı (responsive) HTML/CSS/JavaScript web sitesini içerir.

## Dosya yapısı

```text
sinoder-github/
├── index.html
├── README.md
└── assets/
    ├── sinoder-logo.jpeg
    ├── sinoder-konsept.jpeg
    ├── yonetim-01.jpg
    ├── yonetim-02.jpg
    ├── yonetim-03.jpg
    ├── yonetim-04.jpg
    ├── yonetim-05.jpg
    ├── yonetim-06.jpg
    ├── yonetim-07.jpg
    ├── yonetim-08.jpg
    ├── yonetim-09.jpg
    └── yonetim-10.jpg
```

## GitHub'a yükleme

1. GitHub'da yeni bir repository oluşturun.
2. `index.html` ve `README.md` dosyalarını yükleyin.
3. `assets` adlı klasör oluşturup görsellerinizi bu klasöre yükleyin.
4. Repository içindeki **Settings → Pages** bölümüne girin.
5. **Deploy from a branch** seçin.
6. Branch olarak `main`, klasör olarak `/ (root)` seçip kaydedin.
7. GitHub Pages adresiniz yayımlandığında siteniz açılır.

## Görsel dosyaları

Dosya adları ve büyük/küçük harfleri HTML'deki adlarla aynı olmalıdır. Logo, konsept görseli ve yönetim kurulu fotoğrafları bu pakete dahil değildir; kendi görsellerinizi `assets` klasörüne yükleyin. Görseller eklenene kadar yönetim kartlarında numaralı yer tutucular görünür.

## Özelleştirme

- Yönetim kurulu isimlerini `index.html` içindeki `Üye Adı Soyadı` metinleriyle değiştirin.
- Yönetim fotoğraflarını `assets/yonetim-01.jpg` vb. adlarla yükleyin.
- IBAN kopyalama özelliğini etkinleştirmek için JavaScript içindeki `const IBAN = "";` satırına yalnızca yönetim tarafından doğrulanmış IBAN bilgisini girin.
- Telefon ve sosyal medya bağlantıları HTML içinde düzenlenebilir.

## İletişim formu hakkında

Form, mesajı `+90 544 710 55 02` numarasına WhatsApp üzerinden hazırlar. Kullanıcının WhatsApp uygulamasında mesajı ayrıca göndermesi gerekir. Bu statik GitHub Pages sitesi tek başına e-posta gönderimi veya veritabanına kayıt yapmaz.
