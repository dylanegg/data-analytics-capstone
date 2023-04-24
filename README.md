# Social and Economic Effects on Infant Mortality Rate

A low infant mortality rate is a sign of a healthy nation, not only physically but both socially and economically. This project looks to find the factors that contribute to infant mortality rate to discover where improvements can be made that would cause the most impact in its reduction. The data set analyzed was sourced from various government agencies, including the CDC and World Health Organization. Since this data was from disparate sources, the data was collated first before being cleaned and loaded into a final data set. The effects of Poverty Rate, Median Income, Uninsured Rate, Graduation Rate, and Violent Crime Rate on Infant mortality were analyzed using Linear Regression, Multiple Linear Regression, and Polynomial Regression. R squared and mean absolute error were used to determine the best models for each feature and all features together. While R-squared scores were low, it was observed that Poverty Rate and Median Income were factors in infant mortality rate, and the combined features could be used to predict the rate as well. 

Full report can be viewed in this repository or at https://www.overleaf.com/read/ksctdbfbwpcm

## infant_mortality_rate_combined_dataset.csv

This csv contains the raw data from combining all files from the Original Data Sources Folder. 

## data_cleaning.ipynb

Jupyter notebook containing python code used to clean infant_mortality_rate_combined_dataset.csv and output into final_dataset.csv

## Exploratory_Data_Analysis.ipynb

Jupyter notebook containing python code used to explore the cleaned data set.
Notebook references code discussed by Ken Jee in the following YouTube video: https://www.youtube.com/watch?v=QWgg4w1SpJ8

## model_buidling.ipynb

Jupyter notebook containing python code used to explore the cleaned data set.
Notebook references code discussed by Ken Jee in the following YouTube video: https://www.youtube.com/watch?v=7O4dpR9QMIM

## Predictive Analytics Outcomes.xlsx

Excel file containing mean absolute error, root mean squared error, mean squared error, and R squared for each model in model_buidling.ipynb.

## Linear Regressoin R Squared Values.twbx

Visual analysis of R Squared values from Linear Regression models in Exploratory_Data_Analysis.ipynb

## Social and Economic Effects on Infant Mortality Rate.pdf

Full report on data science project covered in this repository.

