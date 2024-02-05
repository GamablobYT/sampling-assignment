# sampling-assignment - Sahil Manchanda
## Data Sampling and Model Evaluation
Name: Sahil Manchanda<br>
Roll No. 102103134<br>
Group: 3CO5<br>

From the table we can conclude that Random Forest is the best model and if we consider 100% accuracy as overfitting then AdaBoost will be the best
Accuracy of each ML model with each sampling technique:

| Sampling Technique      | Random Forest | Logistic Regression | SVM    | Decision Trees | AdaBoost |
|-------------------------|---------------|---------------------|--------|----------------|----------|
| Simple Random Sampling   | 0.9870        | 0.8571              | 0.8831 | 0.9610         | 0.9610   |
| Stratified Sampling      | 1.0000        | 0.8806              | 0.9627 | 0.9851         | 0.9851   |
| Systematic Sampling      | 1.0000        | 0.8859              | 0.9530 | 0.9933         | 1.0000   |
| Cluster Sampling         | 0.9839        | 0.9194              | 0.9839 | 0.9355         | 0.9839   |
| Bootstrap Sampling       | 1.0000        | 0.9200              | 0.9500 | 0.9900         | 0.9900   |




Data sampling is a crucial method employed to extract meaningful insights about a population by analyzing statistics from a representative subset, eliminating the necessity to scrutinize each individual record. In addressing an initial dataset imbalance — with 763 non-fraudulent cases and only 9 fraudulent cases — an oversampling approach was adopted. This entailed generating additional instances of the minority class (fraudulent cases) to align with the majority class (non-fraudulent cases), resulting in a well-balanced dataset consolidated into a single data frame.

Various sampling techniques were employed to create diverse subsets for analysis:

- **Simple Random Sampling:** Involves the random selection of samples from the entire population.
- **Systematic Sampling:** Selects samples at regular intervals after a random starting point.
- **Cluster Sampling:** Randomly selects entire clusters from the population.
- **Stratified Sampling:** Divides the population into subgroups based on specific criteria for sampling.
- **Bootstrap Sampling:** Resamples with replacement to generate multiple samples from the original dataset.
