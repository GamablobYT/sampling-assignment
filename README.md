# sampling-assignment - Sahil Manchanda
## Data Sampling and Model Evaluation
Name: Sahil Manchanda<br>
Roll No. 102103134<br>
Group: 3CO5<br>

From the table we can conclude that Random Forest is the best model and if we consider 100% accuracy as overfitting then Decision Trees will be the best
Accuracy of each ML model with each sampling technique:

| Sampling Technique      | Random Forest | Logistic Regression | SVM    | Decision Trees | KNN |
|-------------------------|---------------|---------------------|--------|----------------|----------|
| Simple Random Sampling   | 0.9870        | 0.8701              | 0.8831 | 0.9610         | 0.8961   |
| Stratified Sampling      | 1.0000        | 0.9403              | 0.9701 | 1.0000         | 0.9851   |
| Systematic Sampling      | 1.0000        | 0.8926              | 0.9530 | 1.0000         | 0.9597   |
| Cluster Sampling         | 1.0000        | 0.9231              | 0.9580 | 0.9930         | 0.9720   |
| Bootstrap Sampling       | 1.0000        | 0.9200              | 0.9500 | 0.9900         | 0.9100   |




Data sampling is a crucial method employed to extract meaningful insights about a population by analyzing statistics from a representative subset, eliminating the necessity to scrutinize each individual record. In addressing an initial dataset imbalance — with 763 non-fraudulent cases and only 9 fraudulent cases — an oversampling approach was adopted. This entailed generating additional instances of the minority class (fraudulent cases) to align with the majority class (non-fraudulent cases), resulting in a well-balanced dataset consolidated into a single data frame.

Various sampling techniques were employed to create diverse subsets for analysis:

- **Simple Random Sampling:** Involves the random selection of samples from the entire population.
- **Systematic Sampling:** Selects samples at regular intervals after a random starting point.
- **Cluster Sampling:** Randomly selects entire clusters from the population.
- **Stratified Sampling:** Divides the population into subgroups based on specific criteria for sampling.
- **Bootstrap Sampling:** Resamples with replacement to generate multiple samples from the original dataset.
