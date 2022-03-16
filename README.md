<a name="BackToTop"></a>


# Attrition_and_Income_Prediction_Case_Study

**Contributors: Cameron Stewart**

>This project takes the prospective of a hypothetical consultant for the Frito-Lay Talent Management Team. As a consultant, I am tasked with two objectives:
>- Predict if specific employees are leaving due to retirement or resignation (attrition)
>- Predict monthly income of employees which can be used to better understand expected fair value
>
>For predicting attrition, I used KNN and Naive Bayes. The company's target was to reach 60% accuracy, specificity, and sensitivity.
>
>For predicting income, I used Multiple Linear Regression. The company's target was to reach a Root Mean Square Error (RMSE) of less than $3000.
>
>Linked below is the final powerpoint and presentation on YouTube.

The goal of this project was to predict employees leaving a particular company due to retirement or resignation. I first normalized, standardized, or dummy coded necessary features. Then, I used the ROSE package to create synthetic data to balance the "yes" and "no" attrition levels. My model consisted of three meta-algorithms - bagging, boosting, and stacking, which achieved an accuracy of 87.6%. Afterwards, I predicted incomes using linear regression, and explored other areas of the dataset, including the differences in incomes by gender.

The goal here was to predict monthly incomes with linear regression. I used just the quantitative variables, and to meet the assumptions, I log transformed several features, including the response variable. After the assumptions were improved, I used LASSO for variable selection. Job Level, Total Working Years, and Job Involvement were selected for the model. These achieved a .873 adjusted r-squared, or in other words, 87.3% of the variation in employee monthly incomes could be explained by these three features.


[YouTube Presentation](https://youtu.be/XJ5SvUdAJTo)

[Final Powerpoint](../main/PPT_Presentation/Final_Case_Study_Presentation.pptx)

---

## Table of Contents
- [Exploratory Data Analysis](#P1)
- [Predicting Attrition](#P2)
- [Predicting Income](#P3)
- [Conclusion](#P4)
- [References](#References)

---

<a name="P1"></a>

## Exploratory Data Analysis



[Back to Top](#BackToTop)

---

<a name="P2"></a>

## Predicting Attrition



[Back to Top](#BackToTop)

---

<a name="P3"></a>

## Predicting Income




[Back to Top](#BackToTop)

---

<a name="P4"></a>

## Conclusion



[Back to Top](#BackToTop)

---

<a name="References"></a>

## References

[YouTube Presentation](https://youtu.be/XJ5SvUdAJTo)

[Final Powerpoint](../main/PPT_Presentation/Final_Case_Study_Presentation.pptx)

[Full Markdown Analysis in R](../main/Analysis%20and%20Predictions/Case_Study.pdf)

All Raw Data and Prompt infomation in the associated folder.

##### Technologies:

R Studio

R version 4.1.2

[Back to Top](#BackToTop)

