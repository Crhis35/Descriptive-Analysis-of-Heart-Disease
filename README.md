# Anlysis for Heart Disease

***

## Dataset Information

- age : Age of the patient
- sex : Sex of the patient (0 = female; 1 = male)
- cp : Chest Pain type
- exang: exercise induced angina (1 = yes; 0 = no)
- chol : cholestoral in mg/dl fetched via BMI sensor
- trtbps : resting blood pressure (in mm Hg)
- fbs : (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
- thal:
  - 3 = normal
  - 6 = fixed defect
  - 7 = reversable defect
- rest_ecg : resting electrocardiographic results
  - Value 0: normal
  - Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
  - Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria
- thalach : maximum heart rate achieved
- target :
  - 0 = less chance of heart attack
  - 1 = more chance of heart attack
- ca: number of major vessels (0-3)
  - Value 1: typical angina
  - Value 2: atypical angina
  - Value 3: non-anginal pain
  - Value 4: asymptomatic

## Data Analysis Pipeline

***

- Data Collection
- Importing Data
- Exploring Data
- Data Cleaning
  - Handling Missing Data
  - Outlier Detection and Removal
- Exploring Data using Descriptive Statistics
  - Univariate
    - Histograms
    - Density Plot
  - Bivariate
    - Scatter Plot
    - Boxplot
  - Multivariate
    - Correlation Matrix