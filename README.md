# 📉 Customer Churn Prediction

A machine learning project to predict customer churn — which customers are likely to leave a service — using Python and scikit-learn. This project helps businesses proactively retain their customers by identifying potential churners early.

---

## 🔍 Problem Statement

Customer churn refers to when customers stop using a company's product or service. Predicting churn helps companies reduce revenue loss by focusing retention efforts on customers likely to leave.

---

## 📊 Dataset

The dataset contains various customer details such as:

- Demographics (age, gender)
- Account information (tenure, contract type)
- Service usage (internet service, phone service)
- Billing (monthly charges, total charges)
- Churn status (target variable)

> *Dataset was preprocessed and scaled before model training.*

---

## 🧰 Technologies Used

| Tool/Library | Purpose |
|--------------|---------|
| **Python** | Programming Language |
| **Pandas** | Data manipulation |
| **NumPy** | Numerical operations |
| **Matplotlib/Seaborn** | Data visualization |
| **scikit-learn** | ML models & preprocessing |
| **Google Colab** | Notebook environment |

---

## ⚙️ Project Workflow

1. **Data Cleaning** – Handled missing values, converted data types.
2. **Exploratory Data Analysis** – Visualized patterns, relationships, and class imbalance.
3. **Feature Engineering** – Label encoding and one-hot encoding.
4. **Feature Scaling** – Standardized numerical features using `StandardScaler`.
5. **Train-Test Split** – 80/20 split for training and evaluation.
6. **Model Training** – Tried multiple models (Logistic Regression, Random Forest).
7. **Model Evaluation** – Used accuracy, precision, recall, F1 score, and confusion matrix.
8. **Model Saving** – Exported the best model and scaler using `joblib`.

---

## 📈 Results

The final model achieved:

- ✅ Accuracy: ~85%  
- ✅ F1 Score: High for minority (churn) class  
- ✅ Confusion Matrix: Low false negatives (important for retention)

> You can find the trained model file as `scaler.pkl` in the repo.

---

## 🚀 How to Run the Project

1. Clone this repo or upload files to Google Colab.
2. Open `Project.ipynb` in Colab.
3. Run cells step-by-step — all instructions are embedded in the notebook.
4. Final model and scaler are saved as `.pkl` files.

---

## 💡 Future Improvements

- Try different models like XGBoost, SVM, or Neural Networks.
- Hyperparameter tuning using GridSearchCV or RandomizedSearchCV.
- Build a Streamlit web app to allow live predictions.
- Deploy model using Flask or FastAPI + Render/Heroku.

---

## 👨‍💻 Author

**Avi Walunj**  
Aspiring Data Scientist | Passionate about ML & AI  
[GitHub](https://github.com/theaviwalunj)

---

## 📝 License

This project is licensed under the Apache 2.0 License - see the `LICENSE` file for details.

