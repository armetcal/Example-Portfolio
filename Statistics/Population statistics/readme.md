# Population statistics

## AI Disclosure

**AI was used in a limited context to explain key statistical concepts. 
All AI-generated explanations were independently verified. 
No AI was used to generate code or this README file.**

## Demonstrated Skills

-  Data wrangling and formatting in R
-  Essential group comparison statistics

## Description

The scripts in this folder use X dataset, which was downloaded from kaggle.com/exact/file/path. 
The dataset is a cohort of 300 people, 100 controls and 200 with Multiple Sclerosis, 
and includes a series of other metadata including the following variables:

-  Categorical: sex, medication status (on/off)
-  Ordinal: disease severity (low/med/high)
-  Numeric: age, BMI

The difference between the MS and Control groups were assessed for each categorical variable using 
chi square tests and ordinal logistic regression for ordinal variables. 
Numeric variables with a normal distribution used a T test, and non-normal numeric variables were assessed with a Wilcoxon test.

The resulting statistics will be wrangled into a table using a format similar to the following. Numbers are denoted as the mean (95% confidence interval).
<img width="480" height="225" alt="image" src="https://github.com/user-attachments/assets/f0eb68b8-2fc4-4e74-ada9-0c9c12626168" />

