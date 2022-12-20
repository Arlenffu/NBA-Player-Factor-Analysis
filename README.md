# CMSE202-NBA-Player-Factor-Analysis

**Sports / Games 2: Sports related: try to analyze the value of players. Determine how to measure individual value, create a model, test on observations.**

**Packages:** 

**import matplotlib.pylab as plt #Visualizing data**

**import pandas as pd # load the dataframe**

**import seaborn as sns # Provide more advanced and concise functions, and check the correlation by sns**

**import statsmodels.api as sm # show OLS result**

**import numpy as np # get the mean and median**

**I have annotated most of the variables.**

**When running factor analysis, first you need to load the above packages, and then you need to run them in order. Because some variables are deleted in the analysis, how to run without following the steps may lead to some errors.**

**I combined the other two CSV files into nba2019.csv, so you can only focus on nba2019.csv in the file preview.**

**In factor analysis, for the first part, I loaded the data frame, then created a new column of data age. Type, and used the scatter diagram to observe its relationship with salary. Then I calculated old from the data_ The age group has a better conclusion. Finally, I deleted some useless columns and divided the data frame into five parts.**

**The second part is basically an overview and analysis of the overall data after sorting.**

**Finally, the classification of C, PG, PF, SG and SF is discussed. I get their most relevant factors respectively, and then substitute these factors into the fitting model to observe their performance and values.**
