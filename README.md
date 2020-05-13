2020\_group07: Breast cancer analysis
====================

![](./doc/supplementary_figs/00.readme_banner.png)

Description
--------------------

This is a project on a breast cancer proteomes data set, which was done as part of the DTU 22100 "R for Data Science" course. The project includes an exploratory data analysis, PCA, k-means clustering, and an Artificial Neural Network (ANN) on the data.


Data
--------------------
The data for this project contains iTRAQ proteome profiling of 77 breast cancer samples from patients. The data contains protein expression values for over 12.000 proteins for each patient, however with some missing values for the proteins that could not be quantified.

The data contains 3 tables: 
* Proteome data: proteome expression data for 77 patients and 
* Clinical data: clinical labels for patient outcomes 
* PAM50 data: information of genes/proteins significant in breast cancer diagnosis

The data is available in this repository under */data/\_raw*. 

The data was originally found on Kaggle:
<https://www.kaggle.com/piotrgrabo/breastcancerproteomes>


Dependencies
--------------------
- [R](https://cran.r-project.org/bin/windows/base/) >= 3.6.3, including packages:
  * tidyverse
  * broom
  * patchwork
  * grid
  * gridExtra
  * keras
  * miniconda
  * tensorflow


Installation
--------------------
The following code download this data analysis pipeline, when run in the terminal:

```
git clone https://github.com/rforbiodatascience/2020_group07
```

Usage
--------------------
To create the full data analysis the script *00.doit.R* found in */R* should be run. This will run all scripts and create all final plots. A presentation of the project can be found in */doc*.


Group members
--------------------

* Vlad Grigorjev (zidibot)
* Paula Rodriguez (paurrodri)  
* Rebeka Bato (rebekabato)
* Catrine Høm (catrinehom)
