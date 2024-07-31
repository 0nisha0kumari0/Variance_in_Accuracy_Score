# Variance_in_Accuracy_Score

Overview
This research investigates the accuracy variance of a Hate Speech Classification model using Logistic Regression when trained on a single dataset and tested across multiple external datasets. The primary research question examines whether such a model shows significant differences in accuracy when evaluated on diverse datasets. We conducted a comparative analysis by training the model on a specific dataset and then testing its accuracy on several distinct datasets. Additionally, we constructed a model using a combined dataset from multiple sources to enhance its accuracy.

Key Findings
Overfitting in Models 1 and 2: Visual analysis shows that Models 1 and 2 achieve high accuracy on the training dataset but fail to generalize well to other datasets, indicating overfitting.
Robust Performance of Model 3: Model 3 demonstrates good accuracy across various datasets, likely due to the diverse nature of its training data.
Consistent Accuracy of Model_C: Model_C, trained on a combined dataset from multiple sources, delivers consistently high and balanced accuracy scores, avoiding overfitting and underfitting.

Visualizations
Accuracy Comparison
Graph 1: Accuracy of Model 1 and Model 2 on the same source dataset versus other datasets.
Graph 2: Accuracy of Model 3 across different datasets.
Graph 3: Consistent accuracy of Model_C on combined datasets.

Conclusion
The study highlights the limitations of training models on a single dataset and underscores the importance of using diverse datasets for training. Model_C's performance, with its robust and stable accuracy across different datasets, demonstrates that integrating data from various sources is crucial for developing reliable and generalizable Hate Speech Classification models.

