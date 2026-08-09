# Data access — status and correspondence

Two blockers need something we cannot obtain by writing code, and both go
through the same channel: asking the agencies directly.

| # | Need | From | Status |
|---|---|---|---|
| 1 | **Marikina catchment boundary** (GeoJSON/shapefile) | UP Project NOAH / GeoRiskPH (DOST-PHIVOLCS) | Not yet sent |
| 2 | **Upper Wawa telemetry** (level, spill status, spill rate) | OCD CALABARZON / Manila Water | Not yet sent |
| 3 | Formal PMT feed access (currently undocumented `.do` endpoints) | PAGASA (DOST) | Not yet sent |

Record every reply in this folder, dated. This is the path off scraping and off
provisional geometry.

## Why these two block everything

**Without the catchment**, the impact resolver refuses to deliver to anyone —
by design. It will not tell a resident they are affected on the strength of a
hand-drawn boundary, because getting that wrong means telling somebody
downstream they are safe. Everything else works; nobody gets notified.

**Without Upper Wawa**, we are blind to the top of the watershed. It is the
earliest warning the whole Marikina chain gets, and the only public channel is a
Facebook page.

## Drafts

- [`01-georisk-catchment.md`](01-georisk-catchment.md) — catchment boundary
- [`02-ocd-wawa.md`](02-ocd-wawa.md) — Upper Wawa telemetry
- [`03-pagasa-feed.md`](03-pagasa-feed.md) — formal PMT feed access

Each is written to be short, specific about exactly what is wanted, honest about
what we are building, and easy to say yes to. Fill in the sender details and
send — they are drafts for a human to review and put their name to, not letters
to be sent automatically.
