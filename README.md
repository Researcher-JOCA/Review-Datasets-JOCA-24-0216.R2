# Review-Datasets-JOCA-24-0216.R2
This repository contains the anonymized datasets used in the study "Conceptualizing the online experience: A mixed-methods analysis on the drivers of customer satisfaction" (JOCA-24-0216.R2). These files are intended solely for the use of the editorial team and reviewers during the evaluation process.

File Descriptions:
1. review_score_remove_6_na.csv (Raw Data)

Description: This dataset contains the raw sentiment scores extracted directly from the review text. Data cleaning has been applied to exclude reviews that failed to reference any of the six experiential themes (i.e., rows where all six theme scores were 'NA'). 
"NA" values denote missing data, indicating that the specific theme was not mentioned by the customer.

2. review_score_remove_6_na_imputed.csv (Imputed Data)

Description: This is the final dataset used for the path analysis and hypothesis testing. 
The missing values (NA) in the raw dataset were imputed using the Multivariate Imputation by Chained Equations (MICE) algorithm. This process preserves the statistical variance and distribution of the data, ensuring robust model estimation.

Data Privacy Note: All user and transaction identifiers in these files have been anonymized (e.g., experience_id) to protect user privacy.
