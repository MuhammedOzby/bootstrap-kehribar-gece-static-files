# Kehribar Gece — Static Files & Examples

Kehribar Gece için kullanıma hazır statik dosyalar ve Bootstrap örnekler sayfası yaklaşımıyla hazırlanmış HTML kılavuzu.

> **Önizleme:** Şu anki Bootstrap CSS/JS dosyaları 6.0.0-alpha.1 sürümüne aittir. `kehribar-gece.css` ilk tema katmanıdır; Mac'te bulunan geçmiş özelleştirmeler henüz geri aktarılmamıştır. Bu bir üretim sürümü değildir.

## Örnek galerisi

**[Örnekler / Galeri](examples/index.html)** — diğer sayfalara bağlantılar ve hızlı başlangıç

| Örnek | Açıklama |
| --- | --- |
| [Admin Dashboard](examples/admin.html) | Sidebar, KPI'lar, temsili grafik ve kayıt tablosu |
| [Sign-in](examples/signin.html) | Sunucuya veri göndermeyen form taslağı |
| [Pricing](examples/pricing.html) | Üç sütunlu fiyatlandırma şablonu |
| [Components](examples/components.html) | Renkler, düğmeler, alanlar ve kod örnekleri |

Bu örneklerin tamamı bağımsız HTML dosyalarıdır. İnternet/CDN bağlantısı veya build gerektirmez. `examples/assets/examples.css`, örneklere ait yardımcı stil dosyasıdır; dağıtılan temanın parçası olarak düşünülmemelidir.

## CSS / JS kullanımı

```html
<link rel="stylesheet" href="dist/css/bootstrap.min.css">
<link rel="stylesheet" href="dist/css/kehribar-gece.css">
<script src="dist/js/bootstrap.bundle.min.js"></script>
```

Örneği yerel görmek için depoyu ZIP olarak indirip `examples/index.html` dosyasını aç. Dosya yolları dizin düzenine göre göreli tanımlanmıştır.

## Dağıtım dosyaları

- `dist/css/bootstrap*.min.css`: Bootstrap temel, grid, reboot ve utility çıktıları
- `dist/css/kehribar-gece.css`: Önizleme niteliğinde kişisel tema katmanı
- `dist/js/bootstrap.bundle.min.js`: Bootstrap JavaScript bundle
- `examples/`: Galeri ve HTML şablonları

**Kaynak / geliştirme deposu:** [bootstrap-kehribar-gece](https://github.com/MuhammedOzby/bootstrap-kehribar-gece)

## Özelleştirmelerin geri aktarılması

Bu depodaki renkler ve örnek stiller, daha önce Mac üzerinde geliştirilmiş özgün SCSS / CSS düzeninin yerine geçmez. Eski kaynaklar erişilebilir olduğunda ayrı karşılaştırma ve entegrasyon yapılmalıdır.

## Lisans

Bu depodaki kişisel katkılar için [LICENSE](LICENSE); yeniden dağıtılan Bootstrap kodunun atıfları ve orijinal MIT lisansı için [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).
