Anomaly Detection in Mobile Payment Platforms
A Comparative Study of Isolation Forest and DBSCAN

This repository contains the resources for the research thesis:
"Anomaly Detection in Mobile Payment Platforms Using Unsupervised Machine Learning".
The project investigates the performance of two anomaly detection algorithms – Isolation Forest and DBSCAN – in identifying fraudulent transactions in mobile payment systems.

-------------------------------------------------------------------------------
Repository Structure

- main branch → Contains the code for model implementation, preprocessing, and evaluation.
- master branch → Contains the dataset (synthetic + public datasets used for training and testing).

-------------------------------------------------------------------------------
Features

- Data preprocessing (cleaning, normalization, feature engineering).
- Implementation of Isolation Forest and DBSCAN in Python (Scikit-learn, NumPy, Pandas).
- Model evaluation using Precision, Recall, F1-score, ROC-AUC, Confusion Matrix, and PR curves.
- Comparative analysis highlighting the trade-offs between precision and recall.

-------------------------------------------------------------------------------
How to Use

1. Clone the repository
   git clone https://github.com/YourUsername/Mobile_Payment_Fraud.git
   cd Mobile_Payment_Fraud

2. Switch to the correct branch
   - Code:
     git checkout main
   - Dataset:
     git checkout master

3. Run the notebook / scripts
   - Open the Jupyter notebooks or Python scripts in the main branch to replicate results.
   - Use the dataset from the master branch for training and testing.

-------------------------------------------------------------------------------
Technical Environment

- Python 3.8+
- Libraries: scikit-learn, numpy, pandas, matplotlib, seaborn
- Recommended environment: Google Colab or local Jupyter Notebook.

-------------------------------------------------------------------------------
Results

- Isolation Forest: High scalability and precision, but higher false positives.
- DBSCAN: Strong recall for clustered fraud patterns, but parameter-sensitive.
- Both algorithms show complementary strengths → hybrid approaches are recommended for real-world deployment.

-------------------------------------------------------------------------------
License

This project is for academic and research purposes only. Please cite the thesis if you use this work.

-------------------------------------------------------------------------------
Contact

For queries or collaboration:
Sanjay Sathish - Sanjay.Sathish@gisma-student.com
