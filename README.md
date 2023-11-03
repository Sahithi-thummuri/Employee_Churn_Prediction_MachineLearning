# Employee Churn Prediction Using MachineLearning

<b>#FILE DESCRIPTION:</b>

1. Employee_Churn_Prediction_Report.pdf: Complete description of the project
2. Employee_Churn_Code.pdf: Execution of the project


In the ever-competitive job market, retaining existing employees is often more challenging for HR teams than recruiting new ones. The departure of valued staff members not only results in a loss of productivity but also incurs substantial costs for businesses. To tackle this issue, we adopted a machine learning approach to predict potential employee turnover, offering a proactive strategy for managing talent retention. Additionally, in the context of organizational changes and the possibility of layoffs, we explored churn modeling as an informed alternative to haphazard staff reductions. 

<b>METHODS:</b>

Utilizing a range of machine learning techniques, including Logistic Regression, K-Nearest Neighbors, Support Vector Machines, Naïve Bayes, Decision Trees, and more, our models were trained and fine-tuned using the Employee Attrition dataset sourced from Kaggle, aiming to optimize their performance. These models provide businesses with a valuable tool for enhancing employee retention strategies and making data-driven decisions during periods of organizational transition.

<b>DATA SOURCE:</b> https://www.kaggle.com/datasets/whenamancodes/hr-employee-attrition

Dimensionality Reduction:

We have reduced the dimensions to two components by using PCA as a dimension reduction approach. The most variance is captured by these two elements. The data is not completely linearly separable, as shown in the plot below.

![image](https://github.com/Sahithi-thummuri/Employee_Churn_Prediction_MachineLearning/assets/142358393/15aab455-4fbb-4069-8979-109dd15308a5)

RESULTS:

1. Accuracy:
   
   ![image](https://github.com/Sahithi-thummuri/Employee_Churn_Prediction_MachineLearning/assets/142358393/34ee2ea0-a373-4396-8cd5-4c9b146324ad)
3. Confusion matrix:
   
   ![image](https://github.com/Sahithi-thummuri/Employee_Churn_Prediction_MachineLearning/assets/142358393/de27ab14-d474-427e-9ee5-8fd76c834562)
5. Precision, Recall, F1 score, and support:
   ![image](https://github.com/Sahithi-thummuri/Employee_Churn_Prediction_MachineLearning/assets/142358393/692a90b2-7a46-444e-8eed-a155b341cc5c)
6. K-fold Cross-validation (k=10)
   ![image](https://github.com/Sahithi-thummuri/Employee_Churn_Prediction_MachineLearning/assets/142358393/f55b4593-b674-4406-9cc7-4a1549412fed)
7. ROC and AUC:
   ![image](https://github.com/Sahithi-thummuri/Employee_Churn_Prediction_MachineLearning/assets/142358393/566d697e-dd0a-4b2a-b598-cf8e3865fca3)
   
<b>From the results and comparison metrics obtained, we see that the algorithms – Logistic Regression, Random Forest, Kernel SVM and XGBoost give us the best accuracy scores of >85% even with 10-fold cross-validation.</b>





