# Baha Manila — public docs

Public documentation for **Baha Manila** (Manilia Flood Monitor), a free,
experimental flood early-warning app for the Marikina river corridor
(Upper Wawa → Rodriguez → San Mateo → Marikina → Pasig).

The source code lives in the **private** repository
[`thejustinjames/baha-alert`](https://github.com/thejustinjames/baha-alert)
(that link is visible to collaborators only). This repo exists so a few
documents from it can be shared publicly.

> ⚠️ **This is an experimental project, not an official warning service.**
> During a flood, follow [PAGASA](https://www.pagasa.dost.gov.ph/),
> [NDRRMC](https://ndrrmc.gov.ph/), [MMDA](https://mmda.gov.ph/) and your LGU.

## What's here

- **[Architecture](https://thejustinjames.github.io/baha-alert-docs/)** —
  what is actually deployed, read back from the live AWS account
  (`index.html`, served via GitHub Pages).
- **[`data-access/`](data-access/)** — status of formal data-access requests to
  Philippine government agencies, and the draft request letters:
  - [Marikina catchment boundary](data-access/01-georisk-catchment.md) — UP Project NOAH / GeoRiskPH (DOST-PHIVOLCS)
  - [Upper Wawa Dam telemetry](data-access/02-ocd-wawa.md) — OCD CALABARZON / Manila Water
  - [Formal PMT feed access](data-access/03-pagasa-feed.md) — PAGASA (DOST)

## Project links

- Public landing page: https://www.agrisphere.asia
