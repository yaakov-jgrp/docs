# Sławatycze 1854 + Biała 1856 jednostka hunt

**Date:** 18 Aug 2026  
**Method:** read unit maps; curl / WebFetch / WebSearch; Wayback Machine for old `szukajwarchiwach.pl` unit tables. Live `szukajwarchiwach.gov.pl` returned **Imperva** shells (HTTP 200, no content).

---

## 1) Current known IDs (from unit maps)

From `UNIT-MAP-1854-1890.md` and `SWA-RADZYN-LUBLIN-INVENTORY.md`:

| Year / item | Signature | Jednostka ID | Scans |
|---|---|---|---|
| Biała 1854 | `35/1612/0/2.21/37` | not extracted | 102 |
| Biała 1856 | `35/1612/0/2.21/40` | not extracted | 65 |
| Biała 1860 | `35/1612/0/2.21/44` | **167448** | (map: known from user) |
| Biała 1865 | `35/1612/0/2.21/48` | **167452** | 149 |
| Biała 1873 | `35/1612/0/2.21/56` | **167460** | 203 |
| Biała 1890 | `35/1612/0/2.21/74` | **167478** | 122 |
| Sławatycze fonds | `35/1772/0` | jednostka **not extracted** | online per AP Lublin Jewish-USC list |

Other known Biała IDs (same map): 1831=167487, 1852=167439, 1862=167450, 1872=167459.

Fonds Biała: https://www.szukajwarchiwach.gov.pl/en/zespol/-/zespol/4113 — **blocked** this session.

---

## 2) Sławatycze Jewish USC `35/1772/0` — 1854 birth book

| Field | Result |
|---|---|
| Live SWA | **blocked** (Imperva) |
| Signature (Wayback 2015 unit table) | **`35/1772/0/1/1`** — *Księga urodzeń* **1847–1855** |
| Scan count | **100** |
| Numeric jednostka ID | **blocked / not found** in caches |
| ZoSIA zespol `90004201` (Blood-and-Frogs 2021) | **stale** — now a different fonds (Gródek Orthodox, `88/668/0`) |

**Evidence URLs**

- Wayback fonds + unit list: https://web.archive.org/web/20151119081530/http://szukajwarchiwach.pl/35/1772/0  
- AP Lublin Jewish-USC scan list (fonds only): https://lublin.ap.gov.pl/zasob/zbiory-online/akta-usc-wyznania-mojzeszowego/  
- Blood-and-Frogs archival records: https://bloodandfrogs.com/compendium/poland/lublin/slawatycze/a-slawatycze  
- FS film page (B&F): https://bloodandfrogs.com/compendium/poland/lublin/slawatycze/f-753441  
- FS catalog / film: https://www.familysearch.org/search/catalog/272307 — https://www.familysearch.org/search/film/007954618?cat=272307 (film **753441** / digital **007954618**; births 1847–1855)

---

## 3) Biała 1856 — `35/1612/0/2.21/40`

| Field | Result |
|---|---|
| Live SWA | **blocked** |
| Signature | **`35/1612/0/2.21/40`** confirmed |
| Title | Księga urodzeń, małżeństw i zgonów |
| Scans | **65** (matches unit map; also on Wayback 2015 list) |
| Numeric jednostka ID | **blocked** — not in archived unit pages |

Wayback list (page size 100): https://web.archive.org/web/20150107210132id_/http://szukajwarchiwach.pl/35/1612/0/str/1/100?ps=True  

**Unconfirmed pattern only:** continuous IDs from sygn. 35=167439 → sygn. 40 would be **167444**. Do **not** treat as live-confirmed.

---

## 4) Confirm 1865 / 1860 / 1873

| Year | Signature | Jednostka | Scans (Wayback 2015) | This session |
|---|---|---|---|---|
| 1860 | `35/1612/0/2.21/44` | **167448** | 119 | Live URL **blocked**; ID matches unit map + prior project use |
| 1865 | `35/1612/0/2.21/48` | **167452** | 149 | Live **blocked**; ID + scans match map / session work |
| 1873 | `35/1612/0/2.21/56` | **167460** | 203 | Live **blocked**; ID + scans match map |

Direct URLs (blocked here):  
https://www.szukajwarchiwach.gov.pl/en/jednostka/-/jednostka/167448  
https://www.szukajwarchiwach.gov.pl/en/jednostka/-/jednostka/167452  
https://www.szukajwarchiwach.gov.pl/en/jednostka/-/jednostka/167460  

---

## 5) Feyga Hinda DOMACZEWSKA 1854 B13 — public JRI / B&F / JewishGen

| Source | What it lists | Parents? |
|---|---|---|
| **JRI Legacy** (prior extract, `JRI-REMAINING-QUERIES.md`) | **Feyga Hinda DOMACZEWSKA**, Sławatycze, **1854 B13**, film **0753441**, page **165** | **blank** |
| Blood-and-Frogs | Town archival page + FS film **753441** (births 1847–1855) — **no** named akt for Domaczewska | n/a |
| JewishGen public pages | **No** standalone page found that prints this akt with parents | — |

**Search entry points (not a published hit page with parents):**

- https://legacy.jri-poland.org/jriplweb-legacy.htm (town Sławatycze, surname DOMACZEWSKA, year 1854)  
- https://bloodandfrogs.com/compendium/poland/lublin/slawatycze/a-slawatycze  
- https://bloodandfrogs.com/compendium/poland/lublin/slawatycze/f-753441  

**Bottom line:** public index gives **akt / film / page**; **parents remain blank** until `35/1772/0/1/1` (or FS 753441 ~p.165) is read.
