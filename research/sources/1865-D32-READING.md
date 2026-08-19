# 1865 Biała Podlaska death akt 32 — palaeographic reading

**Leaf:** jednostka **167452**, scan **118**, working file `research/scans/1865-D32-full-page.jpg`.  
**Page number** on the leaf: **114**.  
**Layout:** two **death** akts on one Polish-language page. Left margin **№ 31** (top) and **№ 32** (bottom). Right-edge numbers **№ 33 / № 34** belong to the facing leaf. Archiwum Państwowe w Lublinie stamp across the text.

This cannot be Khuna/Chuna Herszberg dying. He is alive in 1872 D26 and 1890 B101. This note does **not** claim Khuna’s parents.

Tesseract `pol+eng` (PSM 6) and OSD were run; OCR is garbage on this cursive (OSD even guessed Japanese / 180°). OCR is **not** used as evidence.

Method: ImageMagick `identify`/`convert` contrast, invert, sharpen, and tight crops under `/tmp/d32-work/` (not git), plus line/word splits of `1865-d32-NAMEZONE.jpg` and `1865-d32-SURVZONE.jpg`. Isolated tiles were treated as **contaminated** when they “found” names from the conflict list on the **wrong** line (e.g. Khuna on the opening `południu / Stawili się` band). Only letter sequences that recur on **more than one complete crop** of the same zone are marked STABLE.

---

## Wrong leaves (do not use as D32)

| File | What it actually is |
|---|---|
| `1865-claimed-d32-top.jpg` | Page **78**, **marriage** akt **№ 12** (not death 32). Couple in the Rozenkier / Berenhut family; February 1865; rabbi Wolf Boruchowski. |
| `1865-claimed-d32-open-enh.jpg` | Same marriage leaf. |
| `1865-claimed-d32-margin.jpg` | Left strip of that **marriage** page (vertical `1865 r.` note). A “z Khunem” reading on this strip is **not** accepted — wrong document. |
| `1865-d32-REAL-full.jpg` | Same **marriage** page **78**, akts **12 / 13**. Prior note already discarded this; confirmed again. |

The real death leaf is `1865-D32-full-page.jpg` (and the crops taken from it: `LEFT`, `RIGHT`, `BOTTOM`, `MARGIN`, `enh`, `akt32-open`, `akt32-end`, `NAMEZONE`, `SURVZONE`).

---

## Akt 31 (top) — context only

Opening and witnesses match akt 32 (same szkolnicy). Surname in the body is a **-berg** name read on the full page as **Gliksberg / Gluksberg**, female deceased, surviving **husband** named. **Not** Herszberg. Used only for letter-form comparison (same clerk, same day formula).

---

## Akt 32 (bottom) — STABLE

These sequences were seen on **at least two** independent crops of the bottom akt (`full-page`, `akt32-open`/`enh`, `NAMEZONE`, `LEFT`/`MARGIN`, and/or the `/tmp/d32x0*` line strips):

| Field | Stable letters / formula |
|---|---|
| Akt number | Left-margin **№ 32.** under **№ 31.** |
| Opening | **Działo się** … **Biał**… … **tysiąc** … **sześćdziesiąt**… **piątego** (1865). Time in the **afternoon** (`po południu`) for the *drawing-up*; death itself **z rana**. |
| Informants | **Szulim Piwo**, age in words **pięćdziesiąt sześć** (56). Second szkolnik **Silbersztejn / Zelbersztejn** (given name Judka/Zelman/Jakób — not locked), age **sześćdziesiąt cztery** (64). Both **Szkolnicy**, **w Mieście Białej zamieszkali**, **oświadczyli**. |
| Death formula | **iż w dniu dzisiejszym o godzinie dziesiątej** … **z rana** … **umarł tu w** … **Białej**. |
| Religion/sex | **Starozakonny** (Jewish male). |
| Surname | **Herszberg** — capital **H**, **ersz**, **b** with high loop, **g** with long descender. Repeats in the *zejściu* clause. |
| Given name (start) | Capital **D** immediately after **Starozakonny**. **Not** Ch/Kh. The short sequence **D-a-n** is the part that survives cross-crop; a final **a** (Dana, genitive of Dan) is the usual continuation on the full identity line. |
| Support/occupation fragment | **z handlu** and **utrzymujący się** … **w Mieście Białej zamieszkały**. |
| Parent clause type | **syn** + two given names in the genitive + (on some crops) a third feminine genitive. Masculine participles (**mający**, **utrzymujący**). |
| Age type | Age written **in words**, not digits. The long numeral-word begins with a round **o** (not **Cz-** of *czterdzieści*). Length matches **osiemdziesiąt** (eighty), not forty. |
| Closing (no children list on this leaf) | After the age participle the clerk goes to **Po przekonaniu się na- / -ocznie o zejściu** [D-name] **Herszberg**, then **Akt ten** … **świadkom przeczytany i przez tychże podpisany został.** That is the standard close when **no** *pozostawiwszy* widow/children block is inserted. |
| Signatures | **Szulim Piwo**; second szkolnik (heavy ink); **Utrzymujący Akta Stanu Cywilnego** + registrar paraph (Reymund / similar). |

**Khuna / Chuna / Huna / z Khunem:** **not named.** No stable **Ch/Kh + una/unem** sequence on the identity line, on the age/parents line, or on the closing/signature band (`SURVZONE`, `akt32-end`, `d32x03`–`d32x05`). Readings that put Khuna on the **first** NAMEZONE line contradict the stable opening **południu / Stawili się**.

---

## Akt 32 — UNSTABLE (do not publish as fact)

Conflicting prior readings vs what actually holds:

| Topic | Conflict | This pass |
|---|---|---|
| Given name | Dawid vs Dana/Dan vs Leyzor Dawid vs Chuna | **D-a-n-(a?)** is the only stable core. **Dawid** needs a terminal **d**-ascender that complete NAMEZONE/`akt32-open` crops do **not** keep under cross-check. **Leyzor** is not stable on the identity line (it is a known *other* Herszberg calling-name and was pulled in). **Chuna as deceased is rejected.** |
| Age | 42 vs 48 vs 82 (and one 88) | **Eighty** (*osiemdziesiąt*) is preferred over **forty** (*czterdzieści*). **dwa** vs **ośm** after that word is **not** locked (82 vs 88). **48** appeared on one line-strip description that also invented a widow Ita — not repeated on the full identity+close crops. |
| Parents | Jankiel×Ruchla vs Izrael×Chie vs Herszek×Chaja | **Jankla i Ruchli** is the **most repeated** genitive pair on NAMEZONE/`akt32-open`. **Herszka i Chaji** appeared only when reading the **left half** (line *starts*, not the parent slot). **Izrael×Chie** was **not** seen. **Do not publish parents.** A following **Brajny** (genitive of Brajna) is a **possible** third element, not locked. |
| Survivors | Ita Herszberg vs none vs “z Khunem” | **No stable *pozostawiwszy / wdowę / dzieci* list.** Close goes **age → Po przekonaniu**. Widow **Ita** and **z Khunem** showed up on **wrong-zone** tiles and on the **claimed marriage** files. |
| Occupation | trader/widower vs wychowawca dzieci | **z handlu** + **utrzymujący się** are stable. **Wdowiec** vs **Wyrobnik** vs **wychowawca** all start with **W** in this hand and **are not locked**. Do not use “tutor of children” as a fact. |

---

## What the akt actually says (only the locked part)

On **5 June 1865** (drawing-up), in district town **Biała**, szkolnicy **Szulim Piwo (56)** and **Silbersztejn (~64)** declared that **that morning at the tenth hour** there died in Biała a Jewish man **D. Herszberg** (given name **Dan / Dana**, not Chuna), supporting himself **from trade** in Biała, **son of** (parents **unread / unpublished**), aged **in the eighties** (prefer **osiemdziesiąt …**, not 42/48). The clerk then attests visual confirmation of the death and has the witnesses sign. **No survivor named Khuna. No stable widow Ita. No stable child list.**

**Test logic (as requested, not a conclusion):**

- If a later sharper plate ever locked the deceased as **Dawid Leyzor ~48** with widow **Ita**, the *pozostawiwszy* list would be the test of whether Khuna is a surviving son (same logic as 1860 D16). **That reading is not locked here.**
- The reading that **is** consistent with the stable letters is an elderly man **Dan ~80+** with **no survivors clause**. That can be **Dan** of the **Dan×Ester** household **as a candidate identity only**. It is **still not proof that Khuna is his son**, and this akt **does not name Khuna**.

JRI-Poland already indexes **1865 D32 HERSZBERG** with **blank given name** (`jri-herszberg-biala.csv`). That blank matches the palaeographic residual on Dana/Dan vs Dawid.

---

## 1865-idx-scan141.jpg – 148.jpg

These are **1280×800 browser screenshots** of Szukaj jednostka **167452**, scans **141–148 / 149** (index at the **end** of the combined birth/marriage/death book). They are **not** a clean 1865 death index. Several leaves are the **1862** index bound or filmed in the same unit.

| File | Year / type | Herszberg / Hirszberg / Gilszberg | D32 given name? |
|---|---|---|---|
| **141** | Header **roku 1862**. Alphabetical civil index. | **Hirszberg/Herszberg Abram 16, Leyzor 21, Sura 16** (and further H rows). | **Wrong year.** These are the **1862 marriage** numbers (JRI: Sura M16, Lejzor M21). |
| **142** | Same 1862 H-block. | Abram **16** / Leyzor **21** / Sura **16**. | **Wrong year.** |
| **143** | Heading **Akta Małżeństw** (marriage index), after a W–Z block. | Possible Herszberg/Gilszberg **marriage** rows (given names **not** stable across crops: Szymon / Samuel Hersz, etc.). **Not** Abram 16 / Leyzor 21. | **Marriage index**, not deaths. **No D32.** |
| **144** | Index table, mixed letters. | A Herszberg **Rajzla**-type row with a **low** akt number was reported; **not** locked. | **Not** a usable D32 death-index line. |
| **145** | G/H section of an index. | One crop again shows **Hirszberg Abram 16 / Leyzor 21** (1862). Another crop alleged **Gerszberg Dawid 32**. Those two cannot both be trusted on this screenshot. | **Given name for D32 not publishable** from this file. |
| **146** | Header **R. 1862. Skorowidz Małżeństw**. | **Gilszberg/Hirszberg Abram 16, Leyzor 21, Sura 16.** | **Wrong year** (1862 marriages). |
| **147** | P–Z names; one header crop read as continuation of **death** acts. | **No HERSZBERG** (H is earlier). | No D32 row. |
| **148** | W/Z (and later letters); high akt numbers (~100+). | **No Herszberg.** A **Chuna** in a **Wajnman** (or similar) row, if real, is **not** Herszberg. | No D32 row. |

**Index given name for death akt 32:** **not readable** from these saved files. Leaves **141, 142, 146** are **1862** (flag exactly as warned). The 1865 **death** H-section was **not** captured as a clean plate. JRI given name remains **blank**.

---

## Files used

- Akt: `1865-D32-full-page.jpg`, `1865-d32-NAMEZONE.jpg`, `1865-d32-SURVZONE.jpg`, `LEFT/RIGHT/BOTTOM/MARGIN.jpg`, `enh.jpg`, `akt32-open.jpg`, `akt32-end.jpg`, `1865-d32-REAL-full.jpg` (wrong), `1865-claimed-d32-*` (wrong).
- Line strips `/tmp/d32x00.jpg`–`d32x09.jpg`.
- Indexes `1865-idx-scan141.jpg`–`148.jpg`.
- Working crops: `/tmp/d32-work/` (not committed).
