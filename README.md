# Project_2
## Analysis of Head size and Brain Weight
Analyzing the relationship between head size and brain weight using data science techniques can uncover patterns and correlations that enhance our understanding of neurological development, allowing for more accurate predictive models and deeper insights into factors influencing brain physiology.

## Dataset: headbrain11.csv
["headbrain11.csv"](https://github.com/marisa-web/Project_2/blob/main/headbrain11.csv)

## EDA on a Dataset and Linear Regression results
import pandas as pd
![image](https://github.com/user-attachments/assets/4b32275d-cf4d-4343-937a-636f843a6adc)

import statsmodels.formula.api as smf
- **model = smf.ols(formula='Head_size ~ Brain_weight', data=df).fit()**
- **predicted_head_size_series = model.predict(df["Brain_weight"])**
import matplotlib.pyplot as plt
![image](https://github.com/user-attachments/assets/49b5305d-c595-4039-b749-5a7445adb49f)
#### Predicting the **Head_size** for a NEW **Brain_weight** of 3000
model.predict(pd.Series(3000, name="Brain_weight"))
#### Analysis of the HeadBrain dataset
![image](https://github.com/user-attachments/assets/ef15fa9f-625c-4199-94fa-3a5cbc6a5c20)



