# Data

## Raw Data (`data/raw/`)

Files in this folder are gitignored — do not commit raw data directly.

**Rule:** Never modify raw files. Clean in code, save output to `data/processed/`.

### Current Datasets

| File | Source | Downloaded | Rows | Notes |
|------|--------|-----------|------|-------|
| `building_permits.csv` | City of Calgary Open Data (data.calgary.ca) | 2026-02-21 | ~485,000 | 303MB — gitignored. Re-download from source if needed. |

### How to Get the Data

1. Go to [data.calgary.ca](https://data.calgary.ca)
2. Search "Building Permits"
3. Download as CSV
4. Save to `data/raw/building_permits.csv`

## Processed Data (`data/processed/`)

Cleaned and transformed versions of raw datasets. Saved by cleaning scripts.

*(empty — cleaning starts Day 3)*
