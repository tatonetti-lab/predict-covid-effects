## Supplementary tables
### table_s1_datetime_git_formatted.csv
#### visit_start_month - the count of visits (row 1), the count of patients (row 2), the count of visits that began in each month, the percent of visits that began in each month
#### non_covid_training_set - non-covid-19 set used in model training 
#### covid_training_set - covid-19 set used in model training
#### non_covid_eval_set  - non-covid-19 set used in model evaluation
#### covid_eval_set  - covid-19 set used in model evaluation
#### all_visits - all visits febraury 2020 to march 2022 with demographics data available
### table_s2_diag_formatted_git.csv	
#### metric - the count of visits (row 1), the count of patients (row 2), the count of visits with diagnosis code observed, the percent of visits with diagnosis code observed 
#### negative_training_set - non-covid-19 set used in model training
#### positive_training_set - covid-19 set used in model training
#### negative_eval_set - non-covid-19 set used in model evaluation
#### positive_eval_set - covid-19 set used in model evaluation
#### all_visits - all visits febraury 2020 to march 2022 with demographics data available
###
### table_s3_all_features.csv
#### feature - model feature being queried
#### importance - gini importance of the feature in the model
#### wasserstein_distance_training - distance between distrubtions where feature is observed and feature is not observed in the model training set
#### wasserstein_distance_eval - distance between distrubtions where feature is observed and feature is not observed in the model evaluation set
#### wasserstein_distance_all_visits - distance between distrubtions where feature is observed and feature is not observed for all visits febraury 2020 to march 2022 with demographics data available
###
### table_s4_mannwhitney_results_git_formatted.csv
#### category - category of phenotype
#### phenotype - name of phenoytpe
#### phe_code - code used to identify phenotype
#### all_X_mwu_stat - mann-whitney u test statistic for conditions irrespective of previous conditions occurring within X period
#### all_X_pvalue - mann-whitney u p-value for conditions irrespective of previous conditions occurring within X period
#### all_X_c_pvalue - mann-whitney u FDR-corrected p-value for conditions irrespective of previous conditions occurring within X period
#### new_X_mwu_stat - mann-whitney u test statistic for conditions accounting for previous conditions conditions occurring within X period
#### new_X_pvalue - mann-whitney u p-value for conditions accounting for previous conditions occurring within X period
#### new_X_c_pvalue - mann-whitney u FDR-corrected p-value for conditions accounting for previous conditions occurring within X period
###
### table_s5_coxph_results_git_formatted.csv 
#### category - category of phenotype
#### phenotype - name of phenoytpe
#### phe_code - code used to identify phenotype
#### all_1_year_case_n - coxph test number of cases for conditions irrespective of previous conditions occurring within 1 year
#### all_1_year_noncase_n - coxph test number of noncases for conditions irrespective of previous conditions occurring within 1 year
#### all_1_year_hazards ratio - coxph test hazards ratio for conditions irrespective of previous conditions occurring within 1 year
#### all_1_year_95% confidence interval (lower) - coxph test lower 95% confidence interval for conditions irrespective of previous conditions occurring within 1 year
#### all_1_year_95% confidence interval (upper) - coxph test upper 95% confidence interal for conditions irrespective of previous conditions occurring within 1 year
#### all_1_year_pvalue - coxph test pvalue for conditions irrespective of previous conditions occurring within 1 year
#### new_1_year_case_n - coxph test number of cases for conditions accounting for previous conditions occurring within 1 year
#### new_1_year_noncase_n - coxph test number of noncases for conditions accounting for previous conditions occurring within 1 year
#### new_1_year_hazards ratio - coxph test hazards ratio for conditions accounting for previous conditions occurring within 1 year
#### new_1_year_95% confidence interval (lower) - coxph test lower 95% confidence interval for conditions accounting for previous conditions occurring within 1 year
#### new_1_year_95% confidence interval (upper) - coxph test upper 95% confidence interal for conditions accounting for previous conditions occurring within 1 year
#### new_1_year_pvalue - coxph test pvalue for conditions accounting for previous conditions occurring within 1 year
###
### table_s6_multivariate_coxph.csv 
#### covariate - the specific covariate considered in the model
#### X_all_hazards ratio - coxph test hazards ratio for conditions irrespective of previous conditions occurring within 1 year for conditon X
#### X_all_95% confidence interval (lower) - coxph test lower 95% confidence interval for conditions irrespective of previous conditions occurring within 1 year for conditon X
#### X_all_95% confidence interval (upper) - coxph test upper 95% confidence interval for conditions irrespective of previous conditions occurring within 1 year for condition X
#### X_all_pvalue - coxph test pvalue for conditions irrespective of previous conditions occurring within 1 year for condition X
#### X_new_hazards ratio - coxph test hazards ratio for conditions accounting for previous conditions occurring within 1 year for condition X
#### X_new_95% confidence interval (lower) - coxph test lower 95% confidence interval for conditions accounting for previous conditions occurring within 1 year for condition X
#### X_new_95% confidence interval (upper) - coxph test upper 95% confidence interval for conditions accounting for previous conditions occurring within 1 year for condition X
#### X_new_pvalue - coxph test pvalue for conditions accounting for previous conditions occurring within 1 year for condtion X

