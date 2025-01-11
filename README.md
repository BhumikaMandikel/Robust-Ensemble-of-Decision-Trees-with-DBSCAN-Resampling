# Robust-Ensemble-of-Decision-Trees-with-DBSCAN-Resampling

This project demonstrates a robust ensemble of decision trees tailored for imbalanced datasets using DBSCAN-based resampling techniques. The ensemble combines models trained on the original data and resampled data, maintaining data structure while improving performance on minority classes.

## Key Highlights
- **DBSCAN Resampling**: Density-based undersampling and oversampling to handle imbalance.
- **Ensemble Learning**: Aggregates multiple decision trees for better classification.
- **Evaluation**: Tested on severely imbalanced datasets with satisfactory results:
  - **1:20 Imbalance**: 8 correct minority classifications out of 64 instances.
  - **1:10 Imbalance**: 124 correct minority classifications out of 137 instances.
## Results
While effective for moderate imbalance, extreme imbalance (1:20) shows limitations, behaving as a random classifier on the ROC curve.
---
Thank you for exploring this project!
