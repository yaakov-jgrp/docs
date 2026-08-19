# Claimed “TRUE” target akts — palaeographic reading (four leaves)

**Do not copy any parent names from these plates onto Khuna.** This note does **not** name Khuna Herszberg’s father or mother.

Method: ImageMagick `identify` / `convert` (contrast-stretch, invert, sigmoidal-contrast, dual-offset complete bands) under `/tmp/t-m27/`, `/tmp/t-b48/`, `/tmp/t-b33/`, `/tmp/t-d9/` (not git). Tesseract was **not** used and is **not** evidence. Only letter sequences seen on **more than one complete crop of the same zone** are STABLE. Isolated tiles and any single vision pass that “find” Herszberg / Litman / Khuna / Dan / Wajntal from the research question on the **wrong line** are **contaminated**. Filenames, `TRUE-TARGETS-meta.txt`, and one overview of a full leaf are **not** evidence.

Geometry (not palaeography): each `*-TRUE-margin.jpg` is the **left strip** of the matching full JPEG (NCC = 1.0 at **x=0**, full height). Each `*-TRUE-parents.jpg` is a nearly full-height body column at **x≈14** (NCC ≈ 0.99), **not** a separate parents plate. Do not treat those supplied files as independent leaves.

These four JPEGs are **different paper** from the earlier false-positive set (NCC vs `1865-m27-PESZA-full.jpg` / `1860-b48-full.jpg` / `1856-b33-full.jpg` / `1856-d09-full.jpg` ≈ 0.58–0.71). `1865-m27-TRUE-full.jpg` **is** identical to `1865-m27-scan97-temp.jpg` (RMSE 0, same MD5).

| Claimed | What these JPEGs actually are | Target akt? | Names Khuna? |
|---|---|---|---|
| **1865 M27** Pesza Herszberg × Jeremiasz Litman | **Yes — marriage akt № 27**, folio **93**, 26 August 1865, Biała. Couple STABLE. Bride’s parents STABLE as **Zysia × Jochwet Herszberg**, both deceased. | **Yes** | **No** |
| **1860 B48** Chaja Ruchla Hirszberg | Page **24**, births **№ 47** (top) and **№ 48** (bottom). Akt 48 child **Chaja Ruchla** STABLE. Father’s surname **not locked as Hirszberg**. | **Akt 48 yes; Hirszberg household not locked** | **No** |
| **1856 B33** Josel Hirszberg | Births **№ 31** (Chawa Gitla) and **№ 32** (Rejza Gampel). Right gutter labels the **next** akt **№ 33 Josel Hirszberg** — body unread. | **No** | **No** |
| **1856 D9** Jankiel WAJNTAL | Death narrative of **Szmul Wolecki** (Boruch × Ryfka), not Wajntal. Left-margin **7 vs 9** not locked. | **No** | **No** |

---

## 1) 1865 M27 — `1865-m27-TRUE-*`

**Is this Pesza Herszberg × Jeremiasz Litman? Yes.**

Prior leaf `1865-m27-PESZA-full.jpg` is marriage **akt 26** (folio **92**, 13 June 1865). This JPEG is the **next** marriage page: folio **93**, left-margin **№ 27**. Scan-number **97** is downloader metadata; it is **not** printed as the clerk’s folio.

### STABLE (recurs on ≥2 complete crops of the same zone)

| Field | STABLE | Crops |
|---|---|---|
| This leaf’s akt | Left-margin **№ 27.** | `hdr1` / `hdr2` / `hdr1-inv`; `open1` / `open2` |
| Folio on the paper | **93** | `hdr1`, `hdr2`, `hdr1-inv`. Tiny black-bar / filename “97” discarded |
| Year / town / drawing-up | **1865** (*tysiąc ośmset sześćdziesiąt piątego*); **Biała** (*w Mieście Powiatowym Białej*); **26 August** (*dwudziestego szóstego Sierpnia*); **6 p.m.** (*szóstej po południu*) | `hdr*` pair + invert; `open1` / `open2` |
| Officiant | District rabbi **Wolf Borensztejn / Berensztejn / Berenstein** (*Rabin Okręgu Białej*) | `open1` / `open2`; restated on `wit1` (*Rabina Wolfa Borensztejna*) |
| Groom | **Jeremiasz Litman** (*Jeremiaszem / Jeremjaszem Litman*), *kawaler*, **19** (*lat dziewiętnaście*), cooper (*z bednarstwa utrzymującym się*), born and residing in **Biała** | `open1`/`open2`; `couple1`/`couple2`/`couple1-inv`; `p-couple`; ceremony `cer1`/`cer2`; close `wit1` |
| Groom’s parents | **Moszek / Mośka × Rejzla**, spouses **Litman**. Father **Moszka Litman** is **present** (*w przytomności … ojca Jeremiasza*) and gives oral consent | `couple1`/`couple2`/`couple1-inv`; `p-couple` (*Mocka i Rejzli*); `par1`/`par2`/`par1-inv`; `cer2` |
| Bride | **Pesza Herszberg** (*Peszą Herszberg*), *panna*, **21** (*lat dwadzieścia jeden skończonych*), born and residing in **Biała**, *przy familii* | `couple1`/`couple2`/`couple1-inv`; `p-couple`; `cer1`/`cer2`; `par2` |
| Bride’s parents | **Zysia / Zysio × Jochwet**, spouses **Herszberg**, **both already deceased** (*obojga już nieżyjących*) | `couple1`, `couple2`, `couple1-inv` (same couple-zone, independent offsets / invert). `par1` restates *małżonków Herszberg obojga już nieżyjących* without repeating the given names |
| Banns | Three *zapowiedzi* on **15, 22, and 29 July** of the current year, Jewish synagogue in **Biała** | `cer1` / `cer2` |
| Witnesses (core) | Two **szkolnicy** of Biała: **Szulim Piwo**, age **56** | `par1` / `par2` / `par1-inv` |
| Close | *Akt ten … przeczytany*; newlyweds declare **no** prenuptial contract; *inni stawający pisać nie umieją*; signed by the rabbi, **Jeremiasz Litman**, and both witnesses | `wit1`; `par*` |

**Does it name Khuna?** **No** as a party, parent, or patronymic. A left-gutter thin crop (`lnum2`) that “found” *…huna* is an isolated tile on line endings — **contaminated; unpublished**.

**Do not force Lejzor × Dana or Dan × Ester.** Those names do **not** appear on the locked couple / parent bands.

### UNSTABLE / unpublished

| Topic | Conflict | This pass |
|---|---|---|
| Groom’s mother as *Ryfka* | Overview-only | Complete couple bands lock **Rejzla**. *Ryfka* unpublished |
| Second witness given name / age | *Iajdle / Zaydie / Fajdla / Icko Zylbersztejn*; 54 vs 44 | Surname **Zylbersztejn** class is repeated; exact given name and age **unpublished** |
| Isolated *Pesia / Beniamin / Czerwca* on `lnum*` / `m-num` | Tight left-strip tiles | Those are line-ends / prior-leaf priming (akt **26** was Beniamin, June). Reject against complete openings |
| Full-page overview that named Zysia × Jochwet on first sight | One pass of `full40` | Used only after the **same** letters recurred on three complete couple-zone crops |

### Test vs 1844 B66 / 1847 D38 (external JRI, not read from these JPEGs)

| Source | What it says | Use here |
|---|---|---|
| JRI **1865 M27** | Pesza HERSZBERG × Jeremiasz LITMAN, parents **blank** | Index. Original now supplies the parents |
| JRI **1844 B66** | Pesza HERSZBERG, father **Zjska / Zysza**, mother **Jochwet** | Age **21** in August 1865 ⇒ born ~1844. **Consistent** with the locked Zysia × Jochwet clause. Does not by itself prove Khuna is of that household |
| JRI **1847 D38** | Jochwet Herszberg d. age 36; survived by husband **Zysza**, son **Leyzor**, daughter **Pesia** | Jochwet dead by 1847. This 1865 akt says **both** Herszberg parents already deceased ⇒ Zysza died **1847–1865**. **Consistent**, not a new parentage for Khuna |

**Publish:** Pesza (21) of Biała, daughter of **Zysia × Jochwet Herszberg** (both deceased) × Jeremiasz Litman (19, cooper, son of **Moszek × Rejzla Litman**, father present). **Not** Dan × Ester. **Not** Lejzor × Dana. **Khuna is not named.** Do **not** treat Zysia × Jochwet as Khuna’s parents.

---

## 2) 1860 B48 — `1860-b48-TRUE-*`

**Is this birth akt 48? Yes. Is the locked household Hirszberg? No — father’s surname not locked.**

Prior leaf `1860-b48-full.jpg` is page **23**, akts **45–46** (Openhejm / Akerman). This JPEG is page **24**. Two births per page ⇒ **47–48**. Right-gutter **49 / 50** belong to the **facing** leaf (same pattern as 1865 D32 and M26).

### Page / numbers — STABLE

| Field | STABLE | UNSTABLE |
|---|---|---|
| Page | **24** | Scanner-bar tiles |
| Upper left-margin akt | **№ 47**, town word **Biała** | Filename “b48”; right-gutter **49** treated as *this* akt |
| Lower left-margin akt | **№ 48**, town word **Biała** | Right-gutter **50** treated as *this* akt |
| Year / town | **1860** (*tysiąc osiemset sześćdziesiątego*); **Biała** | — |

### Upper akt (№ 47) — STABLE vs unpublished

Complete crops: `uopen1`/`uopen2`, `hdr1`, `ufather1`, `umom1`.

| Field | STABLE | UNSTABLE / contaminated |
|---|---|---|
| Drawing-up | **22 June 1860**, **4 p.m.** | — |
| Declarant | **Lejbuś / Lejzor** Goldstein-class, *wyrobnik*, age **29**, of Biała | *Lejzor Herszberg / Hirszberg* on `uopen1`/`uopen2` **contradicts** Goldstein on `ufather1`/`umom1` and the signature *Lejbuś Goldstein*. **Rejected** |
| Child | **Male**; given names **Zyskind Lejb**; *przy obrzezaniu* | — |
| Birth | **14 June**, **9 a.m.**, Biała | — |
| Mother | Wife **Goldsztejn / Goldstein**, age **30** | Exact given name (*Siffra / Szifra / Sura*) unpublished |
| Witnesses | **Chemia Wachtmann**-class (same clerk’s szkolnik pair) | Isolated `uopen2` *i Khuna* — **contaminated; unpublished** |
| Khuna | **Not named** | — |

**Household: other** (Goldstein). Not Dan × Ester, not Dawid Leyzor × Ita, not Abram × Chana Tauba, not Hirszberg.

### Lower akt (№ 48) — STABLE vs unpublished

Complete crops: `lopen1`/`lopen1-inv`/`lopen2`; `lfather1`; `lmom1`/`lmom2`; `p-lmom`.

| Field | STABLE | UNSTABLE / unpublished |
|---|---|---|
| Drawing-up | **June**, afternoon (*piątej po południu*). **27** vs **20** of June conflict across `lopen1` and `lopen2` | Exact day unpublished |
| Child | Female naming formula. Given names **Chaja Ruchla** on **three** complete close/naming crops (`lmom1`, `lmom2`, `p-lmom`) | Tight margin tiles that invent the name without the *Imiona* clause |
| Mother | Age **30** (*lat trzydzieści liczącej*) | Given name *Mendelka Herszowna* vs *Małka z Herszsohnów* — **unpublished** |
| Father / surname | Opening clause: **Icko** + **Herszsohn / Herszenshorn / Herszkowicz**-class, occupation **furman** (`lopen1`, invert, `lopen2`). Age **42 vs 22** conflict | Close *Znaczy jest: Hersz Hirszberg* / Hebrew *הירשבערג* on `lmom2` **contradicts** the opening surname class. **Do not lock Hirszberg. Do not lock Icko vs Hersz.** Occupation *furman* vs *szkolnik* on `lfather1` — the szkolnik/Chemja-Hirszberg father reading is **contaminated** (witness Chemia pulled into the father slot) |
| Witnesses | Chemia-class + Piwo/Pivo-class of Biała | Exact witness surnames (*Wajntraub / Lichtermann / Wilsztein / Akerman / Szwarc*) unpublished |
| Khuna | **Not named** | — |

**Is this JRI 1860 B48 Chaja Ruchla HIRSZBERG?** It **is** 1860 Biała **akt 48**, and the child’s given names **Chaja Ruchla** are locked. The **surname Hirszberg is not locked** (opening Herszsohn/owicz-class vs signature Hirszberg). **Do not publish the parents.**

**Does it name Khuna?** **No.**

---

## 3) 1856 B33 — `1856-b33-TRUE-*`

**Is this Josel Hirszberg, akt 33? No.**

Prior false-positive `1856-b33-full.jpg` is page **11**, births **21–22**. Five birth-pages later is page **16**, akts **31–32**. That arithmetic matches **this** leaf. Akt **33** is the **next** birth scan.

This JPEG is **one page** (2110×3500; no centre-fold), not a 31–34 spread. Left margin = **this** page; right gutter = **facing** page.

### STABLE

| Field | STABLE | Crops |
|---|---|---|
| Year / town | **1856** (*Tysiąc Osiemset Pięćdziesiątego Szóstego*); **Biała** | `uopenA`/`uopen1`; `lopenA`; `umom*`; `lfather1`/`lmom1` |
| This page, top akt | Left-margin **№ 31** **Chawa / Chawy Gitla** (Nowomiast-class on the margin label) | `lnum-top1`; `n31tight` (*Gittel*); naming `umom1`/`umom2` (*dwa Imiona Chawa Gitla / Gittla*) |
| This page, bottom akt | Left-margin **№ 32** **Rejza / Rejzy Gampel** | `lnum-bot1`; `n32tight`; naming `lmom1` (*Imię Rejza*); signatures **Beniamin Gampel / Gumpel** in Polish **and** Hebrew |
| Facing / gutter | Right-edge **№ 33 Aktu Josela Hirszberg z Biały** | `rightgutter-top`; `uopen1` right column; `pg1` locks the **33**. This is the **next** akt’s label, **not** the body on this JPEG |

### Top birth (akt **31**) — STABLE vs unpublished

| Field | STABLE | UNSTABLE |
|---|---|---|
| Child | **Female**; two names **Chawa Gitla** | — |
| Birth | **9/21 May**, **4 a.m.** | Dual-calendar wording unpublished beyond 9/21 May |
| Mother | **Szejna**, age **30** | Maiden *z Kuchów* vs *z Szyk…* — **unpublished** |
| Father | Present; signs in the Lejzor/Szmul-Lejzor class | *Lejzor Hirszberg, handlarz, 40* on `uopenA`/`ufather1` **contradicts** the left-margin **Nowomiast** label for this same akt. That Hirszberg father is **question-primed from akt 33 in the gutter. Unpublished.** |
| Khuna | **Not named** | *Ch…* on a tight margin tile is **Chawa**, not Khuna |

### Bottom birth (akt **32**) — STABLE vs unpublished

| Field | STABLE | UNSTABLE |
|---|---|---|
| Drawing-up | **29 August 1856**, afternoon | — |
| Father | **Beniamin Gampel / Gumpel**, age **19**, *przy rodzicach*, Biała | — |
| Mother | **Ryfka** *Abramowiczów*, on `lmom1` | Needs no second given-name lock beyond Ryfka; maiden spelling unpublished if it floats |
| Child | **Female**; **Rejza**, born **12/24 August**, **2 p.m.** | — |
| Witnesses | **Szulim Piwo** ~40; second szkolnik Chemia/Chaim Wachterman-class | `lfather1` *Chemii Litman* — **contaminated** from the M27 question. Signatures on `lmom1` are **Chaim Wachterman** + **Beniamin Gampel** (Polish and Hebrew) |
| Khuna | **Not named** | — |

**Publish:** this leaf is **not** JRI **1856 B33 Josel HIRSZBERG**. Hunt the **next** 1856 birth scan (left margin **№ 33**). The gutter label *Josela Hirszberg* is **not** a parent clause and does **not** name Khuna.

A full-page overview that put **Lejzor Hirszberg × Dana née Litman** on akt 33 **on this JPEG** is **contaminated** (Dan/Dana + Litman from the research question). Those names are **not** on the locked bands of akts 31–32.

---

## 4) 1856 D9 — `1856-d9-TRUE-*`

**Is this Jankiel WAJNTAL? No.**

Prior false-positive `1856-d09-full.jpg` is the **closing** of the 1856 death book (page **58**), not a death narrative. This JPEG **is** a death-narrative leaf, but the deceased who is locked is **not** Wajntal.

### Layout

Top of the paper: **close** of a previous death (**Ruda Hochmanowa**, surviving children including **Hersz** age 4 and **Szajndla** — `hdr1`/`uopen1`). Then a full death akt of **Szmul Wolecki**. Then the **opening** of the next akt (**Freydla**, February/March).

### STABLE — Szmul Wolecki death

Complete crops: `lopen1`/`lopen2`; `ldec1`; `udec1`/`udec2`; `usurv1`.

| Field | STABLE | UNSTABLE |
|---|---|---|
| Act type | Death (*zmarł* / *o zejściu*) | — |
| Town / year | **Biała**; **1856** | — |
| Deceased | **Szmul Wolecki / Woliński / Wołecki** | — |
| Age / status / occupation | **45**; **widower** (*wdowiec*); **wyrobnik** | — |
| Parents | **Boruch × Ryfka / Rywka**, spouses **Wolecki** | — |
| Survivor | Son **Srul**, **19** | Overview *Szul* — unpublished against *Srul* on two `lopen*` crops |
| Witnesses | **Chemia / Chaim Wechterman / Wachterman** and **Szulim Piwo**, szkolnicy of Biała (Polish + Hebrew signatures) | Exact ages 40 vs 64 unpublished |
| Khuna | **Not named** | — |
| Left-margin number of this akt | **7 vs 9 conflict** | `udec1` *Nro 7*; `udec2`/`usurv1` *№ 9*. Next-akt opening on `lsurv1` is **№ 8 Freydla** (25 Feb / 8 Mar), which fits **Szmul = 7**, not 9. **Not locked.** Digit 7/9 in this hand is a known trap |

**Is this JRI 1856 D9 Jankiel WAJNTAL? No.** Even if a later pass locks the margin as 9, the locked deceased is **Szmul Wolecki**, son of **Boruch × Ryfka**, not Jankiel.

### Test vs 1849 B68 and 1872 D26

| Source | What it says | Use here |
|---|---|---|
| JRI **1856 D9** | **Jankiel WAJNTAL**, given-name-only | Index. **Does not match** the locked Szmul Wolecki narrative |
| JRI **1849 B68** | **Beniamin Wulf WAJNTAL**, father **Jankiel**, mother **Dwora** | Wife-natal household. **Not** this leaf (parents here are Boruch × Ryfka **Wolecki**) |
| **1872 D26** original | Liba Enta, maiden *изъ Вайнталовъ*; parents **Янкеля Герша и Двейры супруговъ Вайнталовъ** | Identifies Liba’s parents as Yankel Hersz × Dwejra WAJNTAL. **Not** the man on this JPEG |

Do **not** assume 1856 D9 is Liba’s father until a death leaf with a locked **Jankiel WAJNTAL** narrative is read.

**Does it name Khuna?** **No.**

---

## 5) Explicit answers

| Question | 1865 M27 TRUE | 1860 B48 TRUE | 1856 B33 TRUE | 1856 D9 TRUE |
|---|---|---|---|---|
| Is each the target akt? | **Yes** — Pesza Herszberg × Jeremiasz Litman, left-margin **27** | **Akt 48 yes**; JRI **Hirszberg** surname **not locked** | **No** — this page is **31–32**; Josel is the **next** leaf | **No** — locked deceased is **Szmul Wolecki**, not Jankiel Wajntal |
| Does any name Khuna? | **No** | **No** | **No** | **No** |
| Parent names to publish | **Yes, locked:** bride **Zysia × Jochwet Herszberg** (both deceased); groom **Moszek × Rejzla Litman** | **No** — father/mother of Chaja Ruchla unpublished | **No** for Josel (unread). Akt 32: Beniamin Gampel × Ryfka (not the target) | **No** for Wajntal. Szmul’s parents **Boruch × Ryfka Wolecki** are not the target household |

---

## 6) What to hunt next (do not reuse the wrong bodies)

| Still needed | Where |
|---|---|
| Nothing further for **1865 M27** couple/parents | This JPEG is the akt. Do not reopen `PESZA-*` (akt 26) or `VERIFIED-*` (akt 17) |
| 1860 B48 **parents / surname** if a cleaner opening-clause crop can lock Herszsohn vs Hirszberg | Same leaf, **opening** of akt 48 only — not signature-line invention |
| **1856 B33 Josel Hirszberg** body | Jedn. **167444**, **next** birth scan after this JPEG; **left** margin **№ 33** |
| **1856 D9 Jankiel WAJNTAL** narrative | Jedn. **167444** death section; leaf whose **left** margin and **body** both lock **Jankiel** + **Wajntal**. Do not reuse this Szmul Wolecki leaf |

**Khuna’s father and mother remain unknown.** Pesza’s locked parents (Zysia × Jochwet) are a **sibling test only**. They are **not** to be published as Khuna’s parents.
