# Drug-Side-Effect-Prediction
# Objective:
The aim of this project was to develop an intelligent system capable of predicting potential drug side effects before clinical trials, thereby improving drug safety and reducing pharmaceutical R&D costs.
# Description:
DeepSide is a deep learning–based predictive model designed to identify possible adverse effects of drug compounds using multi-source biomedical data. The project integrates chemical structure information, drug–target interaction data, and transcriptomic profiles to model the complex biological mechanisms that cause side effects. By combining data-driven insights with domain-specific knowledge, DeepSide helps in early identification of toxic compounds and assists in rational drug design.
# Key Features & Approach:
* Data Collection & Integration: Aggregated drug-related data from public repositories such as SIDER, DrugBank, PubChem, and LINCS.
  * Integrated molecular descriptors, gene expression signatures, and protein–drug interaction networks.
* Feature Engineering & Preprocessing: Utilized RDKit for molecular fingerprint extraction (ECFP/Morgan fingerprints).
  * Normalized and reduced high-dimensional omics data using PCA and t-SNE for efficient training.
  * Handled class imbalance using SMOTE and stratified sampling techniques.
* Model Development: Designed and trained deep neural networks (DNN) and Graph Convolutional Networks (GCN) to capture both chemical and biological patterns.
  * Implemented multi-label classification to predict multiple side effects per drug.Optimized hyperparameters using grid search and Bayesian optimization.
* Evaluation & Insights:
  * Achieved high predictive performance with ROC-AUC > 0.90 and improved recall on rare side effects.
  * Interpreted model predictions using SHAP and LIME to highlight the most influential molecular features.
  * Generated visualizations for molecular embeddings and side effect clusters to enhance interpretability.
* Technologies & Tools:
Python, TensorFlow / PyTorch, Scikit-learn, RDKit, Pandas, NumPy, Matplotlib, Seaborn, NetworkX, SHAP
# Impact:
DeepSide demonstrates how AI can accelerate drug discovery and pharmacovigilance by predicting adverse reactions with high accuracy, potentially reducing late-stage clinical trial failures and improving patient safety.
# output:

<img width="1268" height="730" alt="image" src="https://github.com/user-attachments/assets/711f57d0-f3e6-4559-90e5-6704a8abc24c" />

<img width="1190" height="679" alt="image" src="https://github.com/user-attachments/assets/81da6b76-1ea1-466c-8413-32f4473a34f0" />
