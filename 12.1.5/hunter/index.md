# Hunter Guides — Patch 12.1.5 (Midnight Season 2): Source Index

Compiled 2026-10-15 with the Scrapling MCP server (`ScraplingServer`, Scrapling 0.4.15).

- [Beast Mastery](beast-mastery.md)
- [Marksmanship](marksmanship.md)
- [Survival](survival.md)

## Patch coverage

- **12.1.5 is covered for all three specs** by Wowhead (updated 2026/10/13–14), Icy Veins (Oct 12–14, 2026) and Method.gg (13–14 Oct 2026). No fallback to an older patch was needed for any section.
- **Maxroll:**
  - BM (Oct 10) and SV (Oct 7) are labelled 12.1.5.
  - **MM is still 12.1 (Aug 6, 2026), so it is marked outdated.** It was used only for points that agree with newer sources.
  - The BM hero-talent paragraph on Maxroll still reads like 12.0 text.
- **murlok.io** labels its data "Patch 12.1 / Midnight Season 2." It is live ladder data refreshed every 8 hours (updated about 10 hours before fetch), so it reflects what top players run on 12.1.5 servers.
- **Partly stale text, despite current dates:**
  - Method's SV stats/consumables page mentions Butchery and Draught of Rampant Abandon, and its SV talents page discusses Flamefang Pitch.
  - Wowhead's SV Pack Leader priority still lists Flamefang Pitch, which its own overview says was removed.
  - Both are flagged in [survival.md](survival.md).

## Sources fetched

Fetch-method key:
- `make_request` / `bulk_get`: plain HTTP with a browser fingerprint.
- `fetch`: Playwright browser.
- `stealthy_fetch` / stealth session: Patchright stealth browser with Cloudflare solving.

### Wowhead
`make_request` returned HTTP 202 with an empty body, and `fetch` returned the same. `stealthy_fetch` with `solve_cloudflare` returned 200. All other pages went through one stealth session (`open_session` stealthy → `session_fetch`, then `close_session`).

| URL | Method | Status | Patch / updated |
| --- | --- | --- | --- |
| https://www.wowhead.com/guide/classes/hunter/beast-mastery/overview-pve-dps | make_request → fetch → stealthy_fetch, then session | ok | Patch 12.1.5, 2026/10/13 |
| https://www.wowhead.com/guide/classes/hunter/beast-mastery/talent-builds-pve-dps | stealth session | ok | 12.1.5 guide set (page date not captured) |
| https://www.wowhead.com/guide/classes/hunter/beast-mastery/rotation-cooldowns-pve-dps | stealth session | ok (AoE/opener tabs JS-only, missing) | 12.1.5 guide set (page date not captured) |
| https://www.wowhead.com/guide/classes/hunter/beast-mastery/bis-gear | stealth session | ok | 12.1.5 guide set (page date not captured) |
| https://www.wowhead.com/guide/classes/hunter/beast-mastery/enchants-gems-pve-dps | stealth session | ok | 12.1.5 guide set (page date not captured) |
| https://www.wowhead.com/guide/classes/hunter/marksmanship/overview-pve-dps | stealth session | ok | Patch 12.1.5, 2026/10/13 |
| https://www.wowhead.com/guide/classes/hunter/marksmanship/talent-builds-pve-dps | stealth session | ok | 2026/10/13 |
| https://www.wowhead.com/guide/classes/hunter/marksmanship/rotation-cooldowns-pve-dps | stealth session | ok (AoE/opener tabs JS-only, missing) | 2026/10/14 |
| https://www.wowhead.com/guide/classes/hunter/marksmanship/bis-gear | stealth session | ok | 2026/10/13 |
| https://www.wowhead.com/guide/classes/hunter/marksmanship/enchants-gems-pve-dps | stealth session | ok | 2026/10/13 |
| https://www.wowhead.com/guide/classes/hunter/survival/overview-pve-dps | stealth session | ok | 2026/10/13 |
| https://www.wowhead.com/guide/classes/hunter/survival/talent-builds-pve-dps | stealth session | ok | 2026/10/13 |
| https://www.wowhead.com/guide/classes/hunter/survival/rotation-cooldowns-pve-dps | stealth session | ok (AoE/opener tabs JS-only, missing) | 2026/10/13 |
| https://www.wowhead.com/guide/classes/hunter/survival/bis-gear | stealth session | ok | 2026/10/13 |
| https://www.wowhead.com/guide/classes/hunter/survival/enchants-gems-pve-dps | stealth session | ok | 2026/10/13 |

Wowhead's "talent-calc/blizzard/…" links carry the in-game import strings. Those were copied as the talent strings.

### Icy Veins
Plain HTTP worked for every page.

| URL | Method | Status | Patch / updated |
| --- | --- | --- | --- |
| https://www.icy-veins.com/wow/beast-mastery-hunter-pve-dps-rotation-cooldowns-abilities | make_request | ok | 12.1.5, Oct 12, 2026 |
| https://www.icy-veins.com/wow/beast-mastery-hunter-pve-dps-spec-builds-talents | bulk_get | ok (Dark Ranger strings collapsed, not captured) | 12.1.5, Oct 12, 2026 |
| https://www.icy-veins.com/wow/beast-mastery-hunter-pve-dps-stat-priority | bulk_get | ok | 12.1.5, Oct 12, 2026 |
| https://www.icy-veins.com/wow/beast-mastery-hunter-pve-dps-gear-best-in-slot | bulk_get | ok (slot table is a widget; notable items captured) | 12.1.5, Oct 12, 2026 |
| https://www.icy-veins.com/wow/beast-mastery-hunter-pve-dps-gems-enchants-consumables | bulk_get | ok | 12.1.5, Oct 12, 2026 |
| https://www.icy-veins.com/wow/marksmanship-hunter-pve-dps-spec-builds-talents | bulk_get | ok (Sentinel strings only) | 12.1.5, Oct 12, 2026 |
| https://www.icy-veins.com/wow/marksmanship-hunter-pve-dps-stat-priority | bulk_get | ok | 12.1.5, Oct 12, 2026 |
| https://www.icy-veins.com/wow/marksmanship-hunter-pve-dps-rotation-cooldowns-abilities | bulk_get | ok | 12.1.5, Oct 14, 2026 |
| https://www.icy-veins.com/wow/marksmanship-hunter-pve-dps-gear-best-in-slot | bulk_get | ok | 12.1.5, Oct 12, 2026 |
| https://www.icy-veins.com/wow/marksmanship-hunter-pve-dps-gems-enchants-consumables | bulk_get | ok | 12.1.5, Oct 12, 2026 |
| https://www.icy-veins.com/wow/survival-hunter-pve-dps-spec-builds-talents | bulk_get | ok (Sentinel strings only) | 12.1.5, Oct 12, 2026 |
| https://www.icy-veins.com/wow/survival-hunter-pve-dps-stat-priority | bulk_get | ok | 12.1.5, Oct 12, 2026 |
| https://www.icy-veins.com/wow/survival-hunter-pve-dps-rotation-cooldowns-abilities | bulk_get | ok | 12.1.5, Oct 12, 2026 |
| https://www.icy-veins.com/wow/survival-hunter-pve-dps-gear-best-in-slot | bulk_get | ok | 12.1.5, Oct 12, 2026 |
| https://www.icy-veins.com/wow/survival-hunter-pve-dps-gems-enchants-consumables | bulk_get | ok | 12.1.5, Oct 12, 2026 |

### Method.gg
| URL | Method | Status | Patch / updated |
| --- | --- | --- | --- |
| https://www.method.gg/guides/beast-mastery-hunter | bulk_get | ok (date check only) | 12.1.5, 13 Oct 2026 |
| https://www.method.gg/guides/beast-mastery-hunter/talents | bulk_get / make_request | ok | 12.1.5, 13 Oct 2026 |
| https://www.method.gg/guides/beast-mastery-hunter/stat-priority | bulk_get | **404**: wrong URL guess, replaced by the row below | — |
| https://www.method.gg/guides/beast-mastery-hunter/stats-races-and-consumables | bulk_get | ok | 12.1.5, 13 Oct 2026 |
| https://www.method.gg/guides/marksmanship-hunter/talents | bulk_get | ok | 12.1.5, 13 Oct 2026 |
| https://www.method.gg/guides/marksmanship-hunter/stats-races-and-consumables | bulk_get | ok | 12.1.5, 13 Oct 2026 |
| https://www.method.gg/guides/survival-hunter/talents | bulk_get | ok (some stale text) | 12.1.5, 14 Oct 2026 |
| https://www.method.gg/guides/survival-hunter/stats-races-and-consumables | bulk_get | ok (some stale text) | 12.1.5, 14 Oct 2026 |

### Maxroll
The 3-page `bulk_get` result was too large to return inline, so the MCP host saved it to disk. It was then split and searched locally.

| URL | Method | Status | Patch / updated |
| --- | --- | --- | --- |
| https://maxroll.gg/wow/class-guides/beast-mastery-hunter-raid-guide | bulk_get | ok (stat/trinket widgets not in static text) | 12.1.5, October 10, 2026 |
| https://maxroll.gg/wow/class-guides/marksmanship-hunter-raid-guide | bulk_get | **outdated** (12.1) | patch 12.1, August 6, 2026 |
| https://maxroll.gg/wow/class-guides/survival-hunter-raid-guide | bulk_get | ok | 12.1.5, October 7, 2026 |

### murlok.io and Archon
| URL | Method | Status | Patch / updated |
| --- | --- | --- | --- |
| https://murlok.io/hunter/beast-mastery/m+ | bulk_get / make_request | ok (no import string; talent heatmap only) | "Patch 12.1", live, updated ~10 h before fetch |
| https://murlok.io/hunter/marksmanship/m+ | bulk_get | ok | same |
| https://murlok.io/hunter/survival/m+ | bulk_get | ok | same |
| https://www.archon.gg/wow/builds/beast-mastery/hunter/mythic-plus/overview/10/all-dungeons/this-week | bulk_get, then stealthy_fetch (solve_cloudflare, network_idle) | **blocked** | n/a: both returned only a "One Quick Check" bot-check page |

## Failures and gaps

- **Archon:** blocked by its "One Quick Check" bot wall, both over plain HTTP and with the stealth browser plus Cloudflare solving. I made no further attempts to get past it, so the Archon MM and SV pages were not fetched.
- **Wowhead first attempts:** `make_request` and `fetch` both got HTTP 202 with an empty body (anti-bot). The stealth fetcher worked.
- **Wowhead rotation pages:** the AoE and opener tabs are built client-side and were not in the fetched DOM. Icy Veins covers AoE and openers for all specs.
- **Method `/stat-priority`:** 404, because I guessed the URL. The correct page is `/stats-races-and-consumables`.
- **Maxroll MM:** still on 12.1, so it is marked outdated.
- **Dark Ranger / Pack Leader strings on Icy Veins:** the off-meta hero builds sit in collapsed sections and were not captured. Wowhead and Method strings cover those builds instead.
- **Wowhead BM sub-page dates:** not captured, because the date selector was added after those pages were fetched. The guide set shows Patch 12.1.5 and the overview is dated 2026/10/13.
- **murlok.io:** its "Patch 12.1" label is a generic Season 2 label on live data. It was used only for usage statistics.
- Every required section is filled for every spec. No section had to be marked "not found."
