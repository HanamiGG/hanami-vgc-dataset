# Hanami VGC — Reg M-A Dataset

A one-person archive of competitive Pokemon Reg M-A.
185,000+ Showdown replays, 307 tournaments, anonymized and packaged
under CC BY 4.0.

**→ [Download the latest release](../../releases/latest)**

## What's in the bundle

| Table | Description |
|-------|-------------|
| `replays_parsed` | Per-side parsed records: teams, leads, brought, win/loss, items, moves |
| `replays_meta` | Replay metadata: format, ELO, anonymized players |
| `tournaments` | 307 archived events from LimitlessVGC and play.limitlesstcg.com |
| `tournament_players` | Per-player standings with real W/L for online events |
| `tournament_usage` | Per-mon usage aggregates per event |
| `meta_summary.json` | Top mons, teams, items, moves at a glance |

Each table ships as both Parquet (recommended) and gzipped CSV.

Full schema, methodology notes, and quick-start examples are in the
bundle's `README.md`.

## License

CC BY 4.0 — use it for anything, credit me.

## About

Built by one person across April–June 2026 because the format was
interesting and the data didn't exist anywhere else.
