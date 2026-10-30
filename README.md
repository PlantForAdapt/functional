# Functional

**functional** is a small project to help organise functional data acquisition in the PlantForAdapt project.

## Project

**functional** includes:

- Presentation of the projects and analyses with associated documentation and figures:
  - Reproductive analyses in `files.qmd`
  - Resulting pages in `docs/`
  - Document structure definition in `_quarto.yml`
- Documents (protocols, maps, field sheets) in `documents/`
- Data in `data/` with:
  - All raw data in `raw/`
    - Campaign specific data in `Site_year/`
  - All derived data in `derived/`
    - Campaign specific data in `Site_year/`
| Outputs in `outputs` with campaign specific outputs prefixed by `Site_year_`
- R environment definition with [renv](https://rstudio.github.io/renv/articles/renv.html) in `renv/` and `renv/lock`
- R files (`.Rbuildignore` , `.Rdata` , `.Rprofile` , `.Rhistory`)
- Git and GitHub files (`.gitignore` , `.github/`)
- Project documentation (`README.qmd` , `README.md` , `NEWS.md` , `LICENSE`)

## People

- Sylvain Schmitt (sylvain.schmitt\@cirad.fr)
- Géraldine Derroire (geraldine.derroire\@cirad.fr)
- Joannès Guillemot (joannes.guillemot\@cirad.fr)
- Lucas Mazzei de Freitas (lucas.mazzei\@embrapa.br)
