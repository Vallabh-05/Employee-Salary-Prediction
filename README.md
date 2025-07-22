---

```markdown
# 🧑‍💼 Employee Salary Prediction

This project is a **Streamlit-based web application** that predicts employee salary levels based on various demographic and work-related features. It leverages machine learning models trained on a cleaned version of the UCI Adult dataset.

## 📂 Project Structure

```

├── app.py                  # Main Streamlit web application
├── adult 3.csv             # Original raw dataset
├── cleaned\_adult.csv       # Cleaned and preprocessed dataset
├── model.pkl               # Trained ML model (optional)
├── model\_columns.pkl       # Expected input features for prediction
├── README.md               # Project documentation

````

## 🚀 Features

- Predicts employee salary levels based on demographic and employment attributes.
- Clean and interactive UI using Streamlit.
- Real-time predictions using a pre-trained ML model.
- Encodes and handles categorical variables seamlessly.

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/employee-salary-prediction.git
   cd employee-salary-prediction
````

2. **Install dependencies**
   Ensure you have Python 3.8+ installed.

   ```bash
   pip install -r requirements.txt
   ```

   Or manually install:

   ```bash
   pip install streamlit pandas numpy scikit-learn joblib
   ```

3. **Run the Streamlit app**

   ```bash
   streamlit run app.py
   ```

## 📊 Dataset Information

* **Source**: UCI Machine Learning Repository – Adult Dataset
* **Files**:

  * `adult 3.csv`: Raw dataset
  * `cleaned_adult.csv`: Cleaned version used for model training

### Sample Features Used:

* Age
* Workclass
* Education
* Marital Status
* Occupation
* Race
* Gender
* Hours Per Week
* Native Country


## 💡 Model Overview

* Model Type: Classification (e.g., Logistic Regression, Random Forest)
* Trained using `scikit-learn`
* Encodes categorical features and scales numerical features
* Outputs salary prediction based on user input

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---
