# Kaizen (IC) Card Dashboard

Interactive dashboard for the IC (Kaizen) Card data across all SBUs.

**Live:** https://mahiya98.github.io/kaizen-dashboard/

## Features
- Filters: Month / Year and SBU (each with an **All** option).
- Cards by status (count, %, bar).
- Duplicate card numbers within each sheet (counted per SBU, not combined).
- Rows with empty columns (per-row and per-field).

## Notes
- `index.html` is a single self-contained file (data embedded); it works offline.
- Regenerate the data from the source Google Sheets with the build script in the project folder, then copy the result here.
