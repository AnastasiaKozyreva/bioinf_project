# Biostatistics and Health Data Analysis programm final project, 2021

This repository contains study made as a final project in Biostatistics and Health Data Analysis programm. 
Here we utilized data provided by seroprevalence study of COVID-19 in Saint Petersburg, Russia.  It is a regional longitudinal cohort study aiming to evaluate the spread dynamics of the COVID-19 disease in the population of Saint Petersburg, which is provided by [European University at St. Petersburg](https://eusp.org/projects/reprezentativnoe-populyacionnoe-issledovanie-rasprostranennosti-antitel-k-sars-cov-2-v-sankt-peterburge). 
In the course of a large-scale medical and social research in St. Petersburg, conducted during the pandemic, unique data were collected related to
to social, anamnestic, household, clinical and laboratory signs. 
The data allows testing various hypotheses about the relationship between these features, as well as formulate new hypotheses. 

There are two directions in the study:  
+ Analysis of the social conditions of Saint Petersburg citizens and their relationship with
susceptibility to diseases, especially Covid-19 desease 
+ Identification of typical clinical profiles and their assessment of association with lifestyle

## Structure of repository

```

data/wave2/phone_survey -- depersonified participant-level data from the phone
                           survey in wave 2

data/wave2/test_results -- depersonified data with SARS-CoV-2 antibody test results
                           by manufacturer (A — Sugentech, B — Abbott, C — Genetico
                           Coronapass, D - VectorBest) from the second wave
data/wave2/other_tests --  depersonified data with other blood test results
                           (Vitamin D, Helicobacter pylori Immunoglobulin G,
                           Hemoglobin A0, Cholesterin, Triglycerides, etc.) from
                           wave 2
code                   --  .Rmd files with code providing respective analysis  
pictures               --  graphical data providing visualisation for analysis
 
```
## Roles
+ An assessment of [`The association of Helicobacter Pylori infection with lifestyle`](https://github.com/AnastasiaKozyreva/bioinf_project/blob/main/code/H_Pylori.Rmd) made by [*Anastasia Kozyreva*](https://github.com/AnastasiaKozyreva).
+ `Search for association of IgG (H.pylori) with lipid profile` was made by *Julia Isakova*.
+ An assessment of [`The association of lipidogram with lifestyle`](https://github.com/AnastasiaKozyreva/bioinf_project/blob/main/code/Mark_lipidom_upd.Rmd) made by [*Mark Kachanovskiy*](https://github.com/avemarkus).
+ An assessment of [`General IgE: relationships with pets kept at home`](https://github.com/AnastasiaKozyreva/bioinf_project/blob/main/code/IgE.Rmd) made by [*Kirill Usoltsev*](https://github.com/UsoltsevKirill).
+ [`Machine learning modeling in assessment of immunity against Covid-19 by serological testing `](https://github.com/AnastasiaKozyreva/bioinf_project/tree/main/code/prediction_MNA_by_IgG) made by [*Anastasiia Pulkina*](https://github.com/AnastasiiaPulkina) and [*Pavel Kulanin*](https://github.com/PavelKu78).
+ An assessment of [`Excessive use of masks as anxiety indicator`](https://github.com/AnastasiaKozyreva/bioinf_project/blob/main/code/Masks.Rmd) made by [*Fedor Logvin*](https://github.com/nshnt4evr).

