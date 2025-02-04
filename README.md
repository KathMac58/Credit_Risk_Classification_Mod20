# Credit_Risk_Classification_Mod20
Challenge: Module 20_ Credit Risk Classification

# Credit Analysis Report
Write a brief report that includes a summary and analysis of the performance of the machine learning models that you used in this homework. Summarize the results of the machine learning models.

A. An overview of the analysis: Explain the purpose of this analysis.
The purpose of this analysis is to use various techniques to train and evaluate a model based on loan risk. This analysis is done using a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

B. The results: Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.

> Accuracy Score: The overall correctness of the model was 99%, meaning the model was 99% correct in classifying the total number of samples (19,384).

> Precision Score (positive predicted instances per class): There were 2 classes in this model - 0 and 1.  For class 0, all predicted instances of 0 were correctly predicted. For class 1, 87% of predicted insances were correctly predicted.

> Recall Score (positive actual instances correctly predicted per class): There were 2 classes in this model - 0 and 1.  For class 0, all actual instances of 0 were correctly predicted. For class 1, 95% of actual insances were correctly identified.

C. A summary: Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.
I would recommend this model for a few reasons: 

> It was 99% accurate in predicting the creditworthiness of borrowers.

> In looking at the Precision, Recall, and F1 score, it treats both classes fairly equally which is an important consideration in model outcomes.

> Even though the model performed better on class 0 than class 1, the overall accuracy was still high, and the model handled the imbalance well
