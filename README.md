# 🧠 Fake Job Postings Detection

### 📘 Project Overview  
This project focuses on detecting **fraudulent job postings** using **machine learning**. It aims to help job seekers identify scam job advertisements by analyzing real-world job listing data. The notebook demonstrates a complete ML pipeline — from **data preprocessing and visualization** to **model training and evaluation** — providing insights into how AI can combat employment fraud.

---

### 🗂️ Dataset  
The dataset used is the **Fake Job Postings Dataset** (available on Kaggle).  
It includes job-related information such as:
- **Title**
- **Location**
- **Company Profile**
- **Description**
- **Requirements**
- **Employment Type**
- **Industry**
- **Fraudulent Label**

Each record is labeled as:
- `1` → Fraudulent  
- `0` → Legitimate  

---

### ⚙️ Project Workflow  

1. **Data Cleaning**
   - Removed missing, duplicate, and irrelevant records.  
   - Standardized column names and handled categorical/text data.

2. **Exploratory Data Analysis (EDA)**
   - Visualized distributions of fraudulent vs non-fraudulent jobs.  
   - Analyzed fraud rate across job titles, employment types, and industries.  
   - Identified patterns and anomalies through barplots and countplots.

3. **Feature Engineering**
   - Processed text columns (like job descriptions) using basic NLP techniques.  
   - Encoded categorical variables.  
   - Scaled numeric features where needed.

4. **Model Building**
   - Implemented a **Random Forest Classifier** for classification.  
   - To strengthen the project, additional models can be compared:
     - **Random Forest**
     - **Logistic Regression**
     - **Decision Tree**
     - **Support Vector Machine (SVM)**
     - **KNN**
     - **XGBoost**
   - Models can be evaluated using:
     - Accuracy  
     - Precision  
     - Recall  
     - F1-Score  
     - Confusion Matrix  

5. **Model Evaluation**
   - Compared results and analyzed key features influencing fraud prediction.

---

### 💡 Key Findings  
- **Full-time job posts** have the highest number of fraudulent listings.  
- Fake job posts often lack a company profile or contain vague/suspicious descriptions.  
- The **Random Forest model** provided strong performance in both accuracy and recall, making it effective for detecting fraudulent patterns.

---

### 🧩 Tech Stack  
- **Language:** Python  
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn  
- **Environment:** Jupyter Notebook  

---

### 🚀 How to Run  

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/Fake-Job-Detector.git
   cd Fake-Job-Detector

2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt

3. **Run the Notebook**
   ```bash
   jupyter notebook fake_job_detector.ipynb
