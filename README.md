# Avian Biodiversity within HOLC Grades 
__Assessment of e-bird reports within historic redlining districts__

## Background
In the 1930s, the Home Owners' Loan Corporation (HOLC) rated neighborhoods based on their perceived safety for real estate investment. This ranking system was used to block access to loans for home ownership. This practice, more commonly known as "redlining" continues to have consequences on community health and wealth. This includes environmental health, as redlined neighborhoods are less likely to have greenery, and are hotter than other neighborhoods. This analysis examines discrepancies in biodiversity observations, which tend to be lower in redlined communities. This becomes a pressing issue as citizen science data continues to be used for additional reports, which can affect restoration project planning. This analysis will use data from the United States Environmental Protection Agency in addition to avian biodiversity data to examine the distribution of citizen science contributions.

## Repository Structure
```bash
├── avian-biodiversity-holc-areas.Rproj 
├── data #data too large for GitHub, view references
│   ├── ~$EJSCREEN_2023_BG_Columns.xlsx #ejscreen column descriptions
│   ├── EJSCREEN_2023_BG_Columns.xlsx #ejscreen data
│   ├── EJSCREEN_2023_BG_StatePct_with_AS_CNMI_GU_VI.gdb
│   ├── ejscreen-tech-doc-version-2-2.pdf
│   └── gbif-birds-LA #bird observation shapefiles
│       ├── gbif-birds-LA.dbf
│       ├── gbif-birds-LA.prj
│       ├── gbif-birds-LA.shp
│       └── gbif-birds-LA.shx
├── docs
│   ├── holc-bird-survey_files
│   │   ├── figure-html #maps and plots produced
│   │   │   ├── unnamed-chunk-12-1.png
│   │   │   ├── unnamed-chunk-5-1.png
│   │   │   ├── unnamed-chunk-6-1.png
│   │   │   └── unnamed-chunk-9-1.png
│   │   └── libs #css files for qmd
│   │       ├── bootstrap
│   │       ├── clipboard
│   │       └── quarto-html
│   ├── holc-bird-survey.html
│   └── holc-bird-survey.qmd
└── README.md
```

## Data & References
Digital Scholarship Lab, Mapping Inequality [Data File] Available from: <https://dsl.richmond.edu/> Access date: December 15, 2023.

Ellis-Soto, D., Chapman, M., & Locke, D. H. (2023). Historical redlining is associated with increasing geographical disparities in bird biodiversity sampling in the United States. Nature Human Behaviour, 1-9.

Gee, G. C. (2008). A multilevel analysis of the relationship between institutional and individual racial discrimination and health status. American journal of public health, 98(Supplement_1), S48-S56.

Global Biodiversity Information Facility [Data File] Available from <https://www.gbif.org/> Access date: December 15, 2023.

Hoffman, J. S., Shandas, V., & Pendleton, N. (2020). The effects of historical housing policies on resident exposure to intra-urban heat: a study of 108 US urban areas. Climate, 8(1), 12.

Nardone, A., Rudolph, K. E., Morello-Frosch, R., & Casey, J. A. (2021). Redlines and greenspace: the relationship between historical redlining and 2010 greenspace across the United States. Environmental health perspectives, 129(1), 017006.

United States Environmental Protection Agency (2023), EJScreen: Environmental Justice Screening and Mapping Tool [Date file] Available from: <https://www.epa.gov/ejscreen/download-ejscreen-data> Access date: December 15, 2023.



