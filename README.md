# Breast-cancer-detection
ML classification techniques

1.	Dataset Source
https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-ML241EN-SkillsNetwork/labs/datasets/tumor.csv

2.	Introduction
The primary objective of this analysis is cancer detection using classification models. With a background in Biomedical Engineering, my curiosity led me to explore classification models on cancer data introduced in Week 2. The main goal is to develop a model that classifies tumor samples as cancerous or non-cancerous, providing valuable insights for early diagnosis and treatment.

3.	Data Engineering
The tumor dataset consists of 683 samples and 10 features, including information about clump size, nuclei detected, etc. The target variable is binary, indicating cancer (1) or benign (0). The dataset is reasonably balanced, with 65% benign tumors and 35% cancerous tumors. 8 out of the 9 features had correlations coefficients ranging from 0.6909 to 0.822 features exhibit significant correlations with the target, suggesting their importance in classification.

4.	Classifier Models
Four models were trained: Logistic Regression with l1 and l2 regularization, K-Nearest Neighbors (KNN, with neighbors= 5), Decision Tree, and Random Forests. As one can guess Random Forests gave the best test and train accuracies. Run the code included in this repository to explore the different models and their performance metrics!

Recommendation: It is considered a best practice to execute Python code within virtual environments.
