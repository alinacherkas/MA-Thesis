# MA-Thesis
Replication files for *The Effects of Migration on Attitudes towards the European Union: Extent, Dynamics and Causality*, an MA Thesis submitted to Central European University in a.y. 2019/2020. The thesis is available online via CEU Library at the [following link](https://sierra.ceu.edu/record=b1427828).

## Repository Structure

- *Source Data* - a folder with data used to create datasets for the analysis
- `1.1. Data Preparation Country.ipynb` - a **Python** notebook for reconstructing the main **country-level** dataset
- `1.2. Data Preparation Multilevel.ipynb` - a **Python** notebook for reconstructing the **multi-level** dataset that was used for robustness check.
- `2. Data Analysis.Rmd` - an **R** markdown file with the replication codes for the analysis.
- `2.-Data-Analysis.html` - knitted markdown file. Download it to explore the analysis **without using R or Python**.
- `CEU_Thesis_Data.xlsx` - an Excel file with multiple datasets, including the main **country-level** one. Running `1.1. Data Preparation Country.ipynb` re-creates this file in its entirety.

For viewing the ipython notebooks, I recommend using [nbviewer](https://nbviewer.jupyter.org)

- Click to view [1.1. Data Preparation Country.ipynb](https://nbviewer.jupyter.org/github/alinacherkas/MA-Thesis/blob/master/1.1.%20Data%20Preparation%20Country.ipynb)
- Click to view [1.2. Data Preparation Multilevel.ipynb](https://nbviewer.jupyter.org/github/alinacherkas/MA-Thesis/blob/master/1.2.%20Data%20Preparation%20Multilevel.ipynb)

## Abstract

Looking at the relationship between immigration and attitudes towards the EU, the study employs a wide range of techniques to provide a causal estimate of the direction and magnitude of the effect. Utilising shift-share instrument in panel models, the analysis consistently demonstrates that the increase in immigration flows leads to a growth in the share of people with negative attitudes towards the EU. The causal estimate shows a sizable effect of 0.3 percentage points increase in the share of people with very negative attitudes for 0.1 p.p. growth in immigrant flow. The validity of the results in ensured through a set of robustness checks which include alternative specification of the dependent and main independent variable as well as using multi-level models with more precise controls of local conditions. The study provides a robust causal estimate to support McLaren’s (2002) argument that foreigners create public misperception of the EU which gives a rise to the anti-EU sentiments. The estimated effect size reminds of the heightened sensitivity of the migration issue and the need for a coordinated efforts of EU member-states so as to prevent the spread of the anti-immigrant and anti-EU agendas.

**Key words:** migration, immigrant inflow, EU, instrumental variables, causal inference.
