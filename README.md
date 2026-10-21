# Düzel Grup Sunucu Yedekleme — bilgilendirme sitesi

Bu ayrı, herkese açık depo yalnızca yedekleme aracını tanıtan statik sayfaları barındırır.

## Yayın kapsamı

- `dist/index.html`: uygulama tanıtımı ve iletişim.
- `dist/gizlilik.html`: Drive izni, veri kullanımı ve erişimi kaldırma açıklamaları.
- `dist/kullanim-kosullari.html`: kurum içi kullanım kapsamı.
- `dist/styles.css`: harici bağımlılığı olmayan, uyumlu görünüm.

GitHub Pages kaynağı: `main` dalındaki `/docs` dizini (yayın sırasında `dist` dosyaları `docs` altında eşlenir).

Bu depoya uygulama kaynak kodu, `.env`, OAuth kimlik bilgileri, erişim belirteçleri, kurtarma anahtarları, gerçek müşteri/personel verileri veya yedek dosyaları eklenmez.

## Doğrulama ve sınırlar

Sayfalar betik, form, çerez, izleme veya harici yazı tipi kullanmaz. Gerçek yedekleme işlemini çalıştırmaz. Yayın, OAuth onayının veya yedekleme/geri yükleme testinin tamamlandığı anlamına gelmez.

Yedekleme kurulumu sürmektedir. Metinler bu durumu açıkça belirtir. Bu site için yeni sunucu, ücretli plan veya özel alan adı satın alınmaz; mevcut şirket DNS'i ve uygulama deposu değiştirilmez.

Hazırlanma tarihi: 21 Ekim 2026.
