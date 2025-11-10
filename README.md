# Personal Loan Acceptance Prediction

## Project Objective
The goal of this project is to predict which customers are likely to accept a personal loan offer using demographic and campaign-related data. This helps banks target potential customers more efficiently, optimize marketing efforts, and increase loan acceptance rates.

## 📂 Dataset
- Source: Bank Marketing Dataset (UCI Machine Learning Repository)  
- Size: 41,188 rows × 21 columns  
- Target variable: `y` (1 = accepted, 0 = not accepted)  
- Features include age, job, marital status, education, balance, housing, loan, contact type, campaign, duration, previous outcomes, and economic indicators.

## Approach
1. **Data Understanding & Cleaning**  
   - Explored dataset structure, checked for duplicates and missing values  
   - Encoded categorical variables and scaled numerical features  
   - Split data into training (70%) and test (30%) sets  

2. **Exploratory Data Analysis (EDA)**  
   - Univariate analysis: distributions of age, job, marital status, and target variable  
   - Bivariate analysis: feature relationships with loan acceptance  
   - Visualizations: histograms, bar charts, boxplots, pie charts, correlation heatmaps  

3. **Model Training & Testing**  
   - Built **Logistic Regression** for interpretability  
   - Built **Decision Tree Classifier** for feature importance and better minority class prediction  
   - Trained models on training data and predicted on test data  

4. **Model Evaluation**  
   - Metrics: Accuracy, Confusion Matrix, Precision, Recall, F1-score  
   - Decision Tree slightly outperformed Logistic Regression in identifying accepted loans  

## 📊 Key Insights
- Only ~11% of customers accepted loans; dataset is imbalanced  
- Younger customers with higher balances are more likely to accept loans  
- Job type, marital status, and previous campaign outcomes affect loan acceptance  
- Decision Tree captures more actual “Yes” cases than Logistic Regression  
- Focus on recall and F1-score for minority class is crucial in marketing strategies  

## 📝 Conclusion
This project demonstrates a structured approach to predicting personal loan acceptance. Decision Tree Classifier is recommended for targeting potential customers, while further improvements (like handling class imbalance) could enhance performance.

## 🔗 Repository Contents
- `Personal_Loan.ipynb` → Jupyter Notebook with all steps (1–7)  
- `README.md` → Project overview, approach, results, and insights

- ## Author
- Rimsha Iram
- [Check Portfolio](https://www.datascienceportfol.io/rimshairamanalytics)
- Let’s connect on [LinkedIn](https://www.linkedin.com/in/rimsha-iram-analytics)

---

**By following this workflow, banks can effectively identify customers likely to accept personal loans, making marketing campaigns more efficient and targeted.**
