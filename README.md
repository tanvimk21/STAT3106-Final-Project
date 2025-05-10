This final project generates seeks to generate a natural language processing model to classify 
political rhetoric in quotes from Indira Gandhi’s speeches into thematic categories such as 
nationalism, democracy, and communalism. Using a hand-curated dataset of 300+ quotes, the text 
was preprocessed and converted into a TF-IDF matrix for use in both logistic regression
and XGBoost models. While logistic regression performed better in terms of accuracy, precision,
and recall, XGBoost offered more semantically meaningful feature importance, identifying terms 
with stronger applied thematic coherence. The models were compared using cross-validation and detailed 
error analysis to understand differences in prediction behavior. The XGBoost model failed to 
perform well on the test set, highlighting challenges with generalization and the limitations 
of small, imbalanced datasets. The final version of this report is available under [FINAL-PROJECT.pdf](https://github.com/tanvimk21/STAT3106-Final-Project/blob/main/FINAL-PROJECT.pdf), and can be reproduced by knitting [Final Report.Rmd](https://github.com/tanvimk21/STAT3106-Final-Project/blob/main/FINAL%20PROJECT.Rmd)
The code for exploratory data analysis, feature engineering, and model construction and comparison
can be found under their respective .Rmd files. The data for this is only accessible by reaching
out to me as it was hand-curated by myself over the course of several months using archival materials. 
