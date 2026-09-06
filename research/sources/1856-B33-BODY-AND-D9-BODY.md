# 1856 Biała — BODY JPEGs claimed as B33 and D9 (palaeographic reading)

**Claimed unit:** jedn. **167444**, signature `35/1612/0/2.21/40`.  
**Working files:** `research/scans/1856-b33-BODY-full.jpg` (claimed scan **20**) and `research/scans/1856-d9-BODY-full.jpg` (claimed scan **45**), plus the supplied `-margin.jpg` / `-parents.jpg` crops. Archive full leaves also present as `scan20-1856.jpg` and `scan45-1856.jpg` (= `scan47-1856.jpg`).

This note does **not** name Khuna Herszberg’s parents. Tesseract was **not** used and is **not** evidence. Isolated tiles that produced query-list names (`Khuna`, `Dan`, `Dawid Leyzor`, `Ita`, `Beniamin Wulf`) on a zone that larger complete crops of the **same** band do not keep were treated as **contaminated**.

Method: ImageMagick `identify` / `convert` (contrast-stretch, invert, sharpen) under `/tmp/b33b/`, `/tmp/b33w/`, `/tmp/d9b/`, `/tmp/d9w/`, `/tmp/d9a/`, `/tmp/d9c/` (not git). Dual-offset complete crops of one zone. Only letter sequences that recur on **more than one complete crop** of that zone are STABLE.

Prior leaves (already read; do not reuse as these bodies):

| Prior JPEG | What it is | What should come next |
|---|---|---|
| `1856-b33-TRUE-full.jpg` | Births **№ 31–32** (Chawa Gitla / Rejza Gampel). Right gutter: **№ 33 Aktu Josela Hirszberg z Biały** | Next birth scan, left-margin **№ 33**, body of Josel |
| `1856-d9-TRUE-full.jpg` | Death of **Szmul Wolecki**, then opening of **Freydla akt 8** | After akt **8**: death narrative of akt **9** |

---

## Verdict

| Claimed | What the JPEG actually is | Target akt? | Names Khuna? |
|---|---|---|---|
| **1856 B33** Josel Hirszberg (`1856-b33-BODY-*`) | **Yes — birth akt № 33**, male child **Josel**, surname **Hirszberg**, Biała, September **1856**. Top of scan **20** (NCC 1.0 @ 0,0 vs `scan20-1856.jpg`). | **Yes** | **No** |
| **1856 D9** Jankiel WAJNTAL (`1856-d9-BODY-*`) | **Wrong akt on the BODY JPEG.** Top of scan **45** is the **close of Freydla / Freidla Zeygman** (continuation of akt **8**). Page **42**. Right gutter **№ 10** is the **facing** leaf, not this body. | **No** (not on this crop) | **No** |

**Where akt 9 actually is (same download, not the BODY crop):** on `scan45-1856.jpg` **below** y≈1750, left-margin **№ 9 aktu Jankiel Wajntal**, opening a death narrative that **continues** on `scan46-1856.jpg`. That continuation is palaeographed below as a layout hunt, because the supplied BODY file stops at Freydla.

---

## Geometry (not palaeography)

| File | Size | Match |
|---|---|---|
| `1856-b33-BODY-full.jpg` | 2110×1700 | **Top** of `scan20-1856.jpg` (NCC ≈ 0.99999 @ 0,0). Different paper from TRUE 31–32 (NCC ≈ 0.71) and from the false-positive page-11 leaf (NCC ≈ 0.76). |
| `1856-b33-BODY-margin.jpg` | 400×1700 | Left strip of BODY (NCC 1.0 @ 0,0). |
| `1856-b33-BODY-parents.jpg` | 2110×850 | **Top 850 px of BODY** (NCC 1.0 @ 0,0) — opening / father band, **not** a separate parents plate. |
| `1856-d9-BODY-full.jpg` | 2110×1750 | **Top** of `scan45-1856.jpg` (NCC ≈ 0.99999 @ 0,0). `scan47-1856.jpg` is **identical** to scan 45. Different paper from TRUE Szmul leaf (NCC ≈ 0.76). |
| `1856-d9-BODY-margin.jpg` | 400×1750 | Left strip of BODY (NCC 1.0 @ 0,0). Shows folio **42**, **not** left-margin **№ 9**. |
| `1856-d9-BODY-parents.jpg` | 2110×850 | **Top 850 px of BODY** (NCC 1.0 @ 0,0) — Freydla opening, not a Wajntal parents plate. |

Paper on both BODY files starts near **y=345–354** (rows above that are the black scanner bar). Crops that started at y=0–100 are binding, not text.

Scan numbers **20** and **45** are downloader metadata; they are **not** printed as the clerk’s folio.

---

## 1) B33 BODY — `1856-b33-BODY-*`

**Is this Josel Hirszberg, akt 33? Yes.**

### STABLE (recurs on ≥2 complete crops of the same zone)

| Field | STABLE | Crops |
|---|---|---|
| This leaf’s akt | Left-margin **№ 33 Aktu Josel(a) Hirsz- / Hirszberga z Białej** | `lmargin-top` / `lmargin-top-off`; opening bands `openA`/`openB`/`fatA` |
| Act type | Polish **birth**. *Stawił się Starozakonny* + *okazał Nam dziecię płci Męskiej* + *przy obrzezaniu nadane zostało Imię* | `fat*`/`wit*`/`age*`; `momA`/`momB`; `cloA`/`cloB`/`sigband*` |
| Year / town | **1856** (*Pięćdziesiątego Szóstego*); **Biała** (*Mieście … Białey / Biały*) | `openA`/`openB`; `fatA`/`staw1`/`staw2`; `mom*` |
| Child | Male; given name **Josel** | Margin label; naming/close `cloA`/`cloB`/`sigbandA`/`sigbandB` (*Imię Josel*) |
| Birth | **tu w Białej**; dual calendar **1/13 September** (*Pierwszym / Trzynastym Września roku bieżącego*); **4 a.m.** (*Czwarta z rana*) | `momA`/`momB`; `im1`/`im2` |
| Father | Surname **Hirszberg**. Age **22** (*lat Dwadzieścia Dwa liczący*). Of Biała (*z Białej* / *w Mieście Białej zamieszkały*). Signs **Hirszberg** in Polish and Hebrew **הירשבערג** | `witA`/`witB`/`age1`/`age2`; `sigbandA`/`sigbandB` |
| Mother | Wife of the declarant (*z małżonki Jego*). Given-name core **Chan-** (Chana / Chanka / Chaia). Maiden **Jakubowiczów / Jakimowiczów**. Age **22** (*dwadzieścia dwa liczącej*) | `namA`/`namB`; `momB` (starts the wife clause) |
| Witnesses | Two **szkolnicy** of Biała. **Chemia / Chaim Wachterman**-class + **Szulim Piwo**-class | `witA`/`witB`; `birA`/`birB` |
| Khuna | **Not named** | — |

### UNSTABLE / unpublished

| Topic | Conflict | This pass |
|---|---|---|
| Father’s **given** name | Opening *Itko / Icko* vs signature *Litko / Lewko / Letko / Leib* vs one full-leaf pass *Zelko* | **Do not lock.** Surname + age **22** are locked. Do **not** force Zelko of Dan × Ester |
| Father’s occupation | *Szynkarz* vs *Spekulant* vs blank | Unpublished |
| Drawing-up day / hour | 4/16 vs 12/24 vs 14/26 vs 18/30 September; 9 vs 10 a.m. | Month **September 1856** locked; exact dual-calendar drawing-up day unpublished |
| Top-right corner | *17* as folio vs *17 lipca / Lutego* | Previous TRUE leaf is page **16** (akts 31–32) ⇒ this page is **geometrically** page **17**. Not used as a palaeographic lock |
| Witness ages | First **34**, second **40** on `birA`/`birB`. Chemia is **64** on the 1856 death szkolnik pair | Pair identity locked; exact ages unpublished if they fight the known Chemia ~64 |
| Isolated *Khuna* on a signature invert / tight tile | Contradicts *Chaim* + Wachterman on the same close band | **Contaminated; unpublished** |

**Is this Dan × Ester or Dawid Leyzor × Ita as Josel’s parents?** **No.** The locked household is a **22-year-old Hirszberg** and a **22-year-old** wife née **Jakubowicz-class**. Dawid Leyzor was already adult in the 1840s. Dan × Ester in 1862 were the parents of a marrying son, not a 22-year-old couple. A later pass that wants **Zelko** (Dan × Ester’s son, ~20 in 1856) as this father still has to lock the given name — it is **not** locked here.

**Publish:** 14? September 1856 Biała, birth **№ 33**, son **Josel Hirszberg**, father **[given unpublished] Hirszberg, 22**, mother **Chana-class née Jakubowicz-class, 22**. **Khuna is not named. Do not copy these parents onto Khuna.**

---

## 2) D9 BODY — `1856-d9-BODY-*`

**Is this Jankiel WAJNTAL? No. The BODY JPEG is Freydla Zeygman, completing akt 8.**

That is exactly what the prior TRUE leaf predicted: Szmul, then **opening of Freydla akt 8**; the next scan’s **top** finishes that akt.

### STABLE — Freydla / Freidla Zeygman (BODY JPEG)

Complete crops: `openA`/`openB`; `witA`/`witB`; `decA`/`decB`; `parA`/`parB`; `survA`; `cloA`/`cloB`; `sigA`.

| Field | STABLE | UNSTABLE |
|---|---|---|
| Folio (left) | **42** | Filename “d9”; right-gutter **10** treated as *this* akt |
| Act type | Death (*umarła* / *o zejściu*) | — |
| Year / town | **1856**; **Biała** | Drawing-up hour 9 vs 10 a.m. |
| Informants | **Chemia / Chemie Wachterman / Wuchterman**, **64**; **Szulim Piwo**-class, **40**; both **szkolnicy** of Biała | *Pino / Sino* for Piwo |
| Death | **23 February / 6 March** (*dwudziestym trzecim Lutego / szóstym Marca*), **5 a.m.** | One pass *27* February — unpublished against 23/6 on two `dec*` crops |
| Deceased | Female **Freidla / Freydla Zaigman / Zeygman** (name underlined; close *zejściu Freydli Zeygman*) | *Rychla Khuna Zeygmanowa* on one `survB` pass — **contradicts** Freydla on `par*` + `sigA`. **Contaminated** |
| Husband | **Abram Zeygman**, house-owner (*właściciela domu*), survivor age **40** | *Leygman* on one line — same man |
| Age | **36** (*trzydzieści sześć*) | — |
| Parents | Daughter of **Jankiel × Feiga** (*córka Jankla i Feigi*) | Their surname unpublished |
| Survivors | Husband Abram 40; son **Moszek / Moszka, 3**; daughters **Leja Hudes, 16**; **Złota, 7**; **Ita / Ite, 5** | *Leię Khunę* on `survB` — **contradicts** Leja Hudes / Złota / Ita on `cloA`/`cloB`. **Contaminated** |
| Right gutter | **№ 10** **Gierszon** + *Kaszm…* + *z Rad…* (facing / next akt) | — |
| Khuna | **Not named** | Tight tiles and `survB` |

**This BODY file cannot be tested as JRI 1856 D9.** It is not Jankiel. Freydla’s father **Jankiel × Feiga** is a **different** Jankiel from Wajntal unless a later akt proves otherwise — do **not** merge.

---

## 3) Actual 1856 D9 — below the BODY crop (scan 45 bottom + scan 46 top)

**Is this Jankiel WAJNTAL? Yes** — but **not on `1856-d9-BODY-full.jpg`**. Hunt the lower half of `scan45-1856.jpg` and the top of `scan46-1856.jpg`.

### STABLE — identity / dates / age (scan 45 bottom)

Complete crops: `n9A`/`n9B`/`lmargin`; `openA`/`openB`; `witA`/`witB`; `decA`/`decB`; `parA`/`parB`/`restA`/`restB`.

| Field | STABLE |
|---|---|
| Left-margin label | **№ 9 aktu Jankiel Wajntal / Waintal** |
| Drawing-up | **Biała**, **27 February / 10 March 1856**, **2 p.m.** (*drugiej po południu*), *stawili się* |
| Informants | Same szkolnik pair: **Chemia Wechterman, 64**; **Szulim Piwo**-class, **40** |
| Death | **25 February / 8 March** (*dwudziestym piątym Lutego / ósmym Marca*), **7 a.m.** (*siódmej rano*), **umarł Jankiel Wajntal / Waintal** |
| Age | **32** (*lat trzydzieści dwa mający*) |
| Status fragment | *przy ojcu za-* (line ends; almost certainly *zamieszkały*, completed on scan 46) |

Scan 45 **ends** during that *przy ojcu za-* line. Survivor/parent names are **not** on the BODY JPEG and are **not** on the remainder of scan 45 (the next crop hits the black footer). A footer tile that “found” *i z Khuny z Wajntalów* is **contaminated** (no writing on that band).

### STABLE — parents / spouse / daughters (scan 46 top, continuation of the same akt)

Complete crops: `tA`/`tB`/`tA-inv`; `L03`/`L04`; `wA`/`wB`/`wA-inv`; `xA`; 40% overview of scan 46.

| Field | STABLE | UNSTABLE |
|---|---|---|
| Link back to akt 9 | Close *o zejściu **Jankla Wajntal*** on two complete close bands | Top-right *33* vs *9* — flourish / folio; **unpublished** as an akt number (this page **continues** № 9) |
| Parents of the deceased | **syn Josela i Fraindli** | Maiden of Fraindla unpublished. Do not add Herszberg |
| Spouse | Wife **Dwora / Dworę / Dwoirę**, age **31** | — |
| Daughters | **Gołda / Golda, 12**; second daughter age **8** (*ośm*); **Liba … Jenta, 4** (*Libę* + *Jentę lat cztery*) | Second daughter *Muniche / Munia / Hanicha* — given name unpublished. Whether *Liba Jenta* is one double name or two girls is the clerk’s list of three daughters with one age on the last; treat as **one child Liba + Jenta, age 4** unless a sharper plate splits them |
| Son | **No stable son** on the locked survivor list (wife → daughters → *Po przekonaniu*) | 1849 B68 **Beniamin Wulf** (~7 in 1856) is **not** on the locked list |
| Khuna | **Not named** | — |

Scan 46 then starts **№ 10** **Gierszon Karsmacher**-class of **Radzyń** (matches the gutter label on scan 45). That is **not** Wajntal.

### Test vs 1849 B68 and 1872 D26

| Source | What it says | Use here |
|---|---|---|
| JRI **1856 D9** | **Jankiel WAJNTAL**, given-name-only | **Matches** the locked deceased |
| JRI **1849 B68** | **Beniamin Wulf WAJNTAL**, father **Jankiel**, mother **Dwora**; index also has paternal grandfather **Josel** | Wife **Dwora** and father **Josel** **match** the locked D9 clauses. Locked survivors list **no son**. Do **not** invent Beniamin onto this page. Either he died 1849–1856, was omitted, or this is a different Jankiel×Dwora — **unresolved** |
| **1872 D26** original | Liba Enta, 19, maiden *изъ Вайнталовъ*; parents **Янкеля Герша и Двейры супруговъ Вайнталовъ**; husband **Хуну**, 19, **no patronymic** | Wife **Dwora** = **Dwejra**. Daughter **Liba**, age **4** in March 1856 ⇒ b. ~1852, vs Liba Enta ~1853 from age 19 in June 1872 — **consistent within a year**. Second name **Jenta vs Enta** not locked as the same word. This **supports** Jankiel Wajntal of D9 as Liba Enta’s father. **It does not name Khuna’s parents** |

**Publish (from scan 45+46, not from the BODY JPEG):** Jankiel WAJNTAL died Biała **25 Feb / 8 Mar 1856**, age **32**, son of **Josel × Fraindla**, left wife **Dwora, 31**, and daughters **Golda 12**, (second, 8), **Liba (Jenta) 4**. **Khuna is not named.**

---

## 4) Does either akt name Khuna?

**No.**

- B33 BODY: child **Josel**; witnesses Chemia-class + Szulim Piwo. Isolated *Khuna* on a signature invert is contaminated.
- D9 BODY: **Freydla Zeygman**. Isolated *Khuna* on `survB` is contaminated.
- Actual D9 (scan 45 bottom + 46): **Jankiel Wajntal**. No stable *Ch/Kh + una*. Hebrew for witness Chemia/Chaim is **not** Khuna Herszberg (same trap as on TRUE 31–32).

**Khuna’s father and mother remain unknown.** Do **not** treat Josel Hirszberg’s 22-year-old parents as Khuna’s. Do **not** treat Jankiel Wajntal × Dwora as Khuna’s parents (they are the **wife’s** natal household if the Liba test holds).

---

## 5) Explicit answers

| Question | B33 BODY | D9 BODY JPEG | Actual D9 (scan 45 bot + 46) |
|---|---|---|---|
| Is it the claimed akt? | **Yes** — **№ 33 Josel Hirszberg** | **No** — Freydla Zeygman, akt **8** close | **Yes** — **№ 9 Jankiel Wajntal** |
| Parents to publish | Father **Hirszberg, 22** (given name unpublished); mother **Chana-class née Jakubowicz-class, 22** | Freydla: **Jankiel × Feiga** (not the target household) | **Josel × Fraindla**; wife **Dwora, 31** |
| Age / spouse (D9) | — | Not Jankiel | Age **32**; spouse **Dwora, 31** |
| Names Khuna? | **No** | **No** | **No** |

---

## 6) Files used

- Claimed B33: `1856-b33-BODY-full.jpg`, `-margin.jpg`, `-parents.jpg`; `scan20-1856.jpg` for layout under the crop.
- Claimed D9 BODY: `1856-d9-BODY-full.jpg`, `-margin.jpg`, `-parents.jpg`.
- Layout hunt for real D9: `scan45-1856.jpg` (bottom), `scan46-1856.jpg` (top). `scan47-1856.jpg` = duplicate of 45.
- Working crops: `/tmp/b33b/`, `/tmp/b33w/`, `/tmp/d9b/`, `/tmp/d9w/`, `/tmp/d9a/`, `/tmp/d9c/` (not committed).

**Still needed:** nothing further to *identify* B33 or D9. Optional sharper plate only if someone must lock Josel’s father’s **given** name, the second D9 daughter’s given name, or whether Beniamin Wulf is omitted from D9 survivors. **Do not reopen** the Freydla BODY JPEG as D9. **Do not reuse** `1856-b33-TRUE-*` (31–32) or `1856-d9-TRUE-*` (Szmul) as these bodies.
