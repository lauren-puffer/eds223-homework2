# Exploring patterns of environmental injustice

Environmental inequities can be seen all over the world. When low income, often non-white residents disproportionately take on environmental hazards, they often experience adverse health effects and environmental degradation in their neighborhoods. This repository contains scripts wthatwere used to explore how the historic practice of redlining has influenced the environmental harms experienced by residents in Los Angeles.

In 1933, the Home Owner's Loan Corporation created maps of metropolitan areas in the United States and categorized neighborhoods by grade. The grades were: A - best, B - still desirable, C - declining, and D - hazardous. This process has become know as "redlining." We aim to see how redlining continues to impact the residents of Los Angeles based on their demographic makeup and the environmental injustices they face. We will do this using patial data of historically redlined neighborhoods and demographic and environmental hazard data from EJ Screen.

This repository also examinines the concept that biological surveys conducted by community members are more prevalent in grade A neighborhoods, than in grade D neighborhoods. To do this we will use data from the Global Biodiveristy Information Facility gathered from eBird, a community science platform for bird observations.

## Contained in this repository

```{r}
EDS223-HW2
│   README.md
│   eds_hw2_script.qmd
│   Rmd/Proj files    
│
└───.gitignore
     └───data
         └───ejscreen
         └───gbif-birds-LA
         └───mapping-inequality
```

## Data sources

All of the data housed in this repository is open-access and free to use. We extracted data from the following sources.

**EJ SCREEN**\
EPA, 2024, "Environmental Justice Mapping and Screening Tool (EJScreen)", <https://doi.org/10.7910/DVN/RLR5AX>, Harvard Dataverse, V4, UNF:6:Ew64oHBMGoTrNkLoYBJcUw== [fileUNF]

link to EJ Screen: <https://pedp-ejscreen.azurewebsites.net/>

**HOLC Red lining data**

<https://dsl.richmond.edu/panorama/redlining/data>

**Global Biodiversity Information Facility**

eBird: <https://www.gbif.org/dataset/4fa7b334-ce0d-4e88-aaae-2e0c138d049e>

## Authors

Owner of repository: Lauren Puffer

## Acknowledgements

I would like to acknowledge my professor, Annie Adams, and her Teaching Assistant, Alessandra Vidal Meza for teaching me how to do these data manipulations. I would also like to acknowledge Diego Ellis-Soto for providing the concept for this analysis.
