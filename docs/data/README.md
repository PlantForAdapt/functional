# All data

This folder will contains the data for all analyses.

- All raw data in `raw/`

  - Subfolder for campaign specific data : `Site_year/`
    - `osmo/` data from osmometer reading
    - `hydrated/` all fresh samples measurments (one file per date)
    - `dry_weight.csv`
    - imageJ processing `area_included_all.csv` and `area_excluded_all.csv`
  - `inventory/` for site inventory datasets
  - `geographic/` for GIS layers

- All derived data in `derived/`

  - Subfolder for campaign specific data : `Site_year/` containing all the files created by the data cleaning workflow

- All data used for correction in `corrections/`

  - Subfolder for campaign specific data : `Site_year/`
    - `scan_inspection/` for manual checking of the leaf scan
    - ...

- The listing of all data in `file_structure.txt` generated thanks to `file_structure.R`
