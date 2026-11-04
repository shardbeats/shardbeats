# 💢 ShardBeats — TRAKK SUITE

Simple, lightweight, offline-first tools that solve real beatmaker problems.
No accounts, no mandatory cloud. Everything portable as `.exe`.

### Pipeline

`Idea → Production → Artwork → Video → Promo`

| Tool | What it does | Stack |
|------|--------------|-------|
| [TRAKKNAME](https://github.com/shardbeats/TRAKKNAME) | Offline type-beat title generator (EN/ES, moods, weighted artists). Curation. | Python + PySide6 + SQLite |
| [TRAKKNAME-IONIC](https://github.com/shardbeats/TRAKKNAME-IONIC) | Same engine on Android, 100% offline. | Ionic React + Capacitor |
| [TRAKKCONVERTER](https://github.com/shardbeats/TRAKKCONVERTER) | Converts drumkits / sample packs to Roland SP-404MK2-compatible WAV. Batch + drag&drop. | Python + PySide6 + FFmpeg |
| [TRAKKNORMALIZER](https://github.com/shardbeats/TRAKKNORMALIZER) | Per-clip peak normalization to its own peak, linear gain. | Python + PySide6 + FFmpeg |
| [TRAKKOUT](https://github.com/shardbeats/TRAKKOUT) | Beat + cover → 1080p MP4 + YouTube upload (API v3, templates, queue, scheduling). | Python + PySide6 + FFmpeg + YT API |
| [TRAKKSTUDIO](https://github.com/shardbeats/TRAKKSTUDIO) | Multitool for beatmakers · ShardBeats TRAKK SUITE Organize · Convert to SP-404MK2 WAV · Peak-normalize. 3 independent tools, one window.. | Python + PySide6 + FFmpeg |
| [TRAKKLICENSE](https://github.com/shardbeats/TRAKKLICENSE) | Offline beat-license contracts for beatmakers (EN/ES PDF + evidence, no cloud) | Python + PySide6 |

### Principles

- Simple > complete. One tool = one problem.
- Lightweight: PySide6, SQLite stdlib, portable FFmpeg.
- Offline-first, portable `.exe`, one-click `start.bat`.
- `pytest -q` green before every release.

> Ex `SP-404MK2SimpleConverter` → now `TRAKKCONVERTER`.
> Ex `simple-peak-normalizer` → now `TRAKKNORMALIZER`.
