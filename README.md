## Suppleentary tables
### medrxiv_v1/supplementary_tables/table_s2_diag_formatted_git.csv	
#### metric - the count of visits (row 1), the count of patients (row 2), the count of visits with diagnosis code observed, the percent of visits with diagnosis code observed 
#### negative_training_set - non-covid-19 set used in model training
#### positive_training_set - covid-19 set used in model training
#### negative_eval_set - non-covid-19 set used in model evaluation
#### positive_eval_set - covid-19 set used in model evaluation
#### all_visits - all visits febraury 2020 to march 2022 with demographics data available
###
### medrxiv_v1/supplementary_tables/table_s3_all_features.csv
#### feature - model feature being queried
#### importance - gini importance of the feature in the model
#### wasserstein_distance_training - distance between distrubtions where feature is observed and feature is not observed in the model training set
#### wasserstein_distance_eval - distance between distrubtions where feature is observed and feature is not observed in the model evaluation set
#### wasserstein_distance_all_visits - distance between distrubtions where feature is observed and feature is not observed for all visits febraury 2020 to march 2022 with demographics data available
###
### medrxiv_v1/supplementary_tables/table_s4_mannwhitney_results_git_formatted.csv
#### category - category of phenotype
#### phenotype - name of phenoytpe
#### phe_code - code used to identify phenotype
#### "all_7_days (mwu_stat, pvalue,c_pvalue)" - mann-whitney u test statistic, p-value, and FDR-corrected p-value for conditions irrespective of previous conditions occurring within 7 days
#### "all_14_days (mwu_stat, pvalue,c_pvalue)" - mann-whitney u test statistic, p-value, and FDR-corrected p-value for conditions irrespective of previous conditions occurring within 14 days
#### "all_21_days (mwu_stat, pvalue,c_pvalue)" - mann-whitney u test statistic, p-value, and FDR-corrected p-value for conditions irrespective of previous conditions occurring within 21 days
#### "all_28_days (mwu_stat, pvalue,c_pvalue)" - mann-whitney u test statistic, p-value, and FDR-corrected p-value for conditions irrespective of previous conditions occurring within 28 days
#### "all_3_months (mwu_stat, pvalue,c_pvalue)" - mann-whitney u test statistic, p-value, and FDR-corrected p-value for conditions irrespective of previous conditions occurring within 3 months
#### "all_6_months (mwu_stat, pvalue,c_pvalue)" - mann-whitney u test statistic, p-value, and FDR-corrected p-value for conditions irrespective of previous conditions occurring within 6 months
#### "all_9_months (mwu_stat, pvalue,c_pvalue)" - mann-whitney u test statistic, p-value, and FDR-corrected p-value for conditions irrespective of previous conditions occurring within 9 months
#### "all_1_year (mwu_stat, pvalue,c_pvalue)" - mann-whitney u test statistic, p-value, and FDR-corrected p-value for conditions irrespective of previous conditions occurring within 1 year
#### "new_7_days (mwu_stat, pvalue,c_pvalue)" - mann-whitney u test statistic, p-value, and FDR-corrected p-value for conditions accounting for previous conditions occurring within 7 days
#### "new_14_days (mwu_stat, pvalue,c_pvalue)" - mann-whitney u test statistic, p-value, and FDR-corrected p-value for conditions accounting for previous conditions occurring within 14 days
#### "new_21_days (mwu_stat, pvalue,c_pvalue)" - mann-whitney u test statistic, p-value, and FDR-corrected p-value for conditions accounting for previous conditions occurring within 21 days
#### "new_28_days (mwu_stat, pvalue,c_pvalue)" - mann-whitney u test statistic, p-value, and FDR-corrected p-value for conditions accounting for previous conditions occurring within 28 days
#### "new_3_months (mwu_stat, pvalue,c_pvalue)" - mann-whitney u test statistic, p-value, and FDR-corrected p-value for conditions accounting for previous conditions occurring within 3 months
#### "new_6_months (mwu_stat, pvalue,c_pvalue)" - mann-whitney u test statistic, p-value, and FDR-corrected p-value for conditions accounting for previous conditions occurring within 6 months
#### "new_9_months (mwu_stat, pvalue,c_pvalue)" - mann-whitney u test statistic, p-value, and FDR-corrected p-value for conditions accounting for previous conditions occurring within 9 months
#### "new_1_year (mwu_stat, pvalue,c_pvalue)" - mann-whitney u test statistic, p-value, and FDR-corrected p-value for conditions accounting for previous conditions occurring within 1 year

