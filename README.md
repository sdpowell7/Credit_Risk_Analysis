# Credit Risk Analysis

## Overview

Credit Risk is hard to predict because good loans outnumber risky loans. LendingClub is a peer-to-peer lending service company. They want me to look at their data and come up with a predicting model that will be accurate at it's predictions. I used 6 different models to create my predictions. The each had varying accuracy.

### Results

1. Naive Random Oversampling had an accuracy of 64.6% in it's predictions. The precision for high risk was very low at 1%. However, it's precision at low risk was 100%. The sensitivity rating was 61% for high risk and 68% for low risk.

![FBCBA1C4-2A7E-4873-B625-0934E230702A_1_201_a](https://user-images.githubusercontent.com/81715217/131272870-dfa58459-b8bd-4dfc-b758-f770dba2862a.jpeg)


2. SMOTE oversampling had an accuracy of 62.3%. The precision high risk was extremely low at 1% with low risk precision of 100%. The sensitivity rating for high risk was 61% and low risk was 64%. 

![BDD28C0C-D16A-4864-B07F-109D1C553216_4_5005_c](https://user-images.githubusercontent.com/81715217/131272951-340cca09-b2d3-46f7-84e2-82080802477b.jpeg)


3. Undersampling had an accuracy of 52.9%. The precision high risk was extremely low at 1% with low risk precision of 100%. The sensitivity rating for high risk was 61% and low risk was 45%.

![996C2562-420A-4A38-BD52-EF6F19348682_4_5005_c](https://user-images.githubusercontent.com/81715217/131273028-d049bad8-c4fe-4714-b092-1307839719d7.jpeg)

4. Using a combination of oversampling and undersampling had an accuracy of 64%. The precision high risk was extremely low at 1% with low risk precision of 100%. The sensitivity was 70% for high risk and 58% for low risk.

![A7C4B397-489C-440E-B1D9-4E9D88E9E41A_4_5005_c](https://user-images.githubusercontent.com/81715217/131273121-814426a6-8533-4639-86f0-fe0a8e00e36b.jpeg)


5. When using the Random Forest Classifier to sample, there was an accuracy of 68.3%. The precision for high risk was 88% and low risk was 100%. The sensitivity for high risk was 37% and low risk was 100%.

![653E7B0E-D150-43A2-8A74-AC43FEBE587E_4_5005_c](https://user-images.githubusercontent.com/81715217/131273238-2541bc49-bd10-462e-93b8-fbd038052a85.jpeg)


6. Easy Ensemble AdaBoost Classifier sampling had an accuracy of 93.2%. However the precision was 9% for high risk and 100% for low risk. The sensitivity rating was 92% for high risk and 94% for low risk.


### Summary

The purpose of this analysis was to find the best machine learning model to predict high and low risk loans. Most of the different analysis tools had similar results. I found that the Easy Ensemble AdaBoost classifier was the best prediction model because it's sensitivity rating for high risk, overall precision rating, and f1 score had the highest marks at 92%, 99% and 97% respectively. It also had the highest accuracy score of 93.2%. 
