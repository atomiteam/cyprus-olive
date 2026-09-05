# Yapısal Veri

Bu klasör ileride web sayfası, karşılaştırma araçları ve analiz scriptleri tarafından okunabilecek makine-okur veriyi barındıracaktır.

Planlanan yapı:

```text
data/
├── varieties/
│   └── <cesit-kodu>.json
└── observations/
    └── <gozlem-kodu>.json
```

## Önerilen çeşit alanları

- `id`
- `canonicalName`
- `localNames`
- `origin`
- `status`
- `leaf`
- `fruit`
- `endocarp`
- `phenology`
- `sources`
- `notes`

## Önerilen gözlem alanları

- `id`
- `date`
- `location`
- `treeDescription`
- `leafMeasurements`
- `fruitMeasurements`
- `endocarpMeasurements`
- `photos`
- `candidateVarieties`
- `confidence`
- `notes`

Ham saha verisi ile yorumlanmış çeşit profilleri ayrı tutulmalıdır.
