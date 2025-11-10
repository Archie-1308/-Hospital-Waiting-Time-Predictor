# 🏥 Hospital Waiting Time Predictor

### by Archana Pandey  

**Goal:** Analyze hospital waiting list data to understand factors affecting patient load and predict the total number of patients in different specialties and time bands.

---

## 🧰 Tools & Libraries
- Python (Pandas, NumPy, Scikit-learn)  
- Seaborn, Matplotlib  
- Google Colab  

---

## 📂 Dataset
Dataset: [Hospital Waiting List Management Dataset – Kaggle](https://www.kaggle.com/datasets/michaelbeanie/hospital-waiting-list-management-dataset)

**Columns include:**  
- `Archive_Date` – Date of record  
- `Specialty_HIPE` – Hospital coding of specialty  
- `Speciality` – Department/department name  
- `Adult_Child` – Adult or child category  
- `Age_Profile` – Age group  
- `Time_Bands` – Time slot of appointment  
- `Total` – Total patients  

---

## 🔍 Steps Performed
1. Data Upload & Cleaning  
2. Exploratory Data Analysis (EDA)  
   - Distribution of total patients  
   - Total by specialty/department  
   - Total by adult/child category  
3. Feature Encoding (Label Encoding)  
4. Train/Test Split  
5. Linear Regression Model Training  
6. Evaluation (MAE, RMSE, R², Actual vs Predicted)  
7. Insights & Recommendations  

---

## 📊 Key Insights
- Certain specialties/departments have **much higher patient loads**, indicating bottlenecks.  
- Adult vs Child patient distribution varies across departments.  
- Time bands affect patient totals — peak times are identifiable.  
- Age profile can help predict patient load for better resource allocation.

---

## 🤖 Model Performance
- **MAE:** (Insert your MAE)  
- **RMSE:** (Insert your RMSE)  
- **R² Score:** (Insert your R² score)  

The scatter plot of Actual vs Predicted patients shows the model predicts patient totals reasonably well.

---

## 💡 Recommendations
1. Allocate staff to high-load specialties during peak time bands.  
2. Optimize appointment scheduling based on time bands.  
3. Segment services by adult/child and age profiles to improve efficiency.  
4. Use the regression model to forecast patient load and plan resources in advance.

---

## 👩‍💻 Author
**Archana Pandey** – AI & Data Science Engineering Student
