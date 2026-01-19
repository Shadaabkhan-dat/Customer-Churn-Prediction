Built a complete end-to-end machine learning pipeline, covering data preprocessing, feature engineering, model training, hyperparameter tuning, and evaluation.

Established Logistic Regression as a baseline model, achieving approximately 77% accuracy and 0.77 ROC-AUC, providing a strong and interpretable benchmark.

Evaluated multiple preprocessing strategies, including categorical encoding, feature scaling, and polynomial feature generation. Although polynomial features provided a marginal performance improvement, they significantly increased computational cost and were excluded in favor of simpler, more robust transformations.

Implemented a Random Forest Classifier, which substantially improved performance to approximately 84% accuracy and 0.81 ROC-AUC, effectively capturing non-linear relationships and feature interactions.

Prioritized ROC-AUC over accuracy as the primary evaluation metric to better assess class separation and ranking performance, especially in the presence of class imbalance.

Used cross-validation during model selection to reduce overfitting and ensure consistent generalization across unseen data.

The final solution balances predictive performance, interpretability, and computational efficiency, making it suitable for real-world customer churn prediction scenarios.
