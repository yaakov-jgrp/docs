# 1865 M27 claimed leaf — `1865-m27-PESZA-*` is **akt 26**, not Pesza × Litman

**Not Pesza Herszberg × Jeremiasz Litman. Not Khuna Herszberg’s parents.** Do not copy any parent names from these plates onto Khuna, Pesza, Dan × Ester, Zysza × Jochwet, or Abram × Chana Tauba.

Method: ImageMagick contrast / invert / line and band crops under `/tmp/m27p/` (not git). Tesseract was **not** used and is **not** evidence. Only letter sequences seen on **more than one complete crop of the same zone** are marked STABLE. Isolated thin tiles that “find” Herszberg / Litman / Pesza / Khuna / Dan on the wrong line are **contaminated** (filename- and question-primed) and unpublished.

Prior false positive (do **not** reuse): `1865-m27-VERIFIED-*` = **1865 marriage akt 17**, page **83**, Mendel Mink/Minc × Ruchla Leja Edelsztejn. This JPEG is a different leaf (NCC vs `VERIFIED-full.jpg` ≈ 0.67).

Jednostka context (from prior map, not re-fetched here): APL `35/1612/0/2.21/48`, jedn. **167452**, 1865 Biała BMD. Hunt for real M27 remains: marriage section, left margin **№ 27**, surnames Herszberg + Litman.

Working files (untracked scans; palaeography only):

| File | What it actually is |
|---|---|
| `research/scans/1865-m27-PESZA-full.jpg` | 2183×3500 archival JPEG. **Claimed** SWA **scan 96** of jedn. 167452 (meta: `35_1612_0_2.21_48_894008.jpg`). Paper begins ~y=270 (rows 0–260 are black scanner bar). |
| `research/scans/1865-m27-PESZA-margin.jpg` | 200×400. Pixel match to the full leaf at **(50, 100)** (subimage RMSE ≈ 0.005). Left-margin **№ 26**, not 27. |
| `research/scans/1865-m27-PESZA-bride-parents.jpg` | 1400×1200. Pixel match to the full leaf at **(400, 1500)** (NCC ≈ 0.9996). Ceremony / banns / consent band of **this same akt 26**, not a separate Pesza-parents plate. |
| `research/scans/1865-m27-CANDIDATE-scan92-full.jpg` | Context only. Different leaf (NCC ≈ 0.72). Folio **88**; not M27. |
| `research/scans/1865-m27-PESZA-meta.txt` | **Wrong** on akt number (“№ 27 at top left”). Discard that claim. |

---

## 1. Page, margin numbers, year, town — STABLE

These recur on independent **complete** crops of the same zone (opening band / paper-top / left-margin plate), not on 85 px line tiles:

| Field | STABLE | UNSTABLE / do not use |
|---|---|---|
| Archival JPEG | Claimed **scan 96** of jedn. **167452**, 2183×3500 | Do not treat **96** as the clerk’s folio |
| Folio on the paper | **92** (complete paper-top band + several opening-band crops of the same header) | Center-only squares and one full-page pass also read **93**. Not locked as a second folio. Tiny black-bar crops that read 96/27 are the scanner bar / filename priming |
| **This leaf’s akt** | Left margin **№ 26.** (margin JPEG; `akt-left` color + sigmoidal; left-strip; opening band showing left **26** and right **27** together) | Meta/filename “m27”; isolated right-gutter **27** treated as *this* page’s number |
| Facing / gutter number | Right-edge **№ 27.** belongs to the **next / facing** leaf, same pattern as 1865 D32 (`№ 33/34` on the gutter, not the body) | Do not index this JPEG as marriage **27** |
| Year / town / opening | **1865** (*tysiąc ośmset sześćdziesiąt piątego*); **Biała** (*w mieście Powiatowem Białej*); **13 June** (*trzynastego Czerwca*); **7 p.m.** (*siódmej po południu*) | One pass pulled *Janowie* into the *Działo się* line — that is the groom’s town leaking; opening formula is Biała. *czwartek* on one thin tile is a *Czerwca / sześćdziesiąt* misread |
| Officiant | District rabbi **Wolf Borensztejn / Borenstein / Bronstein** (*Rabin Okręgu Białej*) | *Pomorski / Pomeranc* — primed from other leaves / ceremony wording |

**This page’s body is one marriage akt, matching left-margin 26.** Akt **27** is not the text on this JPEG.

Layout check vs claimed scan **92** (folio **88**, akt **22** body with **23** starting at the right gutter, 8 June 1865): four scans later is folio **~92** and akt **~26**. That arithmetic matches this leaf. Real **M27** is the **next** marriage scan (left margin **№ 27**), not this file.

---

## 2. Couple — STABLE vs unpublished

Complete couple-zone crops (independent bands covering y≈500–1100, plus the ceremony restatement at y≈1450–1750):

| Field | STABLE | UNSTABLE / unpublished |
|---|---|---|
| Groom given name | **Beniamin** (instrumental *Beniaminem*), *kawaler* | Isolated tiles: *Jeremiasz Litmanem*, *Szymonem Litmanem*. Those contradict Beniamin on every complete couple + ceremony band of the same zone |
| Groom age | **18** (*ośmnaście / osiemnaście skończonych*) | — |
| Groom occupation | **krawieckiej** (tailor), *utrzymującym się* | *handlowej / szmuklerz* on thin tiles |
| Groom parents | Mother **Ryfka**; both parents **nieżyjących** (deceased); surname same **-baum** family as the groom | Father’s given name **Joel** is the most repeated complete-crop reading (*z Joela i Ryfki*) but *Icek / Berek / Judka* appeared on other passes of the same band — **do not lock the father’s given name** |
| Groom surname | **-baum** name; spelling that survives on the most complete couple bands: **Ajzenbaum / Ejzenbaum** | One-off *Dyzenhauz, Tyfenbaun, Fijszenbaum / Fyszenbaum, Zyzenbaum, Lejzenbaum, Syporborn*. Unpublished as fact |
| Groom residence / birth | **Not Biała** (he is an incomer; banns also name a second town) | *Łomazy* vs *Janów / Janowiec Podlaski* vs *Sarnaki / Sanniki* vs *Bielsko* — not locked |
| Bride given name | **Not Pesza.** Instrumental ***-ejlą*** (*Leją* and *Kejlą* both recur; *Chają Leją* once) | Exact choice **Leja vs Kejla** unpublished. Isolated *Peszą Herszkowną* is contaminated |
| Bride age / status | **17** (*siedemnaście / siedmnaście skończonych*), *panna* | One complete-band pass pulled mother’s **Małka** into the bride slot — reject |
| Bride surname | Same family as her parents: **M…baum** class | Exact letters float (*Majbaum, Mehlbaum, Mastbaum, Mandelbaum, Mochtbaum, Maulbaum, Maszbaum, Moszków, Matlkann, Mośkiewicz, Markówna*). **Not Herszberg.** Exact spelling unpublished |
| Bride residence | **Biała** — *urodzoną i zamieszkałą*, *przy rodzicach*, supported from parents’ *zarobek* | — |

**Is this Pesza Herszberg × Jeremiasz Litman? No.**

---

## 3. Parent clauses — STABLE vs unpublished

| Side | STABLE | UNSTABLE / unpublished |
|---|---|---|
| Groom | Son of **… × Ryfka**, spouses **[Ajzenbaum-class]**, **both deceased** | Father’s given name not locked (see above) |
| Bride | Daughter of **Abram** and **Małka**, spouses **[M…baum-class]**, **both living** in **Biała**. Father **Abram** is **present** (*w przytomności Abrama … ojca*) and gives **oral consent** | Exact parental surname spelling unpublished. Isolated tile *córką Khuny i Racheli … Herszbergów* is **contaminated** (wrong line, names from the research question) |

**Does it name Khuna?** **No** as a party, parent, or patronymic. A witness-line reading *Khuna / Kuchna / Juchma Piwo* appeared on some complete crops of the świadkowie band and **contradicts** *Szulim / Pinkus Piwo* on other complete crops of the **same** band. Treat Khuna-on-Piwo as unpublished contamination. Do not invent Khuna’s parents from this leaf.

**Does the bride’s father match Dan × Ester, Zysza × Jochwet, or Abram × Chana Tauba?** **None of those.** Father **Abram**, mother **Małka**, surname **not Herszberg**. Sharing the given name Abram with the Abram × Chana Tauba household is **not** a match (mother is Małka, not Chana Tauba).

---

## 4. Banns, consent, witnesses, signatures

| Field | STABLE | UNSTABLE |
|---|---|---|
| Banns | Three *zapowiedzi*; Jewish synagogues in **Biała** and a second town (Janów-class) | Exact ordinal days (6 vs 7, then 14 and 21 of the current year) not locked |
| Groom consent | Orphan: **rada familijna** (family-council) permission, January of the current year (*trzydziestego Stycznia* recurs) | Exact council-akt wording unpublished |
| Bride consent | Oral consent of father **Abram**, present | — |
| Witnesses | Two **szkolnicy** residing in **Biała**: surname **Piwo** + surname **Zilbersztejn / Zelbersztejn / Silbersztejn**. Second witness age **64** (*sześćdziesiąt cztery*) is the better-repeated figure | Piwo given name (*Szulim* vs *Pinkus*) not locked; *Khuna Piwo* unpublished. Piwo age 56 vs 70/76 not locked (56 matches the same clerk’s 5 June 1865 D32 pair, but is not re-locked here) |
| Close | *Akt ten … przeczytany*; *inni stawiający pisać nie umieją* | — |
| Signatures | Rabbi **Wolf Borensztejn**; **Abram** (bride’s father) with Hebrew signature / *Znaczy Abram …*; witness **Zilbersztejn**; **Utrzymujący Akta Stanu Cywilnego** | Exact Latin spelling of Abram’s surname in the signature line unpublished. *Mink / Pomorski* on one lower-page pass is bleed from the **akt 17** false-positive file — reject |

`1865-m27-PESZA-bride-parents.jpg` is this **ceremony / banns / consent** strip (y=1500), not the first identity/parent clause (that sits higher, ~y=700–1200). Same failure mode as `1865-m27-VERIFIED-bride-parents.jpg`.

---

## 5. Context leaf: `1865-m27-CANDIDATE-scan92-full.jpg`

Context only; not fully dual-cropped to the same standard.

| Field | Reading |
|---|---|
| Folio | **88** (opening-band crops) |
| Akt | Body of a **8 June 1865** Biała marriage; right gutter starts **akt 23**. This is **not** left-margin **№ 27** |
| Couple | **Not** Pesza Herszberg × Litman on the complete opening/couple bands used here |
| Khuna | Do **not** harvest a groom’s-father “Khunim / Kuchim” from this leaf. Wrong akt, and that reading was not locked on two complete crops of the same parent zone in this pass |

---

## 6. What to publish vs not

**Publish**

- Claimed scan **96** / jedn. **167452** / 2183×3500 is **1865 Biała marriage akt № 26**, folio **92**, drawn up **13 June 1865**.
- Couple: **Beniamin [Ajzenbaum/Ejzenbaum-class]** (18, tailor, parents deceased, mother **Ryfka**) × **Leja or Kejla [M…baum-class]** (17, of Biała, daughter of **Abram × Małka**, father present).
- **Not** Pesza Herszberg × Jeremiasz Litman.
- **Does not name Khuna** as parent or party.
- Bride’s father is **none of** Dan×Ester / Zysza×Jochwet / Abram×Chana Tauba.
- Right-margin **27** is the **next** akt, not this text.
- Real **1865 M27** is still unread: jedn. 167452 marriage section, **left** margin **№ 27**, surnames Herszberg + Litman (likely the **next** scan after this JPEG).

**Do not publish**

- Exact locked spellings of either surname beyond the **-baum / M…baum** class.
- Groom’s father’s given name.
- Groom’s town (Łomazy vs Janów).
- Bride given name as a single locked form (Leja vs Kejla).
- Khuna / Rachela / Herszberg / Pesza / Litman / Dan from isolated tiles.
- Any statement that this leaf names Khuna’s parents.
- Reuse of `1865-m27-VERIFIED-*` (akt **17**) or this `PESZA-*` set (akt **26**) as M27.

**Do not commit these JPEGs as Khuna parentage.** This note does not name Khuna’s father or mother.
