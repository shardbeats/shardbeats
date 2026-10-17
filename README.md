# 💢 ShardBeats — TRAKK Family

Herramientas simples, ligeras y offline-first que resuelven problemas reales de beatmakers.
Sin cuentas, sin cloud obligatoria. Todo portable con `.exe`.

### Pipeline

`Idea → Producción → Portada → Video → Promo`

| Tool | Qué hace | Stack |
|------|----------|-------|
| [TRAKKNAME](https://github.com/shardbeats/TRAKKNAME) | Generador offline de títulos type-beat (EN/ES, moods, artists ponderados). Curación. | Python + PySide6 + SQLite |
| [TRAKKNAME-IONIC](https://github.com/shardbeats/TRAKKNAME-IONIC) | Mismo motor en Android, 100% offline. | Ionic React + Capacitor |
| [TRAKKCONVERTER](https://github.com/shardbeats/TRAKKCONVERTER) | Convierte drumkits/sample packs a WAV compatible Roland SP-404MK2. Batch + drag&drop. | Python + PySide6 + FFmpeg |
| [TRAKKNORMALIZER](https://github.com/shardbeats/TRAKKNORMALIZER) | Normalización peak por clip a su propio pico, ganancia lineal. | Python + PySide6 + FFmpeg |
| [TRAKKOUT](https://github.com/shardbeats/TRAKKOUT) | Beat + cover → MP4 1080p + subida a YouTube (API v3, templates, queue, scheduling). | Python + PySide6 + FFmpeg + YT API |
| [TRAKKMEMES](https://github.com/shardbeats/TRAKKMEMES) | Fábrica local de compilaciones verticales 9:16 para promocionar tus beats con clips. | Python + FastAPI + FFmpeg |

### Principios

- Simple > completo. Una tool = un problema.
- Ligera: PySide6, SQLite stdlib, FFmpeg portable.
- Offline-first, `.exe` portable, `start.bat` one-click.
- `pytest -q` verde antes de cada release.

> Ex `SP-404MK2SimpleConverter` → ahora `TRAKKCONVERTER`.
> Ex `simple-peak-normalizer` → ahora `TRAKKNORMALIZER`.
