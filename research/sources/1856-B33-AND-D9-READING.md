# 1856 Biała — claimed B33 and D9 (palaeographic reading)

**Claimed:** jednostka **167444**, signature `35/1612/0/2.21/40`.  
**Working files:** `research/scans/1856-b33-full.jpg` (claimed scan 14, margin 33) and `research/scans/1856-d09-full.jpg` (claimed scan 61, margin 9), plus the supplied `-margin.jpg` / `-parents.jpg` crops.

This note does **not** name Khuna Herszberg’s parents. Tesseract was not used. Isolated tiles that produced query-list names (`Josel`, `Hirszberg`, `Dawid Leyzor`, `Ita`, `Wajntal`, `Beniamin Wulf`) on a zone that larger complete crops of the **same** band do not keep were treated as **contaminated**.

Method: ImageMagick `identify` / `convert` (contrast-stretch, invert, sharpen) under `/tmp/b33z/`, `/tmp/b33w/`, `/tmp/d09z/`, `/tmp/d09w/`, `/tmp/d09i/`, `/tmp/d09p/` (not git). Dual-offset complete crops of one zone. Only letter sequences that recur on **more than one complete crop** of that zone are STABLE.

---

## Verdict (both files)

| Claimed | What the JPEG actually is |
|---|---|
| **1856 B33 Josel Hirszberg** | **Wrong akt.** Two **birth** acts on one leaf: left-text **№ 21** (top) and **№ 22** (bottom). Page number top-right **11**. Not Hirszberg. |
| **1856 D9 Jankiel WAJNTAL** | **Wrong akt.** Not a death narrative. **Closing / certification** of the 1856 **death** book (Akt *Zejścia*), page **58**, with a right-edge numbered table. |

Neither leaf names **Khuna / Chuna / Huna**. Do not invent Khuna’s parents from these files.

---

## Identification of the JPEGs (geometry, not palaeography)

Paper on `1856-b33-full.jpg` (2110×3500) starts near **y=339**, x≈134–1911.  
Paper on `1856-d09-full.jpg` starts near **y=365**.

Template match of the supplied crops onto the full leaves:

| File | Best match on the full leaf | What that position is |
|---|---|---|
| `1856-b33-margin.jpg` (250×400) | **y=96, x=1704** | **Top-right** (page-number corner), mostly binding above the paper line. **Not** the left-margin akt number. |
| `1856-b33-parents.jpg` (1400×1500) | **y=1200, x=296** | End of the **top birth** + most of the **bottom birth**. |
| `1856-d09-margin.jpg` (200×300) | **y=136, x=1728** | **Top-right binding.** Almost no writing. |
| `1856-d09-parents.jpg` (1400×2000) | **y=800, x=304** | Body of the **closing** text, not a *syn / małżonki / pozostawiwszy* clause. |

Scan numbers **14** and **61** are not printed on the JPEGs. Archive filenames `35_1612_0_2.21_40_894943.jpg` / `…_894930.jpg` are downloader metadata only. Numeric ID **167444** remains the unconfirmed `/40` extrapolation unless a live jednostka page is captured.

---

## 1) Claimed B33 — `1856-b33-full.jpg`

**Layout:** two Polish-language **birth** acts, same clerk. Archive banner *Archiwum Państwowe w Lublinie* at the foot.

### STABLE (recurs on ≥2 complete crops of the same zone)

| Field | Stable letters / formula | Crops |
|---|---|---|
| Town | **Białey / Biały** in *Mieście (Powiatowem) Białey* | `open1` / `open1b`; `surn1`; `open2line`; `stawil2` |
| Year | **Tysiąc … Osiemset Pięćdziesiątego Szóstego** (1856) | `open1` / `open1b`; `stawil1-n` / `stawil1b`; `open2line` |
| Page number (top-right) | **11** | first independent read of `1856-b33-margin.jpg`; unenhanced `pagenum.jpg`. Later enhanced rereads of that **same** corner as “33 Josel” are discarded (query contamination; that crop is not a left-margin akt number). |
| Top akt number | **№ 21 Aktu** | unenhanced `open1.jpg` and enhanced `open1b-n.jpg`. Consecutive with bottom **22**. Tight `nro1*` tiles that saw a lone **9** are not used (digit *2* vs *9* in this hand; also the D9 target). |
| Bottom akt number | **№ 22 Aktu** | `nro2.jpg`, `nro2-n.jpg`, unenhanced `open2line.jpg`, and `1856-b33-parents.jpg`. Enhanced `open2line-n.jpg` “33” is discarded. |
| Act type | Birth formula **Stawił się Starozakonny** + **nadane zostały … Imiona** / **nadane zostało** | openings + naming bands |
| Month of drawing-up | **Kwietnia** (April), dual calendar; a struck-through date word on the top akt | `open1` pair; `open2line` pair |

### Top birth (akt **21**) — STABLE vs unpublished

| Field | Status | Reading |
|---|---|---|
| Child | **STABLE core; second name unpublished** | Male (**któremu**). **dwa Imiona**. First name **Szlama / Szloma** on three complete crops of the naming band (`mother1.jpg`, `mother1-n.jpg`, `mother1b-n.jpg`). **Josel** appeared only on one unenhanced pass of that band and on later tiny `two-names1*` tiles that also pulled **Dawid Leyzor** — **contaminated; not published**. |
| Father | **STABLE as Goldszmid-family goldsmith, not Herszberg** | Surname **Goldszmid / Goldsmit / Goldszmit**. Occupation **złotnik**. Age in the **twenties** (*lat dwadzieścia …*). Given-name pair **Szmul/Srul + Lejb/Leib** — Sz vs Sr not locked. |
| Mother | **Age STABLE; names unpublished** | Feminine **lat dwadzieścia dwa liczącej** (22). Maiden / given name did not recur the same way (Etla/Ita and several *-owiczów* forms). **Do not publish the mother.** |
| Is this Dan×Ester or Dawid Leyzor×Ita? | **No** | Locked identities are a **Goldszmid** goldsmith and a 22-year-old wife. **Dawid Leyzor** and **Ita** showed up only on contaminated tiles of this leaf. |
| Khuna | **Not named** | No stable **Ch/Kh + una/unem**. |

### Bottom birth (akt **22**) — STABLE vs unpublished

| Field | Status | Reading |
|---|---|---|
| Father | **STABLE** | **Icko / Icek Leyb Herszman** (Hersz + **man**). **Not** Hirszberg / Herszberg (no **-berg**). Trader (*handlarz*) on the parents crop + early full-leaf passes; age **trzydzieści dwa** (32) on those complete views. |
| Mother | **Given name STABLE; maiden unpublished** | **Hindla / Hindli**. Maiden **Zelmanowiczów** vs **Szumanów / Szynermanów** did not survive cross-crop — **unpublished**. Age **trzydzieści** (30) on two `name2*` crops. |
| Child | **Sex STABLE; given name unpublished** | Male (*dziecię płci męskiej* / *mu … nadane*). The given name is **cut off** at the bottom of `1856-b33-parents.jpg`. One early full-leaf pass offered Zelda/Ajdla; that did not recur on the naming band. **Unpublished.** |
| Witnesses | **One name STABLE** | **Chemia / Chaim Wachterman / Wuchterman / Wachturman**, szkolnik, Biała. Second szkolnik **Szulim** + age near forty — given name likely, age not locked. |
| Khuna | **Not named** | **Chemia Wachterman is not Khuna Herszberg.** Do not merge Chemia / Nechemia with Khuna. |

### What this leaf cannot do

This is **not** JRI **1856 B33 Josel HIRSZBERG**. On a 2-births-per-page book, page **11** is akts **21–22**; akt **33** would be about page **17**. Parents of Josel Hirszberg (Dan×Ester vs Dawid Leyzor×Ita vs other) are **not on this JPEG**.

---

## 2) Claimed D9 — `1856-d09-full.jpg`

**Layout:** three certification blocks, circular *Powiat Bialski* / USC stamp, registrar and *podsędek* signatures. **Right edge:** a ruled column of integers **1…24** with name-stems cut off by the gutter.

### STABLE

| Field | Stable letters / formula | Crops |
|---|---|---|
| Page number | **58** (top left) | `open.jpg`, `open-n.jpg`, `openb-n.jpg`; also `titleb-n.jpg`. Tiny `pg*` tiles that “found” *Hirsz* are discarded. |
| Book type | **Księgę niniejszą do zapisywania Akt** … (*Zejścia* / death acts on the full leaf and 40% overview) | `open*` pair; first full-leaf / `full-40` |
| Year | **Roku Tysiąc Osiemset Pięćdziesiątego Szóstego** (1856) | `l0` / `l0-n`; `count` / `count-n`; `trzydziesci-n` |
| Town | **Biała / Biały / Białey**; stamp **POWIAT BIALSKI** | `count*`; `l1-n`; `l2-n`; `l6-n`; `l8-n` |
| Closing formula | **zamyka i podpisuje** | `count*`; `l0*` |
| Date on first close | **Biała dnia 19/31 Grudnia 1856** | `count.jpg` / `count-n.jpg`; `l1-n.jpg` |
| Second close | **Sprawdziłem / Sprawdzałem i nie znalazłem nic do nadmienienia**; **Biała d. 15/27 Czerwca** | `l4-n`; full-leaf. Year after *Czerwca* is **1856 vs 1857** across crops — **unpublished**. |
| Later block | **Działo się w Sądzie … Okręgu Bialskiego**; **Burmistrz M. Biały jako Urzędnika Stanu Cywilnego** | `l6-n`; `l8-n`; full-leaf bot-half |
| Death-act count (full leaf) | **Trzydzieści Osiem** (38) | two independent full-leaf / 40% reads of the same opening block |
| Right table | Integers in a column, including a **9** | `row9.jpg`, `row9-n.jpg`, `row9b-n.jpg`. The **name** to the right of **9** is **off the scan edge** (only a capital flourish). |

### Deceased / parents / spouse / age / survivors

**Unpublished — not present as an akt.** A closing page does not have *umarł*, *syn*, *małżonka*, or *pozostawiwszy*.

`1856-d09-margin.jpg` is the wrong corner (binding). It does **not** show left-margin **№ 9**.

### Test: is this Liba Enta’s father Jankiel × Dwora?

**Cannot be tested on this JPEG.** The narrative of death akt **9** is not here.

External comparanda (not read from these 1856 files):

| Source | What it says | Use here |
|---|---|---|
| JRI **1856 D9** | **Jankiel WAJNTAL**, given-name-only | Index claim only. Does not prove this leaf is that akt. |
| JRI **1849 B68** | **Beniamin Wulf WAJNTAL**, father **Jankiel**, mother **Dwora** | Wife-natal household. Original B68 **not** in this file set. Tiny D09 title tiles that “found” **68 Beniamin Wulf** are **contaminated** from this comparandum. |
| **1872 D26** original (scan 113, already read) | Liba Enta, maiden **изъ Вайнталовъ**; parents **Янкеля Герша и Двейры супруговъ Вайнталовъ**; husband **Хуну** age 19 **without** patronymic | Identifies Liba’s parents as Yankel Hersz × Dwejra WAJNTAL. **Does not** identify the man on a missing 1856 D9 page. |

Until the **death narrative** for akt **9** is on a leaf with left-margin **№ 9**, do **not** assume JRI D9 is Liba’s father, and do **not** assume spouse **Dwora** or any age/survivors.

Right-column **9** + a cut-off capital is **not** a stable **Wajntal Jankiel**.

### Khuna

**Not named.** No *Herszberg / Hirszberg*. No *Khuna / Chuna / Huna*.

---

## 3) Does either akt name Khuna?

**No.**

- Claimed B33 leaf: Goldszmid birth + Herszman birth. Witness **Chemia Wachterman** is a szkolnik, **not** Khuna Herszberg.
- Claimed D9 leaf: book close. No personal names of a deceased family in the locked text.

Khuna’s father and mother remain **unknown**.

---

## 4) Files used

- Claimed B33: `1856-b33-full.jpg`, `1856-b33-margin.jpg`, `1856-b33-parents.jpg`.
- Claimed D9: `1856-d09-full.jpg`, `1856-d09-margin.jpg`, `1856-d09-parents.jpg`.
- Working crops: `/tmp/b33z/`, `/tmp/b33w/`, `/tmp/d09z/`, `/tmp/d09w/`, `/tmp/d09i/`, `/tmp/d09p/` (not committed).

**Still needed (not these JPEGs):** 1856 birth leaf with left-margin **№ 33** (Josel Hirszberg); 1856 death leaf with left-margin **№ 9** (Jankiel Wajntal narrative).
