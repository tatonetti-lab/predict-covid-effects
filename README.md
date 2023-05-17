# predict-covid-effects

This repository contains certain supplementary tables and code for the project exploring the effects of COVID-19.

## Using machine learning probabilities to identify effects of COVID-19
COVID-19, the disease caused by the SARS-CoV-2 virus, has had and continues to have extensive economic, social and public health impacts in the United States and around the world. To date, there have been more than 500 million reported cases of SARS-CoV-2 infection worldwide with more than 6 million reported deaths, more than 80 million of those cases and more than 1 million of those deaths have been reported in the United States. Retrospective analysis throughout the pandemic, which identified comorbidities, risk factors and treatments, has underpinned the response COVID-19. As the situation transitions from a pandemic to an endemic, retrospective analyses using electronic health records will be increasingly important to identify long term effects of COVID-19. However, these analyses can be complicated by the incompleteness of electronic health records, which in turns makes it difficult to differentiate visits where the patient has COVID-19. To address this, we trained a random forest classifier to assign a probability of a patient having been diagnosed with COVID-19 during each visit using demographic data, temporal data and visit-specific diagnoses (Training AUROC = 0.9867, Training OOB AUROC = 0.8957, Evaluation AUROC = 0.8958). Using these probabilities, we identified conditions associated with higher COVID-19 probabilities irrespective of clinical history and when accounting for previous diagnosis and estimated the hazards ratio for myocardial infarction (Hazards ratio = 121.736 (87.375, 169.611), p = 3.796E-177 and Hazards ratio = 80.262 (4.134, 4.637), p = 4.543E-256, respectively), urinary tract infection (Hazards ratio = 72.021 (58.116 - 89.253), p < 2.225E-308 and Hazards ratio = 61.380 (51.273 - 73.479), p < 2.225E-308, respectively), acute renal failure (Hazards ratio = 1.264E4 (9.278E4 - 1.724E4), p < 2.225E-308 and Hazards ratio = 6.333E3 (4.947E3 - 8.108E3), p < 2.225E-308, respectively) and type 2 diabetes (Hazards ratio = 345.730 (283.180 - 422.098), p < 2.225E-308 and Hazards ratio = 217.271 (187.898 - 251.235), p = 1.39E-22, respectively) when accounting for demographics and the ten most common clinical conditions.


For more information on this project:

> Using machine learning probabilities to identify effects of COVID-19. <br>
Vijendra Ramlall, Benjamin May, and Nicholas P. Tatonetti <br>
_medRxiv_ (2022-07-05)  <br>
DOI: 10.1101/2022.07.02.22277179
