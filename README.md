# CCF Volunteer List Summarizer

Single-page site. Paste the full volunteer list (copied from Excel/Sheets) or import a `.xlsx/.csv/.tsv/.txt` file and it outputs the short AM Shift (9am / 12nn) and PM Shift (3pm / 6pm) table.

## Run
Open `index.html` in a browser. No build step. Everything runs locally; nothing is uploaded.

## Notes
- Which roles appear is editable under "Rows to show".
- Open slots (e.g. Camera Director at 6 PM) are flagged with `*` and a note.
- `.xlsx` import uses SheetJS from a CDN; pasting works offline.
