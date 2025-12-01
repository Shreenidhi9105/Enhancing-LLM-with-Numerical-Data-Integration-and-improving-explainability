#  Intrusion Detection System using Machine Learning & Explainable AI (NSL-KDD)

This project uses classical Machine Learning and Explainable AI (XAI) techniques to classify normal vs. malicious network traffic using the NSL-KDD dataset, a benchmark for network intrusion detection research.
The goal is to build a transparent, defendable model suitable for cybersecurity use-cases.

 Project Workflow
1. Load NSL-KDD Train & Test datasets  
2. Data cleaning + preprocessing  
3. Train Machine Learning models (ex: Logistic Regression, Random Forest etc.)  
4. Evaluate performance on unseen test data  
5. Apply XAI techniques (explain feature influence)

 Dataset Details
Dataset Source: NSL-KDD (Hosted on GitHub)  
Used both:
- `NSL_KDD_Train.csv`
- `NSL_KDD_Test.csv`

Dataset contains:
- 41 input features (categorical + numerical)
- 1 target class (normal / attack categories)

 Programming : Python 3.x 
 ML Libraries : scikit-learn, pandas 
 Visualization : matplotlib 
 Notebook :  Google Colab 


##  How to Run This Project

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/Shreenidhi9105/Enhancing-LLM-with-Numerical-Data-Integration-and-improving-explainability/blob/main/xai-project-final.ipynb
)


