# NCOS-vegetation

This repository contains data, code, and outputs for a vegetation analysis of salt marsh habitat at North Campus Open Space (NCOS) in Goleta, California. The project examines which plant species dominate the restored marsh, how dominant species cover has changed across survey years (2021–2025), and how native and non-native vegetation cover have shifted over time. All analyses were conducted in R, and outputs were rendered using Quarto.

**Authors:** Macey Hartmann and Erick Morales Oyola  
**Course:** ENVS 193DD, Spring 2026, UC Santa Barbara

# Data and file information

```
ncos-vegetation/
├── data/
│   ├── veg.csv
│   │   # NCOS vegetation monitoring dataset with species identity,
│   │   # percent cover, cover category, habitat type, transect,
│   │   # survey date, and survey year
│   └── vp_veg_metadata.csv
│       # Vegetation transect metadata, including the number of quadrats
│       # sampled within each transect-year
│
├── data-exploration/
│   ├── data-exploration.qmd
│   │   # Data exploration source file with draft visualizations and
│   │   # preliminary analysis workflow
│   ├── data-exploration.pdf
│   │   # Rendered data exploration document
│   ├── ncos-saltmarsh-vegetation.qmd
│   │   # Salt marsh vegetation analysis source file
│   └── ncos-saltmarsh-vegetation.pdf
│       # Rendered salt marsh vegetation analysis
│
├── final-paper/
│   ├── final-paper.qmd
│   │   # Final paper source file with hidden but annotated R code
│   ├── final-paper.pdf
│   │   # Rendered final paper
│   └── references.bib
│       # BibTeX bibliography used to automatically generate citations
│
├── references/
│   │   # PDFs and saved reference materials used for background,
│   │   # interpretation, and citation support
│   ├── Beheshti-2023_CA-wetland-restoration.pdf
│   ├── Callaway 2004; restoration of urban salt marshes.pdf
│   ├── Ferren-1985_Carpinteria-salt-marsh.pdf
│   ├── Fitzgerald 2021; recovering ecosystem function.pdf
│   ├── Mellichamp-2023_protecting-upper-devereux-slough.pdf
│   ├── Morzaria-Luna 2004; relationship between topography and vegetation patterns.pdf
│   ├── NCOS_coastal-salt-marsh.pdf
│   ├── NCOS_planning.pdf
│   ├── NCOS-2016_restoration-plan.pdf
│   ├── NCOS-2019_year-1-monitoring-report.pdf
│   ├── NCOS-2024_year-7-monitoring-report.pdf
│   ├── Sanderson 2001; empirical model of salt marsh vegetation.pdf
│   ├── Stratton-2021_Ventura-milk-vetch.pdf
│   ├── Thomsen 2021; monitoring vegetation at a tidal marsh restoration site.pdf
│   ├── Tijuana-publications.pdf
│   ├── Wilhelm-Safian-2023_Ventura-milk-vetch-2023-report.pdf
│   └── Zedler 2004; causes and consequences of invasive plants in wetlands.pdf
│
├── timeline-check-in/
│   ├── images/
│   │   # Draft images and visual materials for the elective magazine
│   ├── references.bib
│   │   # BibTeX references for the timeline check-in
│   ├── Timeline-Check-In.qmd
│   │   # Timeline check-in source file with project background,
│   │   # draft analyses, exploratory figures, and elective planning
│   └── Timeline-Check-In.pdf
│       # Rendered timeline check-in report
│
├── ncos-vegetation.Rproj
│   # RStudio project file
│
└── README.md
    # Overview of repository purpose, files, outputs, and related repositories
```

# Rendered outputs

- [Timeline Check-In](timeline-check-in/Timeline-Check-In.pdf)
- [Final Paper](final-paper/final-paper.pdf)

# Related repositories

- [Project Proposal](https://github.com/ejmoralesoyola/project-proposal)
- [Literature Dissection](https://github.com/maceyhartmann/literature-template)
