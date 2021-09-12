## Heart Disease Predcition

This repo shows the code I used for the Medium Article entitled <a href='https://medium.com/@djt20djt20/how-to-predict-heart-disease-using-data-science-78df177e816b'> How to predict heart disease (using machine learning) </a ><br />

As a man in my mid-thirties, I wanted to discover the degree to which age increases the risk of getting heart disease. I hope this might allow me to take preventative action early, if such risk exists. To this end, I seek to answer three questions:
1. How does the prevalence of heart disease vary with age?
2. Can I build a predictive model of heart disease using age as one of the variables?
3. From this model, how important a predictor is age of heart disease?

### Libraries used

pandas <br />
matplotlib<br />
seaborne<br />
sklearn<br />

### Summary of Results
I discover that heart disease is much more likely to develop in one's late forties and early fifties. But also that, in men, it can occur earlier. The model I build is around 85% accurate, and I find that the most important predictors were (in this order):
- results of the fluoroscopy
- ST depression induced by exercise
- whether one has suffered from asymptomatic chest pain
- the results of thallium stress test
- whether one is male
- one's maximum heart rate
- whether one has exercise induced angina
- results of an ECG scan

### Files in the Repo
**heart_failure_clinical_records_dataset.csv**: the raw data in a csv file.<br />
**heart_attack.ipynb**: A notebook where I perform my analysis

