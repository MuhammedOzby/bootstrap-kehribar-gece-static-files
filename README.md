# Kehribar Gece — Statik dosyalar

Orijinal Kehribar Gece yönetim panelinin hazır HTML, CSS, JavaScript ve font dosyaları.
Ana Bootstrap sürümü **5.3.8** olarak sabittir. Yeni kararlı sürüm çıktığında güncelleme ayrıca değerlendirilir.

## Önizleme

[Panel](index.html) · [Örnek galerisi](examples.html) · [Bileşenler](components.html) · [Boş başlangıç](blank.html)

Sayfaları doğrudan tarayıcıda açabilirsiniz. Kurulum, derleme ve CDN gerekmez.
Aydınlık, karanlık ve sistem görünümü desteklenir. Tüm veriler örnektir.

Diğer sayfalar: [Müşteriler](customers.html), [Fatura](invoice.html), [Giriş](login.html), [Profil](profile.html), [Fiyatlandırma](pricing.html), [404](404.html), [500](500.html), [Bakım](maintenance.html).
Eski `examples/` bağlantıları ilgili sayfalara yönlenir.

## Kendi sayfanızda kullanın

```html
<html lang="tr" data-bs-theme="dark">
<head>
  <script src="dist/js/theme.js"></script>
  <link rel="stylesheet" href="dist/css/kehribar-gece.min.css">
</head>
<body>
  <!-- Sayfa içeriği -->
  <script src="dist/js/bootstrap.bundle.min.js"></script>
  <script src="dist/js/layout.js"></script>
</body>
</html>
```

Tema CSS dosyası Bootstrap bileşenlerini içerir. Bu kullanımda ayrıca `bootstrap.min.css` yüklemeyin.
`kehribar-gece.css`, aynı derlenmiş temanın uyumluluk kopyasıdır; önceki tema katmanı değildir.
`pages.css` ve `components.css` ilgili örnek sayfaların ek stilleridir.
`dist/css/bootstrap*.min.css` dosyaları temasız Bootstrap 5.3.8 çıktılarıdır.
Fontların çalışması için `dist/css/` ile `dist/fonts/` dizin yapısını koruyun.

## Kaynak ve güncelleme

[Geliştirme deposu](https://github.com/MuhammedOzby/bootstrap-kehribar-gece) içindeki `kehribar-gece/` klasörü kaynak alınır.
Bu depo yalnızca hazır statik dosyaları dağıtır. Orijinal tema Bootstrap 5.3.8 ve Sass 1.78.0 ile derlenmiştir.
Go `html/template` örnekleri `templates/go/` klasöründedir. `AssetBase` değerini dağıtımınızın `dist/` adresine ayarlayın.
`manifest.json`, dağıtım sürümlerini ve dosyaların SHA-256 özetlerini içerir.

## Lisans

Kişisel katkılar: [LICENSE](LICENSE). Bootstrap, Popper ve Source Sans 3: [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).
