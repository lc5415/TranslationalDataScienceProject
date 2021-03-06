# Translational Data Science (TDS) Project

TDS project as part of the Master in Health Data Analytics & Machine Learning

## Project description & aims
### Data set (N~500,000) 
 - UK Biobank
 - Genetic and biochemistry data, lifestyle and socio-economic factors
 - Outcomes of interest: __cardiovascular disease__
 
### Suggested methodological approaches
 - Integrating the genetic information in a Polygenic Risk Score
 - Computing the Biological Health Score (allostatic load) from biochemistry data
 - Derive univariate/multivariate disease prediction models using (sets of) biomarkers 
 - Evaluate and compare prediction performance of the models
 - Assess their complementarity to known risk-factors
 
### Supervisors
Verena Zuber, Marc Chadeau-Hyam, Barbara Bodinier, Matt Whitaker

### Relevant papers
[M Karimi, Early-life inequalities and biological ageing: a multisystem Biological Health Score approach in Understanding Society (2019) J. Epidemiol. Community Health](https://jech.bmj.com/content/73/8/693)

## Scripts reference

Useful scripts:

* `Scripts/preprocessing.R`
* `Scripts/EDA.R`
* `Scripts/BHS.R`: Calculating BHS with multiple references
* `Scripts/LASSO_ENet.R`: Single iteration LASSO, ridge and Elastic Net
* `Scripts/PLS_models.R` Implementation of PLS and sPLS
* `Scripts/StabLasso.R`: subssampling code for lasso logistic regression 
* `Scripts/knnImputation.R`: Imputation using kNN
* `Scripts/parlMICE.R`: parallel implementation of MICE imputation
* `Scripts/univariate_analysis.R`: univariate analysis
...



