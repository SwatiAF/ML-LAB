# ML-LAB
ML 

measuring metrics:

1. precision: metric used to evaluate the performance of a classification model. Precision values range from 0 to 1

`Precision = True Positives / (True Positives + False Positives)`

Precision provides an indication of the model's ability to correctly identify positive instances and avoid false positive predictions. 

2. accuracy: metric to evaluate the performance of a classification model.

`Accuracy = (True Positives + True Negatives) / (True Positives + True Negatives + False Positives + False Negatives)`

Accuracy provides an overall measure of how well the model performs across all classes. It considers both positive and negative predictions and provides an indication of the model's ability to correctly classify instances from the entire dataset.

3. recall: Recall, also known as sensitivity or true positive rate, is a metric used to evaluate the performance of a classification model

`Recall = True Positives / (True Positives + False Negatives)`

focuses on the model's ability to identify positive instances correctly, considering the actual distribution of positive instances in the dataset

4. F1-score: metric used to evaluate the performance of a classification model

`F1-score = 2 * (Precision * Recall) / (Precision + Recall)`

F1-score combines precision and recall into a single value, providing a balanced assessment of the model's performance. It is particularly useful when there is an imbalance in the dataset, as it considers both false positives and false negatives.

5. A confusion matrix is a table that visualizes the performance of a classification model by comparing the predicted labels with the actual labels of a dataset. It provides a detailed breakdown of the model's predictions, showing the true positive (TP), true negative (TN), false positive (FP), and false negative (FN) values. The confusion matrix is commonly used in evaluating binary classification tasks but can also be extended to multi-class classification problems.

![image](https://github.com/SwatiAF/ML-LAB/assets/83855603/b6afba03-1843-4120-9b73-9a5d53cdb353)

The confusion matrix helps evaluate the model's performance by providing insights into its ability to make correct predictions across different classes. From the confusion matrix, various evaluation metrics can be derived, including accuracy, precision, recall, and F1-score, which can further assess the model's performance.




