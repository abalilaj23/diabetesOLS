# Diabetes Progression Predictor

## Project Overview

Diabetes is a chronic disease that alters how the body turns food into energy. Normally, food is broken down into simple sugars (glucose) and released into the bloodstream. Insulin, a hormone made by the pancreas, helps the glucose pass from the bloodstream into the cells. In diabetic patients, the pancreas can no longer make insulin or cannot adequately use the insulin it does produce. Without careful management, diabetes can lead to dangerous complications.

This **linear regression model** is used to predict disease progression one year after the baseline. The data comes from a study by **Bradley Efron, Trevor Hastie, Iain Johnstone, and Robert Tibshirani** (2004) titled "Least Angle Regression," *Annals of Statistics*. 

### Source URL:
[Least Angle Regression Study - Source](https://www4.stat.ncsu.edu/~boos/var.select/diabetes.html)

### Data URL:
[Diabetes Dataset](https://www4.stat.ncsu.edu/~boos/var.select/diabetes.tab.txt)  
(Note: The Data URL mentioned above is obtained from the source URL. The source URL provides detailed information about the dataset, variables, and reference links.)

## Dataset Information

The dataset contains **n=442 observations** and **ten baseline variables**.

### Variables:

- **age**: Age in years
- **sex**: Sex (gender)
- **bmi**: Body mass index
- **bp**: Average blood pressure
- **s1**: Total serum cholesterol (tc)
- **s2**: Low-density lipoproteins (ldl)
- **s3**: High-density lipoproteins (hdl)
- **s4**: Total cholesterol / HDL (tch)
- **s5**: Possibly log of serum triglycerides level (ltg)
- **s6**: Blood sugar level (glu)

### Dataset Characteristics:

- **Number of Instances**: 442
- **Number of Attributes**: 10 numeric predictive values
- **Target**: Column 11 is a quantitative measure of **disease progression one year after baseline** (this is the variable of interest).

## Model Overview

This linear regression model predicts how diabetes progresses based on the baseline features mentioned above. The model aims to provide insights into disease progression based on various health metrics such as BMI, cholesterol levels, blood pressure, and others.

## References

- Efron, B., Hastie, T., Johnstone, I., & Tibshirani, R. (2004). *Least Angle Regression*, *Annals of Statistics*.
