# Insight Project: SepRisk. Know your sepsis risk. Save your life. 
 
 Contained in this repository are the notebooks I created for a consulting project I undertook for Patch'd Medical.
 The project examined whether sepsis risk could be predicted from patients' vital signs, hospital diagnosis, medical history, and demographic information. 
 
 My analysis was aimed at addressing the questions Patch’d were interested in answering, namely:
 1. Can we predict sepsis risk using a machine learning model
 2. Can that model predict sepsis risk relative to time?
 3. Can the model estimate someone’s time to sepsis based on their feature values
 4. What are the relative importance of features contributing to the model
 
 The notebooks outline the pre-processing steps for importing the data, merging, cleaning and preparing the data to perform a time-to-event analyses. I analysed the data using Cox proportional hazards model, the accelerated failure-time model, Cox regression with time varying covariates, and gradient boosting Cox regression. I evaluate the models using Harrell's C concordance statistics and cumulative dependent area under the curve. 
 
 The gradient boosted Cox model showed the best overall discrimination capacity and competes with the best available published model: https://www.ncbi.nlm.nih.gov/pubmed/29286945
