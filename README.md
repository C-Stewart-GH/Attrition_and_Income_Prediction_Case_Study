<a name="BackToTop"></a>


# Attrition_and_Income_Prediction_Case_Study

**Contributors: Cameron Stewart**

>This project takes the prospective of a hypothetical consultant for the Frito-Lay Talent Management Team. As a consultant, I am tasked with two objectives:
>- Predict if specific employees are leaving due to retirement or resignation (attrition)
>- Predict monthly income of employees which can be used to better understand expected fair value beyond Job Title
>
>For predicting attrition, I used KNN and Naive Bayes. The company's target was to reach 60% accuracy, specificity, and sensitivity.
>
>For predicting income, I used Multiple Linear Regression. The company's target was to reach a Root Mean Square Error (RMSE) of less than $3000.
>
>For this project, I used R to perform the analysis. Linked below is the full analysis, final powerpoint, and presentation on YouTube.

[YouTube Presentation](https://youtu.be/XJ5SvUdAJTo)

[Final Powerpoint](../main/PPT_Presentation/Final_Case_Study_Presentation.pptx)

[Full Analysis](../main/Analysis%20and%20Predictions/Case_Study.pdf)

---

## Table of Contents
- [Data Description](#P1)
- [Predicting Attrition](#P2)
- [Predicting Income](#P3)
- [Conclusion](#P4)
- [References](#References)

---

<a name="P1"></a>

## Data Description

Structure:
- 36 variables provided
- 870 observations
- No missing values identified
- Highly Imbalanced Attrition Variable (~16% left the company)
- Test Set for Attrition and Monthly Income of 300 observations

Interesting Findings:


[Back to Top](#BackToTop)

---

<a name="P2"></a>

## Predicting Attrition

<img width="550" alt="image" src="https://user-images.githubusercontent.com/37990637/158663902-a08c6def-1f1b-4222-869f-5ba12812fecc.png">

<img width="700" alt="image" src="https://user-images.githubusercontent.com/37990637/158664266-7c643ed1-1382-490e-ad0a-c3d485147eb6.png">

In the below plot, you can see we are not able to achieve a sufficient specificity with KNN to meet the company target of 60%

<img width="700" alt="image" src="https://user-images.githubusercontent.com/37990637/158664401-3ad68d09-412f-474c-a9ee-5cba4ae7640c.png">

In the below plot, you can see we reach the 60% target for accuracy, specificity, and sensitivity once the top four features are added.

<img width="700" alt="image" src="https://user-images.githubusercontent.com/37990637/158664457-ac3f6af1-b7cb-440b-90c4-5b841deaa480.png">

The final selected model is the Naive Bayes model with the top four features.

<img width="550" alt="image" src="https://user-images.githubusercontent.com/37990637/158664529-f85c3114-ad4d-4d39-8c6e-588e76e36f43.png">

[Back to Top](#BackToTop)

---

<a name="P3"></a>

## Predicting Income

<img width="550" alt="image" src="https://user-images.githubusercontent.com/37990637/158664888-c733c662-9805-4d16-98aa-5d2571c55769.png">

<img width="700" alt="image" src="https://user-images.githubusercontent.com/37990637/158664680-4d54e8f6-bab4-4f77-afee-c25f5778c4a4.png">

<img width="550" alt="image" src="https://user-images.githubusercontent.com/37990637/158665074-9b49efdd-0a98-4144-bae1-903c13c4abbd.png">

<img width="700" alt="image" src="https://user-images.githubusercontent.com/37990637/158665171-71e6e117-ae43-4cee-8d3e-03e8b60784c4.png">

<img width="700" alt="image" src="https://user-images.githubusercontent.com/37990637/158666083-827982a6-0237-49ba-8d62-66f83214c39f.png">

[Back to Top](#BackToTop)

---

<a name="P4"></a>

## Conclusion

The provided models for attrition and monthly income both exceed the company's targets. The next steps would be to follow up and validate the model on future data. Also, to set up a system to retrain the model periodically or when the underlying distribution significantly changes.

[Back to Top](#BackToTop)

---

<a name="References"></a>

## References

[YouTube Presentation](https://youtu.be/XJ5SvUdAJTo)

[Final Powerpoint](../main/PPT_Presentation/Final_Case_Study_Presentation.pptx)

[Full Analysis](../main/Analysis%20and%20Predictions/Case_Study.pdf)

All Raw Data and Prompt infomation in the associated folder.

##### Technologies:

R Studio

R version 4.1.2

[Back to Top](#BackToTop)

