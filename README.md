1.A complete end-to-end machine learning pipeline was built, covering data preprocessing, feature engineering, model training, and evaluation.
Logistic Regression was used as a baseline model, achieving approximately 77% accuracy and 0.77 ROC-AUC, providing a strong and interpretable starting point.
3.Multiple preprocessing strategies were evaluated, including encoding, scaling, and polynomial features. While polynomial features improved performance slightly, they increased computational cost and were removed in favor of simpler, more robust transformations.
4.Random Forest Classifier significantly improved performance, achieving ~84% accuracy and ~0.81 ROC-AUC, indicating better capture of non-linear relationships and feature interactions.
5.Model evaluation focused on ROC-AUC rather than accuracy alone, ensuring better assessment of ranking and class separation, especially important for imbalanced classification problems.
6.Cross-validation was used during model selection to avoid overfitting and ensure generalization.
7.The final model balances performance, interpretability, and computational efficiency, making it suitable for real-world deployment.
