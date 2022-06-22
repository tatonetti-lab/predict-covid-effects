# predict-covid-effects
## This repository contains certain scode for .
#
## jupyter notebooks
### 1_pull_data.ipynb
#### pull and process raw data from mysql database
### 2_number_of_features_analysis.ipynb
#### monitor performance with addition of features
### 3_number_of_trees_analysis.ipynb
#### monitor performance with increasing number of estimators
### 4_depth_analysis.ipynb
#### monitor performance with increasing maximum depth
### 6_feature_analysis_importance.ipynb
#### identify important features from final random forest model
### 7_pull_data_all_data_make_date_matrix.ipynb
#### make the datetime data matrix for all visits
### 7_pull_data_all_data_make_demog_matrix.ipynb
#### make the demographics data matrix for all visits
### 7_pull_data_all_data_make_diag_matrix.ipynb
#### make the diagnosis data matrix for all visits
### 8_applying_random_forest_model.ipynb
#### apply the optimized random forest classifer to all visits
### 10_phenotype_mann_whitney_test.ipynb
#### compare between distrubtion of COVID-19 probability of visits after which a phenotype is observed and those where the phenotype is not observed
### 11_identify_previous_conditions.ipynb
#### identify conditions that occurred before the start of the visit from our historial data and the live data
### 12_new_phenotype_mann_whitney_test.ipynb
#### compare between distrubtion of COVID-19 probability of visits after which a phenotype is observed and those where the phenotype is not observed for excluding visits for patients who previously had phenotype
### 13_hazards_analysis_all.ipynb
#### univariate cox portional hazards analysis of COVID-19 probability between visit discharge and first instance of phenotype
### 14_hazards_analysis_new.ipynb
#### univariate cox portional hazards analysis of COVID-19 probability between visit discharge and first instance of phenotype excluding visits for patients who previous had phenotype
### 15_multivariate_hazards_analysis_all.ipynb
#### multivariate cox portional hazards analysis of demographics, most frequently obserbed conditions and COVID-19 probability between visit discharge and first instance of phenotype
### 15_multivariate_hazards_analysis_new.ipynb
#### multivariate cox portional hazards analysis of demographics, most frequently obserbed conditions and COVID-19 probability between visit discharge and first instance of phenotype excluding visits for patients who previous had phenotype
