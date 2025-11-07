# 👗 Celeste Clothing Purchase Prediction

## 📘 Project Overview
This project predicts whether an online shopper will make a purchase based on their browsing behavior.  
It uses **Machine Learning** models to analyze patterns in user sessions, pages viewed, and time spent.

---

## 🧾 Dataset Source
[Kaggle – Online Shoppers Intention Dataset](https://www.kaggle.com/datasets/henrysue/online-shoppers-intention)

The dataset contains online shopping session data such as:
- Administrative, Informational, and Product-related pages visited
- Page durations
- Bounce rate, exit rate, and page values
- Visitor type, weekend flag, and revenue (purchase or not)

---

##Tech Stack
- Python 🐍
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn for model building
- Jupyter Notebook

---

## 👤 Author
**Sunnie Singh**  
AI & Machine Learning Engineer | Passionate about Applied ML  
🔗 [LinkedIn](https://linkedin.com) | [GitHub](https://github.com/Singhsunnie12)

---

##Model Training and Results

###Data Preprocessing
Before training, the dataset was cleaned and prepared by:
- Handling missing values  
- Encoding categorical variables (e.g., VisitorType, Month)  
- Normalizing numerical features for consistent model performance  
- Splitting the dataset into training (80%) and testing (20%) sets  

###Models Used
Several classification models were trained and compared:
- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  
- XGBoost Classifier  

###Evaluation Metrics
Each model was evaluated using:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**
- **ROC-AUC Curve**

### 📊 Model Performance Summary

| Model | Accuracy | Precision | Recall | F1 Score |
|--------|-----------|------------|----------|-----------|
| Logistic Regression | 0.87 | 0.83 | 0.85 | 0.84 |
| Decision Tree | 0.90 | 0.88 | 0.89 | 0.89 |
| Random Forest | **0.93** | **0.92** | **0.91** | **0.92** |
| XGBoost | 0.92 | 0.91 | 0.90 | 0.91 |

✅ The **Random Forest Classifier** achieved the best overall performance.

---

##Visualizations
Key insights from exploratory data analysis (EDA):
- Shoppers visiting **Product-related pages** longer tend to purchase more.
- **Returning visitors** have a significantly higher purchase rate.
- **Month of visit** affects purchase likelihood (e.g., high during November–December).
- Strong negative correlation between **Bounce Rate** and **Revenue**.

---

## Future Improvements
- Tune hyperparameters for better accuracy.  
- Integrate live tracking of website sessions using APIs.  
- Deploy the model using **Streamlit** or **Flask** for real-time prediction.  

---



