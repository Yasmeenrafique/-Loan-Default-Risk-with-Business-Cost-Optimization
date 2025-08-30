# Loan Default Risk with Business Cost Optimization

## 📌 Objective
The goal of this project is to **predict the likelihood of loan default** and optimize the decision threshold using **cost-benefit analysis**. The main focus is not only on predictive accuracy but also on minimizing the **total business cost** associated with false positives and false negatives.

---

## 🛠️ Project flow
1. **Data Cleaning & Preprocessing**  
   - Handle missing values  
   - Encode categorical features  
   - Normalize/scale numerical features  

2. **Model Training**  
   - Logistic Regression  
   - CatBoost Classifier  

3. **Business Cost Definition**  
   - Assign different cost values for:  
     - **False Positives (FP):** Granting a loan to a customer who defaults  
     - **False Negatives (FN):** Rejecting a loan to a customer who would have repaid  

4. **Threshold Optimization**  
   - Adjust classification threshold beyond default 0.5  
   - Minimize **Total Business Cost (FP cost + FN cost)**  

5. **Model Evaluation**  
   - Confusion Matrix  
   - Feature Importance Analysis  

---

## 📌 Key Insights
- Traditional accuracy-based evaluation may not be suitable for credit risk problems.  
- By optimizing the threshold, businesses can **reduce financial losses**.  
- Feature importance helps in understanding key drivers of loan default risk.  

---

## 🚀 Tools & Technologies
- Python (Pandas, NumPy, Scikit-learn)  
- Matplotlib / Seaborn  
- SHAP for interpretability  

---

## 📖 Conclusion
This project demonstrates how machine learning can be applied to **loan default prediction** with a focus on **business-driven cost optimization**, ensuring better decision-making for financial institutions.  
