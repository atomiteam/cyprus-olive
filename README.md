# Cyprus Olive — Kıbrıs Zeytin Genetikleri ve Saha Kataloğu

Bu depo, Kıbrıs'ta bulunan yerli zeytin genotiplerini, eski/yerel varyantları ve **yerli olmasa bile ada koşullarında verimli ve dayanıklı olduğu görülen diğer zeytin tiplerini** bölge bölge belgelemek için oluşturulmuştur.

## Çalışmanın amacı

Kıbrıs'ın yerel zeytin genetikleri hakkında erişilebilir ve doğrulanabilir bilgi sınırlıdır. Ayrıca sahada ve fidanlıklarda kullanılan “yerli” gibi isimlerin her zaman tek ve genetik olarak doğrulanmış bir çeşidi temsil ettiği varsayılamaz.

Bu proje dört katmanlı bir referans arşivi oluşturmayı hedefler:

1. **Saha kataloğu** — farklı bölgelerdeki ağaçların fotoğraf, konum ve gözlemlerini kaydetmek.
2. **Morfolojik karşılaştırma** — yaprak, meyve, çekirdek, ağaç formu ve olgunlaşma özelliklerini standart biçimde karşılaştırmak.
3. **Performans gözlemi** — yerli olsun veya olmasın Kıbrıs koşullarında verimli, dayanıklı ve ilginç ağaçları belirlemek.
4. **Genetik doğrulama** — morfolojik olarak ayrılan grupları SSR/SNP ve gerektiğinde daha geniş genom analiziyle test ederek yerli çeşitleri ve alt tipleri mümkün olduğunca kesin belirlemek.

Fotoğrafa dayalı teşhisler hiçbir zaman kesin çeşit adı olarak tutulmaz; genom/genotip doğrulaması yapılana kadar **aday çeşit / aday genotip** statüsündedir.

## Web giriş sayfası

İlk web prototipi:

- [`web/index.html`](web/index.html) — çalışmanın amacı, karşılaştırma kataloğu ve lokasyon bağlantıları
- [`web/locations/magusa-onder-avm.html`](web/locations/magusa-onder-avm.html) — ilk lokasyon kataloğu

## Lokasyon katalogları

Her farklı saha ağacı kalıcı bir kod alır. Örnek:

- **MAG-ONDER-001** — Gazimağusa, Önder AVM yanı otopark

Lokasyon listesi: [`content/tr/locations/README.md`](content/tr/locations/README.md)

Yapısal kayıt: [`data/locations.json`](data/locations.json)

## Klasör yapısı

```text
cyprus-olive/
├── README.md
├── analysis/                         # Devam eden analiz, hipotez ve literatür notları
├── assets/
│   ├── catalog/                      # Karşılaştırma katalogları / infografikler
│   └── locations/
│       └── magusa-onder-avm/         # MAG-ONDER-001 saha görselleri ve manifest
├── content/
│   ├── tr/                           # Ana kaynak dil
│   │   ├── genetics/                 # Genetik doğrulama yaklaşımı
│   │   ├── locations/                # Lokasyon katalog indeksi
│   │   ├── methodology/              # Saha tanımlama ve örnekleme yöntemi
│   │   ├── observations/             # Ayrıntılı saha gözlemleri
│   │   └── varieties/                # Çeşit / genotip profilleri
│   ├── el/                           # Gelecekte Yunanca
│   └── en/                           # Gelecekte İngilizce
├── data/
│   └── locations.json                # Web ve analiz için yapısal lokasyon verisi
└── web/
    ├── index.html
    ├── styles.css
    └── locations/
```

## İlk saha kaydı — MAG-ONDER-001

İlk katalog, Gazimağusa'da Önder AVM yanındaki otoparkta gözlenen bir zeytin ağacıyla başlatılmıştır. Aynı ağaçtan ağaç genel görünümü, yaprak, farklı meyve kümeleri, meyve eti, çekirdek, cetvelle çekirdek ölçümü ve meyve–çekirdek karşılaştırma fotoğrafları alınmıştır.

İlk gözlemde meyveler açık yeşil, dolgun ve sulu; yapraklar dar-uzun ve gümüşi; çekirdek orta boy, dolgun-oval ve oluklu görünmektedir. Ladoelia, Kato Drys ve Korakou dahil Kıbrıs yerel materyaliyle karşılaştırma sürmektedir; **kesin teşhis yapılmamıştır**.

Fotoğraf manifesti: [`assets/locations/magusa-onder-avm/README.md`](assets/locations/magusa-onder-avm/README.md)

## Genetik doğrulama

Uzun vadede aynı saha kodunun fotoğraf, morfometri ve laboratuvar örneğini birbirine bağlaması amaçlanıyor. Önerilen aşamalar:

- SSR / mikrosatellit profili
- SNP tabanlı ayrım
- seçilmiş örneklerde daha geniş genom dizileme

Ayrıntı: [`content/tr/genetics/genom-dogrulama-plani.md`](content/tr/genetics/genom-dogrulama-plani.md)

## Çalışma ilkeleri

- Gözlem, hipotez ve doğrulanmış bilgiyi ayrı tutmak.
- Her iddiaya mümkün olduğunca güvenilir kaynak eklemek.
- Fotoğrafları lokasyon ve kalıcı örnek koduyla ilişkilendirmek.
- Aynı ağaçtan birden fazla meyve, yaprak ve çekirdek örneği toplamak.
- Belirsiz örnekleri `aday` veya `bilinmeyen genotip` olarak işaretlemek.
- Fidanlık veya yerel isimlendirmeyi doğrudan genetik çeşit adı kabul etmemek.
- Yerli olmayan fakat yüksek performans gösteren ağaçları da koruma/üretim açısından kataloglamak.

## Dil

Şimdilik ana içerik **Türkçe** tutulmaktadır. Yapı ileride **Yunanca (`el`)** ve **İngilizce (`en`)** içerik eklenebilecek şekilde hazırlanmıştır.
