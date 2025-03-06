# **Customer Complaint Classification**  

## **Problem Statement**  
The goal of this project is to build a model that classifies customer complaints based on their respective products or services. By automating this process, we can categorize tickets efficiently, enabling faster issue resolution.  

We will perform **topic modeling** on the provided `.json` dataset. Since the data is **unlabeled**, we will use **Non-Negative Matrix Factorization (NMF)** to identify patterns and group tickets into five key clusters:  

1. **Credit Card / Prepaid Card**  
2. **Bank Account Services**  
3. **Theft / Dispute Reporting**  
4. **Mortgages / Loans**  
5. **Others**  

Once the topics are identified, we can use this labeled data to train a **supervised learning model** (e.g., logistic regression, decision tree, naive bayes and random forest) for future complaint classification.  

---  

## **Pipeline Overview**  
To complete this project, we will perform the following steps:  

1. **Data Loading** – Read and preprocess the dataset.  
2. **Text Preprocessing** – Clean and prepare text data for analysis.  
3. **Exploratory Data Analysis (EDA)** – Identify patterns and insights from the data.  
4. **Feature Extraction** – Convert text into numerical representations.  
5. **Topic Modelling** – Use **NMF** to group complaints into predefined clusters.  
6. **Model Building (Supervised Learning)** – Train classification models.  
7. **Model Training & Evaluation** – Optimize and assess model performance.  
8. **Model Inference** – Classify new customer complaints into the correct category.  
 
