# Predicting Heart Disease in Patients with Angina

This repository is for the analysis and modeling done with the UCI heart disease dataset.

### Project Outcome
Doctors diagnosing heart attacks (i.e., angina caused by heart disease) has a [misdiagnosis rate of 33%](https://www.bbc.com/news/health-37215768). This translates to a recall score of 66% (or correctly diagnosing 66% of patients that have heart disease with heart disease). Moreover, the [accuracy of doctors diagnosing heart disease in all patients is 83%](https://www.bbc.com/news/health-42357257). Using these as recall and accuracy thresholds to be above, the final model was evaluated on a test set and correctly predicted all heart disease cases and had an accuracy of 90%. I productionized this model onto [Heroku](https://hdp-site.herokuapp.com/) to help doctors with diagnosing heart attack patients. The Flask files are viewable at [this repo](https://github.com/MichaelABryant/hdp-flask).

### Code Used 

**Python Version:** 3.9.12 <br />
**Packages:** pandas, numpy, matplotlib, seaborn, sklearn, xgboost, tqdm<br />
**For Web Framework Requirements:**  ```pip install -r requirements.txt```  
