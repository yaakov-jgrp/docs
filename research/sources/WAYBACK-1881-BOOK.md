# 1881 Biała Jewish USC book — Wayback hash recovery (19 Aug 2026)

**Question:** Can the 1881 original of **M2 Matla GERSZBERG × Chaim Dawid Zonszajn** be read without the live Szukaj viewer?

**Answer this run:** **No.** The unit page and the **first 15 scans** are recoverable from the 2015 Wayback crawl. Those scans are the **birth** section (May 1881). The marriage section hashes were **not archived**. Live Szukaj remains Incapsula-blocked from curl.

---

## Unit (confirmed from archived HTML)

| Field | Value |
|---|---|
| Signature | `35/1612/0/2.21/64` |
| Title | Księga urodzeń, małżeństw i zgonów, **1881** |
| Snapshot | https://web.archive.org/web/20150416140255id_/http://szukajwarchiwach.pl/35/1612/0/2.21/64 |
| Pages | **151** |
| Scans (live map) | **87** (6 thumbnail pages of 15) |
| Microfilm | **brak mikrofilmu** — no FamilySearch duplicate |
| Notes on the unit | damaged birth index; torn leaves; digitized |
| Numeric jednostka | still unconfirmed live; sequential guess **167468** |

Numeric ID was **not** printed on the 2015 page (reference code shown as **64** only).

---

## Scan 1–15 hashes (2015 thumbnail strip)

Do **not** treat scan number as akt number.

| Scan | Hash |
|---|---|
| 1 | `4tU7herNt3Ia-i1Xoweoug` |
| 2 | `d_QCv5_PCmv8U-leCfppQw` |
| 3 | `5uswryJu0ApzYVcOF6zUbw` |
| 4 | `7s85QBJf_PlVRoC0YyPhSQ` |
| 5 | `hSeZeC8-TYbTYBA3GioEiA` |
| 6 | `BmI6c_3tRbCt4vKfa38kYw` |
| 7 | `Pbz5-cHU5JC5H0rQrJHRig` |
| 8 | `yD_N2CH4hl_7FF3PNvsoAg` |
| 9 | `qXhROK2lSnsXNqQlYqjaFQ` |
| 10 | `qM7eXetx3fCZ0hnAzNodVw` |
| 11 | `b3gEScGGb_KFG1a7oXA2SQ` |
| 12 | `fP1MCdwILeZhBKTtX1xMkA` |
| 13 | `Cc-9TDVroQ4M9I5ziBet-g` |
| 14 | `HGTD47bj7Bm4Y-O9V3Gxig` |
| 15 | `9-yA-Q5H5oP0bHTCAUWx9A` |
| 16 (next_page only) | `SX3RytQUOfAT-acZcKUaNQ` — **not in Wayback** |

Wayback archived **medium** JPEGs for hashes **8** and **10** only; thumbs for 1–15.

---

## What the two medium leaves actually are

| File | Hash | What is on the paper | M2? |
|---|---|---|---|
| `research/scans/wayback-1881/medium_yD_N2CH4hl_7FF3PNvsoAg.jpg` | scan **8** | Births **№ 15–18**, April–May **1881**, Biała. Diblewicz / Skeidljarukh-class. **No Herszberg/Gerszberg.** | **No** |
| `research/scans/wayback-1881/medium_qM7eXetx3fCZ0hnAzNodVw.jpg` | scan **10** | Births **№ 23–26**, 18/30 May **1881**. Goldsztejn / Herszman / Degensztejn. Witnesses Szulim Piwo, Moszko Meterbaum. **No Matla, no Zonszajn.** | **No** |

Calibration: ~4 birth akts per scan in this stretch. Marriages follow the birth section (and damaged birth index). **M2 is not in scans 1–15.**

---

## What was tried and failed this run

| Method | Result |
|---|---|
| curl live `jednostka/167468` and `/56` | Incapsula 212-byte shell |
| GET `/skan/-/skan/{old-hash}` | Incapsula iframe (~850 B) |
| photos.szukajwarchiwach.gov.pl/{hash} | 403 |
| Wayback `str/1/2/15` … `str/1/6/15` at the 20150416 timestamp | 404 (only page 1 of thumbs crawled) |
| Wayback medium of scan 16 hash | 404 |
| CDX `2.21/56` (1873) and `1772/0/1/1` | no 2015 unit-page snapshot at the 1881 timestamp |
| FamilySearch catalog **272307** | Incapsula 403 (Sławatycze film, not 1881) |

---

## Next derivative

Open the **marriage** section of `35/1612/0/2.21/64` in a real browser (left-margin **№ 2**, couple Matla Гершбергъ × Зоншайн). Do not reuse scans 8 or 10. Do not use scan 2 as akt 2.
