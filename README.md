# AI/ML Project - Loan Defaulter Risk Expectany 💵🪙

<p align="center"><img src="https://user-images.githubusercontent.com/54996245/145803093-2929ae90-9b97-446d-bcd0-8daebc28b467.jpg" style="width: 1000px;"/></p>

### Description:

Banks earn a major revenue from lending loans. But it is often associated with risk. The borrower's may default on the loan. To mitigate this issue, the banks have decided to use Machine Learning to overcome this issue. They have collected past data on the loan borrowers & would like you to develop a strong ML Model to classify if any new borrower is likely to default or not.

The dataset is enormous & consists of multiple deteministic factors like borrowe's income, gender, loan pupose etc. The dataset is subject to strong multicollinearity & empty values. Can you overcome these factors & build a strong classifier to predict defaulters? 

### Acknowledgements:
This dataset has been referred from Kaggle.

### Objective:
- Understand the Dataset & cleanup (if required).
- Build classification model to predict weather the loan borrower will default or not.
- Also fine-tune the hyperparameters & compare the evaluation metrics of vaious classification algorithms.

### Stractegic Plan of Action:
**We aim to solve the problem statement by creating a plan of action, Here are some of the necessary steps:**
1. Data Exploration
2. Exploratory Data Analysis (EDA)
3. Data Pre-processing
4. Data Manipulation
5. Feature Selection/Extraction
6. Predictive Modelling
7. Project Outcomes & Conclusion

### Some Visuals of the Project:

**1. Target Variable Distribution**
  
<p align="left"><img src="https://user-images.githubusercontent.com/54996245/145803168-203d7b44-7db2-4281-8aeb-ab44c726d3ff.png" /></p>

**2. Categorical Feature-set Distribution**

![image](https://user-images.githubusercontent.com/54996245/145803215-ed2bc9ca-4fec-44dd-aff9-e7a1c745e081.png)

**3. Numerical Feature-set Distribution**

![image](https://user-images.githubusercontent.com/54996245/145803247-b6ab6724-2ba9-4e97-b3c6-681cc048d012.png)
![image](https://user-images.githubusercontent.com/54996245/145803265-80724fea-193b-435b-a3c0-54081c4a04b2.png)

**4. Relationship between the Feature-set**

<!--![image](https://user-images.githubusercontent.com/54996245/145106255-a0352942-3779-4c3f-a568-205df5480cec.png)-->

**5. Data Retention after preforming preprocessing step**

![image](https://user-images.githubusercontent.com/54996245/145803308-43fc7f22-5c99-4ded-822f-a7b84d23fdb0.png)

**6. Correlation plot for features**

![image](https://user-images.githubusercontent.com/54996245/145803326-37e8933c-9e63-42cd-9f8b-1c1ce9cb5362.png)

**7. VIF & RFE Scores & PCA Decomposition**
  
![image](https://user-images.githubusercontent.com/54996245/145803346-16589898-7c5e-4158-9cf4-a2d52bc0a010.png)
![image](https://user-images.githubusercontent.com/54996245/145803361-d3fed660-61c8-4a79-a4ee-1ce856d27b7c.png)
![image](https://user-images.githubusercontent.com/54996245/145803373-2a693229-07fc-4ba4-a8fa-5eb8a2d500c5.png)
![image](https://user-images.githubusercontent.com/54996245/145803386-02794a68-25ef-4fd1-8775-96a1ae7c4b5b.png)

**8. ROC Plots**

![image](https://user-images.githubusercontent.com/54996245/145803432-b0e7478d-ebaf-44c7-b9f5-ccdb4d329b01.png)

**9. Tree Plot & Feature Importance in Random Forest
  
![image](https://user-images.githubusercontent.com/54996245/145803457-6c75953b-be2b-43a4-9b66-f1482cf2ebb8.png)
![image](https://user-images.githubusercontent.com/54996245/145803512-b8ac3ba4-4b96-4ad3-aafd-cd6e075d0ae0.png)


**10. ML Algorithm's Scores for the Dataset**
  
![image](https://user-images.githubusercontent.com/54996245/145803557-3ec71109-2b95-4852-8187-492caaae2779.png)
![image](https://user-images.githubusercontent.com/54996245/145106489-bf55df02-ca20-4a41-858e-854bad3ac17f.png)

  
### Here are some of the key outcomes of the project:
- The Dataset was large enough summing around 1.5 lakh samples & after preprocessing 31.8% of the datasamples were dropped. 
- The samples were slightly imbalanced after processing, hence SMOTE Technique was applied on the data to  balance the classes, adding 15.5% more samples to the dataset.
- Visualising the distribution of data & their relationships, helped us to get some insights on the relationship between the feature-set.
- Feature Selection/Eliminination was carried out and appropriate features were shortlisted.
- Testing multiple algorithms with fine-tuning hyperparamters gave us some understanding on the model performance for various algorithms on this specific dataset.
- The SVM, Boosting & Random Forest Classifier performed exceptionally well on the current dataset, considering F1-score as the key-metric.
- Yet it wise to also consider simpler model like Logistic Regression as it is more generalisable & is computationally less expensive, but comes at the cost of slight misclassifications.

