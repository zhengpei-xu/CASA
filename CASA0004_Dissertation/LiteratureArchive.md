# Literature Notes
**Dissertation:** Adapting LTS to a UK Context — West Midlands Case Study
**Last updated:** 2026-03-19

---

## Index

| # | Author(s) | Year | Title | Theme | Priority | Status |
|---|-----------|------|---------------|-------|----------|--------|
| 00 |sample|sample|sample|sample|sample| `unread` |
| 01 |Jeong, P. and Smith, D|2025|Improving Infrastructure and Accessibility Indicators for  Urban Cycling Networks: Measuring the Accessibility Gap  for Safer Cycle Routes in London using Detailed  Infrastructure Data and Level of Traffic Stress|`lts-framework`|`core`| `done` |
| 02 |Mekuria et al.|2012|Low-Stress Bicycling and  Network Connectivity|`lts-framework`|`core`| `done` |

> **Theme tags:** `lts-framework` `ltn-1/20` `cycling-stress` `network-analysis` `uk-policy` `west-midlands` `intersection` `methodology`
>
> **Priority:** `core` `related` `background`
>
> **Status:** `unread` `reading` `done` `needs-revisit`

---

## Notes

---

### [00] Author(s) (Year) — Title

> **Zotero key:** `authorYYYY`
> **Themes:** `` `` ``
> **Priority:** `` | **Status:** ``

**Core argument**

<!-- What is the paper claiming? What is the main finding? 2-3 sentences max. -->

**Relevance to dissertation**

<!-- Which chapter or argument does this support, challenge, or extend?
     Be specific — link it to your framework, indicators, or case study. -->

**Limitations / Questions**

<!-- Weaknesses you noticed, or questions this paper leaves open for your work. -->

---

### [01] Jeong, P. and Smith, D (2025) — Improving Infrastructure and Accessibility Indicators for  Urban Cycling Networks: Measuring the Accessibility Gap  for Safer Cycle Routes in London using Detailed  Infrastructure Data and Level of Traffic Stress

> **Zotero key:** `jeong2025`
> **Themes:** `lts-framework`
> **Priority:** `core` | **Status:** `done`

**Core argument**

use
- cycling infrastructure 
- accessibility
to build a measurement for tracking improvement process

<!-- What is the paper claiming? What is the main finding? 2-3 sentences max. -->

**Relevance to dissertation**

- Data
    - Python "pyrosm" package
        - road classification
        - cycle infrastructure type
        - number of lanes
        - speed limits
        - POIs(destination points) (amenity/shop/toursim)
    - census data (LSOA level)
        - population
        - journey to work
    - TfL link level count data (representative sample of road types)
    - survey data (resident workplace/total communting pop/ cycling pop)
        - 2011 journey to work data
        - 2021 journey to work data
    -active lives survey data (DfT 2024) (cycling rates for all trip purposes)

- methodology
    - 1. derive cycling networks from OSM
        - pre-processing: clean wrong names
        - add "unprotected advisory cycle lanes"
        - OSM tags ->different road type
    - 2. enhance "Conveyal LTS" model
        - conveyal model 
            - step 1: make segregations based on attributions
            - step 2: the intersction LTS value is determined by most dangerous connecting crossing
        - improved model
            - based on english road type, give a basic score
            - introduce new intersection measurement (traffic lights and stop signs)
    - 3. add a preference weight based on route choice by TfL (off road/protected cycle land/...)
    - 4. use normalised score to make segreations of LTS level
    - 5. use the edge betweeness to calculate the demand flow 

**Limitations / Questions**

<!-- Weaknesses you noticed, or questions this paper leaves open for your work. -->

---
### [02] Mekuria et al. (2012) — Low-Stress Bicycling and  Network Connectivity

> **Zotero key:** `authorYYYY`
> **Themes:** `lts-framework`
> **Priority:** `core` | **Status:** `reading`

**Core argument**

<!-- What is the paper claiming? What is the main finding? 2-3 sentences max. -->

**Relevance to dissertation**

<!-- Which chapter or argument does this support, challenge, or extend?
     Be specific — link it to your framework, indicators, or case study. -->

**Limitations / Questions**

<!-- Weaknesses you noticed, or questions this paper leaves open for your work. -->

---













<!--
INSTRUCTIONS FOR ADDING A NEW ENTRY
1. Add a row to the Index table above
2. Copy the block below, paste at the bottom of the Notes section
3. Fill in all fields; delete any comment lines when done

---

### [NN] Author(s) (Year) — Title

> **Zotero key:** `authorYYYY`
> **Themes:** `` `` ``
> **Priority:** `` | **Status:** ``

**Core argument**



**Relevance to dissertation**



**Limitations / Questions**



-->
