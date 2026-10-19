# CASA0002 Urban Simulation

Lectures, readings and practicals from **Urban Simulation** (Term 2).

```
WeekN/
├── Lecture/     lecture slides
├── Readings/    papers for the week
└── Practical/   notebooks with their data
```

| Week | Topic | Practicals |
|------|-------|------------|
| 1 | Introduction to urban modelling; Python & linear algebra review | `Python-and-Linear-Algebra` |
| 2 | Gravity model & unconstrained spatial interaction | `Basic-Gravity-Model`, `Unconstrained-SIM` |
| 3 | Constrained spatial interaction models | `Singly-Constrained-SIM` |

## Data not stored in this repo

`Week2/Practical/Unconstrained-SIM/Data/LAD_Dec_2015_Generalised_Clipped_Boundaries_GB.geojson` (~160 MB) is not
included here. Get it either from:

- the original [zhengpei-xu/CASA0002](https://github.com/zhengpei-xu/CASA0002) repository (Git LFS: `git lfs pull`), or
- the ONS [Open Geography Portal](https://geoportal.statistics.gov.uk/) — search for
  *Local Authority Districts (December 2015) Generalised Clipped Boundaries in Great Britain* and download as GeoJSON.

Save it to `Week2/Practical/Unconstrained-SIM/Data/` with the file name above; the notebooks read it from
`./Data/`. The file is git-ignored so it won't be committed by accident.
