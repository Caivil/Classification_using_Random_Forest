# 📘 drug target Classification using Random Forest and Evaluation Strategies
This notebook performs classification of Mechanism of Action (MOA) labels based on PCA-transformed gene expression data.
It uses a Random Forest Classifier and evaluates its performance through various validation strategies.

# 🔍 Key Steps:
- Load and preprocess PCA-based gene expression data.
- Clean and standardize MOA labels.
- Train a Random Forest model.
- Evaluate performance with:
  - Confusion matrix
  - Classification metrics (Accuracy, Precision, Recall, F1)
  - Bias-Variance Decomposition
  - Leave-One-Out Cross Validation (LOOCV)
  - 10-Fold Stratified Cross Validation
# ✅ Final Verdict:
The Stratified K-Fold Random Forest model achieved stable and strong performance across all metrics,
while maintaining a good balance between model bias and variance.
# 📂 Input:
- `pca_scores_ml.csv`: CSV file containing PCA scores with MOA labels.
# 📦 Dependencies:
- pandas, numpy, seaborn, matplotlib
- scikit-learn, mlxtend

