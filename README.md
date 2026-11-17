## 📊 Model Performance Comparison

The following table presents the evaluation results obtained from the three Ensemble Learning models on the test dataset.

| Model | Accuracy | Precision | Recall | F1-score |
|---|---:|---:|---:|---:|
| Bagging | 97.37% | 100.00% | 92.86% | 96.30% |
| Boosting | 96.49% | 100.00% | 90.48% | 95.00% |
| Stacking | **99.12%** | **100.00%** | **97.62%** | **98.80%** |

### Key Findings

- Stacking achieved the highest Accuracy (99.12%).
- All three models achieved 100% Precision.
- Stacking achieved the highest Recall (97.62%), correctly identifying 41 out of 42 malignant cases.
- Stacking also achieved the highest F1-score (98.80%).

### Conclusion

Based on the experimental results, Stacking outperformed both Bagging and Boosting across Accuracy, Recall, and F1-score.

Combining Decision Tree, Logistic Regression, and K-Nearest Neighbors through a Logistic Regression meta-learner provided the strongest performance in this experiment.

**Note:** These results are based on a single 80/20 train-test split with a fixed random state. Further validation using stratified cross-validation is recommended to assess model stability and generalization.

data: https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic?utm_source=chatgpt.com