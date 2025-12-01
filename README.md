#  Intrusion Detection System using Machine Learning & Explainable AI (NSL-KDD)

This project uses classical Machine Learning and Explainable AI (XAI) techniques to classify normal vs. malicious network traffic using the NSL-KDD dataset, a benchmark for network intrusion detection research.
The goal is to build a transparent, defendable model suitable for cybersecurity use-cases.

## Project Workflow
1. Load NSL-KDD Train & Test datasets  
2. Data cleaning + preprocessing  
3. Train Machine Learning models (ex: Logistic Regression, Random Forest etc.)  
4. Evaluate performance on unseen test data  
5. Apply XAI techniques (explain feature influence)

## Dataset Details
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

## Challenges

One of the most challenging problems I recently solved was building an Explainable Intrusion Detection System using machine learning on the KDD cybersecurity dataset. The dataset is highly imbalanced and contains both complex categorical and numerical network traffic features, so the first major challenge was transforming and encoding the data in a way that preserved signal for the model. I tried with multiple classical ML algorithms and tuned to improve generalization on unseen attack types. Despite achieving high accuracy, I realized the security stakeholders need to trust the system’s decisions, so I implemented XAI techniques to identify the most influential features behind predictions. This added transparency and interpretability helping end users to understand why certain traffic is flagged as malicious.


