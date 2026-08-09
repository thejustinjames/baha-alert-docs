# Request: formal access to PMT flood forecasting data

**To:** PAGASA (DOST) — Hydrometeorology Division
**Subject:** Request for formal access to Pasig–Marikina–Tullahan FFWS data

---

Good day,

I am building a free, non-commercial flood information app for residents of the
Marikina river corridor, using data your Pasig–Marikina–Tullahan Flood
Forecasting and Warning System publishes.

I am currently reading the endpoints your own web interface uses
(`/water/table_list.do` and `/rainfall/table_list.do`). They work well and I
poll them at the same rate the data updates — every five minutes for water
levels, ten for rainfall — with an identifying user agent.

I would rather not depend on an undocumented interface for something people may
rely on during a typhoon. **Is there a supported or formal way to access this
data?** If those endpoints are considered stable and I may continue using them,
knowing that would also be genuinely useful.

I would also appreciate guidance on:

- Whether my polling rate is acceptable, or whether you would prefer slower
- Whether you would be notified in advance of changes to the response format
- The attribution wording you would like used in-app
- Station coordinates and codes, if a canonical list exists beyond
  `/water/map_list.do`

**How the data is used:** the app shows current river levels against your
published Alert/Alarm/Critical levels and notifies residents when a level is
crossed near them. It shows **your** declared warning status in preference to
its own calculation, never displays a lower level than you do, states clearly
that it is not an official warning service, and tells users to follow PAGASA,
OCD and their LGU regardless of what it shows. Every reading is attributed to
PAGASA with a direct link to your page.

Thank you for publishing this data — it is the backbone of what I am building.

Sincerely,

**[Name]**
[Email] · [Phone]
[Organisation, if any]
