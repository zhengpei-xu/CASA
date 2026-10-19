# CASA

For storing and archiving the materials of programme **MRes Urban Spatial Science** (UCL CASA, 2025–26).

## Modules

| Term | Module | Folder | Contents |
|------|--------|--------|----------|
| 1 | CASA0005 Geographic Information Systems and Science | [`CASA0005_Geographic-Information-Systems-and-Science`](CASA0005_Geographic-Information-Systems-and-Science) | Weekly R practicals & homework (RStudio project) |
| 1 | CASA0013 Foundations of Spatial Data Science | [`CASA0013_Foundations-of-Spatial-Data-Science`](CASA0013_Foundations-of-Spatial-Data-Science) | Python practicals & exercises |
| 2 | CASA0002 Urban Simulation | [`CASA0002_Urban-Simulation`](CASA0002_Urban-Simulation) | Lectures, readings & spatial interaction model practicals |
| 2 | CASA0006 Data Science for Spatial Systems | [`CASA0006_Data-Science-for-Spatial-Systems`](CASA0006_Data-Science-for-Spatial-Systems) | ML practicals & road safety coursework |
| 2 | CASA0011 Agent-based Modelling for Spatial Systems | [`CASA0011_Agent-based-Modelling-for-Spatial-Systems`](CASA0011_Agent-based-Modelling-for-Spatial-Systems) | Coursework 1 (Sugarscape) & Coursework 2 (taxi ABM) |
| 3 | CASA0004 Dissertation | [`CASA0004_Dissertation`](CASA0004_Dissertation) | Code, LaTeX source & project website |

## Archive conventions

```
CASA/
├── CASA00XX_Module-Name/          # one folder per module: code + full English name
│   ├── README.md                  # what the module is and how its folder is laid out
│   ├── WeekN/                     # taught weeks (practical-based modules)
│   │   ├── Lecture/               #   lecture slides
│   │   ├── Readings/              #   papers / reading list
│   │   └── Practical/<topic>/     #   notebooks or scripts + their Data/
│   └── Coursework-N_Title/        # assessed work
│       ├── Code/  Data/  Model/   #   analysis inputs
│       └── LaTeX/                 #   report source and final PDF
└── README.md                      # this index
```

- Folder names use `-` instead of spaces; files keep their original names so notebook/R paths still work.
- Data a practical reads stays next to the code that reads it (relative paths).
- OS / editor junk (`.DS_Store`, `.ipynb_checkpoints/`, `.virtual_documents/`) is ignored.
- CASA0002, CASA0005 and CASA0013 were merged in from their former standalone repositories with full commit history.
