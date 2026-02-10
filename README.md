## Epitope Response Prediction
[R programming, tidymodels, SmartEDA, themis, doParalled]
Built an end-to-end pipeline to classify peptide epitopes as immune Response vs NoResponse .
•
Performed systemic EDA, removed non informative variables, grouped features by descriptor family (CTDC, CTDD, BLOSUM, SOCN, QSO, ScalesGap, AAC, etc) to assess distributions, missingness and outliers.
•
Implemented grouped train/holdout splitting on Info_group to prevent data leakage, tuned a random forest model with tidymodels, and evaluated performance before generating deployment predictions on an unseen holdout set.
