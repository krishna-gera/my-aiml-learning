Day 4 – Models & Metrics
- Models trained: LogisticRegression, DecisionTree, RandomForest
- Train/Test split: stratified, test_size=0.2
- Best model (by F1 / ROC-AUC): RandomForest (AUC: 0.XX, F1: 0.XX)
- Observations:
  - Model X had high precision but lower recall → it misses some survivors.
  - Feature scaling (for LR) may improve performance.
  - Next step: feature engineering & hyperparameter tuning (GridSearch).
Files saved: assets/LogisticRegression_confusion.png, assets/RandomForest_roc.png, assets/results_summary.json
