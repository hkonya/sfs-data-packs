# Super Football Star — Veri Paketleri

[Super Football Star](https://github.com/hkonya) (SFS) için topluluk tarafından hazırlanan
futbol veri paketleri. Oyun bu depodan paketleri indirip yeni kariyer kurulumunda kullanır.
Bu depo SFC paketlerinden **bağımsız** sürümlenir; şema ve içerik SFS motorunun ihtiyaçlarına göre gelişir.

## İçerik (2026-27)

- 20 ülke · 100 lig kaydı · 3.619 kulüp · 62.147 oyuncu · 20 ulusal kupa
- 70 lig + 20 kupa amblemi, 3.366 kulüp logosu, 24.556 portre (görsel katmanı opsiyonel)

| Dosya | Açıklama |
|---|---|
| `index.json` | Katalog: paketler, sürümler, boyutlar, görsel varlık adresleri |
| `world-2026-27-core.json.gz` | 20 ülkenin tamamı tek pakette (oyunun indirdiği) |
| `<ülke>-2026-27-core.json.gz` | Ülke başına çekirdek |
| Releases → `<ülke>-2026-27-images.tar` | Kulüp logoları, portreler, lig/kupa amblemleri (ülke başına, opsiyonel) |

## Yol haritası

Paket, SFS'in ortak dünya / organizasyon motoru için genişletiliyor: gerçek lig grupları,
sezon sürümlü statüler, önceki sezon tabloları, Avrupa katsayıları, takvimler, alt lig havuzu,
milli takım kapsamı ve arka plan federasyonları. Ayrıntı: SFS deposunda `docs/`.

## Telif ve kullanım

Paket ücretsiz topluluk içeriğidir, oyunla dağıtılmaz ve isteğe bağlı indirilir.
Görseller ayrı Release varlıklarıdır; hak sahibinin talebiyle kaldırılır (takedown).
