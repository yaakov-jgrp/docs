# US v. Daskal — Sentencing Memos

Research copies of sentencing filings from *United States v. Daskal*, E.D.N.Y. Case No. 1:21-cr-00110-NGG.

## Source

- CourtListener docket: https://www.courtlistener.com/docket/59713716/united-states-v-daskal/
- RECAP/PACER PDFs via `storage.courtlistener.com`

## File inventory

| File | Description |
|------|-------------|
| `gov-sentencing-memo-doc150.pdf` / `.txt` | Government sentencing memorandum (Doc 150) |
| `defense-sentencing-memo-doc147.pdf` / `.txt` | Defense sentencing memorandum (Doc 147) |
| `defense-exhibit-A-doc147.1.pdf` / `.txt` / `.ocr.txt` | Exhibit A (Doc 147-1) — 3 pages |
| `defense-exhibit-B-doc147.2.pdf` / `.txt` / `.ocr.txt` | Exhibit B (Doc 147-2) — 29 pages |
| `defense-exhibit-C-doc147.3.pdf` / `.txt` / `.ocr.txt` | Exhibit C (Doc 147-3) — 18 pages |

- `.txt` — text layer extracted with `pypdf`
- `.ocr.txt` — OCR via `pdftoppm` + `tesseract` (exhibits only)

## Notes

Exhibits A and B are largely scanned and/or redacted image PDFs, so OCR quality may vary (misreads, broken words, sparse pages where redactions dominate). Prefer `.ocr.txt` over the thin `pypdf` extracts for those exhibits. Exhibit C OCR is generally more usable but may still contain scan artifacts.
