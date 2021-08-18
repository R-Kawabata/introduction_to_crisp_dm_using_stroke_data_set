# Introduction to CRISP-DM using Stroke data set

### introduction
This is a notebook to practice the CRISP-DM process and understand how we can apply it using, as example of real data set, stroke prediction data set available on Kaggle website.

You will need to know Python programming, Statistics and Machine Learning skills to understand the CRISP-DM steps.

I hope this notebook can somehow help you to understand the CRISP-DM methodology and help you in your studies.

### Project motivation
The stroke is one of top 3 diseases causing the most deaths worldwide, according to WHO (World Health Organization). I didn't know much about it and I decided to choose the data set from Kaggle to learn more about it. Besides that, this is one of Udacity Data Science Nanodegree project.

### Libraries
The project should run with libraries included in the Anaconda distribution.
- Python 3.8.8
- Pandas 1.2.4
- Matplotlib 3.3.4
- Seaborn 0.11.1
- Numpy 1.20.1
- imblearn 0.8.0
- sklearn 0.24.1

### Files in the Repository
#### Jupyter Notebook
```introduction_to_crisp_dm_using_stroke_data_set.ipynb:``` Jupyter Notebook containing the project itself

#### Dataset directory
```healthcare-dataset-stroke-data.csv:``` CSV file containing the patient data

## Link to data set
[Kaggle Stroke Prediction Data set](https://www.kaggle.com/fedesoriano/stroke-prediction-dataset)

### Data set information
1. **id**: unique identifier
2. **gender**: "Male", "Female" or "Other"
3. **age**: age of the patient
4. **hypertension**: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
5. **heart_disease**: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
6. **ever_married**: "No" or "Yes"
7. **work_type**: "children", "Govt_job", "Never_worked", "Private" or "Self-employed"
8. **Residence_type**: "Rural" or "Urban"
9. **avg_glucose_level**: average glucose level in blood
10. **bmi**: body mass index
11. **smoking_status**: "formerly smoked", "never smoked", "smokes" or "Unknown"
12. **stroke**: 1 if the patient had a stroke or 0 if not

**Note:** *Unknown* in smoking_status means that the information is unavailable for this patient

## Results
The results can be find in my blog post [Here](https://medium.com/@raphaelkawabata/introduction-to-crisp-dm-using-one-of-most-used-data-mining-methodologies-9ce64183fc83)
