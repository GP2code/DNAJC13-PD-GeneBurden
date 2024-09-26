# Variants in _DNAJC13_ and their Association with Parkinson's Disease Across Different Ancestral Backgrounds

`GP2 ❤️ Open Science 😍`

Pending DOI 

**Last Updated:** September 2024 

## Summary
This is the online repository for the manuscript titled **"Variants in DNAJC13 and their Association with Parkinson's Disease Across Different Ancestral Backgrounds"**. 

The aim of this study is to explore the association between missense mutations in *DNAJC13* and Parkinson's disease (PD) in a large-scale population data derived from **Accelerating Medicines Partnership - Parkinson Disease ([AMP-PD](https://www.amp-pd.org/))** and **Global Parkinson’s Genetics Program ([GP2](https://gp2.org/))** initiatives consisting from PD cases and controls representing various ancestral groups, based on previously identified mechanisms in *DNAJC* proteins playing a role in neurodegeneration<sup>[1](https://www.tandfonline.com/doi/full/10.1080/15548627.2023.2269028)</sup>, familial and individual case reports of *DNAJC13* disease-causing variants<sup>[2,](https://academic.oup.com/brain/article/143/7/2220/5866165)</sup><sup>[3,](https://www.prd-journal.com/article/S1353-8020(18)30263-3/)</sup><sup>[4,](https://movementdisorders.onlinelibrary.wiley.com/doi/10.1002/mds.27559)</sup><sup>[5,](https://www.frontiersin.org/journals/genetics/articles/10.3389/fgene.2019.01061/full)</sup><sup>[6](https://jamanetwork.com/journals/jamaneurology/fullarticle/2685096)</sup>, and functional studies<sup>[7,](https://academic.oup.com/hmg/article/27/5/823/4788599)</sup><sup>[8,](https://linkinghub.elsevier.com/retrieve/pii/S030439401930285X)</sup><sup>[9](https://link.springer.com/article/10.1007/s00018-020-03521-y)</sup> supporting gene-disease relationship.



### Data Statement 
* All GP2 data are hosted in collaboration with the Accelerating Medicines Partnership in Parkinson's Disease (AMP-PD) and are available via application on the website. The GP2 PD case and control data are available via the GP2 website (https://gp2.org; release 7: 10.5281/zenodo.10962119). 
* All data used from the AMP-PD v3 are available via application on the website (https://www.amp-pd.org/).
* Genotyping imputation, quality control, ancestry prediction, and processing were performed using GenoTools (v1.0.0), publicly available on GitHub


### Helpful Links 
- [GP2 Website](https://gp2.org/)
    - [GP2 Cohort Dashboard](https://gp2.org/cohort-dashboard-advanced/)
- [Introduction to GP2](https://movementdisorders.onlinelibrary.wiley.com/doi/10.1002/mds.28494)
    - [Other GP2 Manuscripts (PubMed)](https://pubmed.ncbi.nlm.nih.gov/?term=%22global+parkinson%27s+genetics+program%22)


# Repository Orientation 
- The `analyses/` directory includes all analyses discussed in the manuscript

```
analyses/
├── GP2_R7/
│   ├── 01_DNAJC13_GP2_R7_AAC.ipynb
│   ├── 02_DNAJC13_GP2_R7_AFR.ipynb
│   ├── 03_DNAJC13_GP2_R7_AJ.ipynb
│   ├── 04_DNAJC13_GP2_R7_AMR.ipynb
│   ├── 05_DNAJC13_GP2_R7_CAS.ipynb
│   ├── 06_DNAJC13_GP2_R7_EAS.ipynb
│   ├── 07_DNAJC13_GP2_R7_EUR.ipynb
│   ├── 08_DNAJC13_GP2_R7_MDE.ipynb
│   └── 09_DNAJC13_GP2_R7_SAS.ipynb
└── AMP_PD_R3/
    ├── 01_DNAJC13_AMP_PD_R3_EUR.ipynb
    └── 02_DNAJC13_AMP_PD_R3_AJ.ipynb
```

---
### Analysis Notebooks
* Languages: Python, bash, and R

| Directory  | Notebooks                | Description                                                                       |
|------------|--------------------------|-----------------------------------------------------------------------------------|
| GP2_R7/    | 01_DNAJC13_GP2_R7_AAC    | Full pipeline (subset, annotate, association, gene burden) for GP2 AAC dataset    |
|            | 02_DNAJC13_GP2_R7_AFR    | Full pipeline (subset, annotate, association, gene burden) for GP2 AFR dataset    |
|            | 03_DNAJC13_GP2_R7_AJ     | Full pipeline (subset, annotate, association, gene burden) for GP2 AJ dataset     |
|            | 04_DNAJC13_GP2_R7_AMR    | Full pipeline (subset, annotate, association, gene burden) for GP2 AMR dataset    |
|            | 05_DNAJC13_GP2_R7_CAS    | Full pipeline (subset, annotate, association, gene burden) for GP2 CAS dataset    |
|            | 06_DNAJC13_GP2_R7_EAS    | Full pipeline (subset, annotate, association, gene burden) for GP2 EAS dataset    |
|            | 07_DNAJC13_GP2_R7_EUR    | Full pipeline (subset, annotate, association, gene burden) for GP2 EUR dataset    |
|            | 08_DNAJC13_GP2_R7_MDE    | Full pipeline (subset, annotate, association, gene burden) for GP2 MDE dataset    |
|            | 09_DNAJC13_GP2_R7_SAS    | Full pipeline (subset, annotate, association, gene burden) for GP2 SAS dataset    |
| AMP_PD_R3/ | 01_DNAJC13_AMP_PD_R3_EUR | Full pipeline (subset, annotate, association, gene burden) for AMP-PD EUR dataset |
|            | 02_DNAJC13_AMP_PD_R3_AJ  | Full pipeline (subset, annotate, association, gene burden) for AMP-PD AJ dataset  |

## Ancestry labels
|**Abbreviation**   |      **Ancestry**            |
|:-----------------:|:----------------------------:|
|       AAC         |African American|
|       AFR         |African|
|       AJ          |Ashkenazi Jews|
|       AMR         |Admixed American/Latin American|
|       CAS         |Central Asian|
|       EAS         |East Asian|
|       EUR         |European|
|       MDE         |Middle Eastern|
|       SAS         |South Asian|

---

# Software 
|               Software              |  Version(s) |                              Resource URL                              |       RRID      |                                               Notes                                               |   |
|:-----------------------------------:|:-----------:|:----------------------------------------------------------------------:|:---------------:|:-------------------------------------------------------------------------------------------------:|:-:|
|     Python Programming Language     | 3.8 and 3.9 |                         http://www.python.org/                         | RRID:SCR_008394 | pandas; numpy; seaborn; matplotlib; statsmodel; used for general data wrangling/plotting/analyses |   |
| R Project for Statistical Computing |     4.2     |                        http://www.r-project.org/                       | RRID:SCR_001905 |   tidyverse; dplyr; tidyr; ggplot; data.table; used for general data wrangling/plotting/analyses  |   |
|                PLINK                |     2.0 and 1.9    |                   http://www.nitrc.org/projects/plink                  | RRID:SCR_001757 |                                     used for genetic analyses                                     |   |
| ANNOVAR | 2020-06-08 | http://www.openbioinformatics.org/annovar/	| RRID:SCR_012821 | Genetic annotation software |
RVTests | v2.1.0 | http://genome.sph.umich.edu/wiki/RvTests | RRID:SCR_007639 | Burden analyses
