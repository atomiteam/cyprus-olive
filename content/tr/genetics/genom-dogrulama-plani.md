# Genom / genetik doğrulama planı

Bu projenin uzun vadeli hedefi, saha fotoğraflarıyla oluşturulan morfolojik kümeleri genetik verilerle doğrulamak ve Kıbrıs'taki yerel zeytin materyalinin alt tiplerini mümkün olduğunca doğru biçimde ayırmaktır.

## Temel yaklaşım

1. Her saha ağacına kalıcı bir örnek kodu verilir (`MAG-ONDER-001` gibi).
2. Aynı ağaç için yaprak, meyve, çekirdek, ağaç formu ve fenoloji kaydı tutulur.
3. Genetik örnek alındığında örnek tüpü aynı kodla etiketlenir.
4. İlk aşamada literatürdeki Kıbrıs yerel çeşitleri ve doğrulanmış referans materyalle karşılaştırma yapılır.
5. Morfolojik eşleşme hiçbir zaman tek başına kesin çeşit teşhisi sayılmaz.

## Genetik test katmanları

### Aşama 1 — SSR / mikrosatellit profili

Daha düşük maliyetli ilk doğrulama katmanı olarak kullanılabilir. Literatürdeki Kıbrıs genotipleriyle karşılaştırmaya uygunsa hızlı eleme sağlar.

### Aşama 2 — SNP paneli

Yakın klonları ve alt grupları ayırmak için daha yüksek çözünürlük sağlar. Aynı adla bilinen fakat genetik olarak farklı materyali ortaya çıkarmak için değerlidir.

### Aşama 3 — Geniş genom dizileme

Özellikle aday yerel genotiplerin korunması ve bilimsel olarak güçlü bir referans veri seti oluşturulması hedeflenirse seçilmiş örneklerde tüm genom / yüksek yoğunluklu dizileme düşünülebilir.

## Hedeflenen sonuç

Her saha ağacı için zamanla aşağıdaki yapı elde edilmelidir:

```text
Saha kodu
  ├─ Lokasyon
  ├─ Fotoğraflar
  ├─ Yaprak morfolojisi
  ├─ Meyve morfolojisi
  ├─ Çekirdek morfolojisi
  ├─ Fenoloji / olgunlaşma
  ├─ Verim ve çevre gözlemi
  ├─ Aday çeşit / genotip
  └─ Genetik doğrulama
       ├─ SSR
       ├─ SNP
       └─ Genom referansı
```

Amaç sadece bilinen çeşit isimlerinden birini atamak değil; Kıbrıs'a özgü, bugün tek bir “yerli” adı altında karışmış olabilecek genetik alt tipleri de ortaya çıkarabilmektir.
