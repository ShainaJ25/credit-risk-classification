# credit-risk-classification
Module 20 Challenge

**Background**

In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

**Credit Risk Analysis Report:**

1. Provide an overview that explains the purpose of this analysis

* The purpose of this analysis was to train and evaluate the accuracy of a data model based on loan risk. The goal was to build a model that can predict the creditworthiness of borrowers. A key method used was Logisitc Regression which is a statistical method that predicts binary outcomes and evaluates input features that outputs probabilites used to classify data into two categories. 

2. Using a bulleted list, describe the accuracy, precision, and recall scores of the machine learning model

* Accuracy: The accuracy score of the model was 99%. This means that the data model correctly predicted 99% of all instances in the dataset.

* Precision: For healthy loans the precision score was 100%, while high-risk loans had a precision score of 84%. This indicates that there may be some false positives for this data model. Also, overall the average presicion score for this data model was 92%, meaning that 92% of the loans predicted as healthy or high-risk are acutally healthy or high-risk.  

* Recall: For healthy loans there was a 99% recall score and for high-risk loans there was a 94% recall score. This indicates that there were some false negatives for this data model. The overall recall average score for this data model was 97%. Having this high of an overall recall score means that 97% of the loans that were predicted by the model were succefully idenitifed as high-risk or healthy. This important for minimizing the risk of overlooking potentially problematic loans and ensuring that this data model will be useful to the company. 

3. Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning

* I would recommend this data model because this logistic regression model preforms exceptionally well in predicting healthy loans, achieving 100% precision and 99% recall scores. For high-risk loans, the model still preforms well, though there are some false positives, which is reflected in the precision score (84%) being lower than recall score (94%). Overall, the data model is highly effective in prediciting and indentifying loans, with average recall and precision scores of 97%  and 92% respectively. Given that these scores are on a 0-1 scale, the machine learning model demonstrates a strong preformance in accurately identifying both healthy and high-risk loans making it a machine learning model that would be of benefit to the company. 

**References**

Xpert Learning Assistant. (2024, December 12). Xpert Learning Assistant. https://bootcampspot.instructure.com/courses/6467/external_tools/313

