# Electric Vehicle Population Forecasting using Random Forest

## 📌 Overview

This project predicts the future population of Electric Vehicles (EVs) using historical EV registration data and Machine Learning. A Random Forest Regressor is trained on the dataset after preprocessing and feature engineering to forecast EV population trends.

The project demonstrates the complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), model training, evaluation, and model serialization.

---

## 🚀 Features

- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Feature engineering
- Random Forest Regression model
- Model evaluation using regression metrics
- Forecasting EV population
- Model saving using Joblib

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

---

## 📂 Project Structure

```
EV-Population-Forecasting/
│
├── Week1SourceCode.ipynb
├── Electric_Vehicle_Population_Size_History_By_County_.csv
├── preprocessed_ev_data.csv
├── forecasting_ev_model.pkl
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 📊 Dataset

**Dataset:**
Electric Vehicle Population Size History by County

The dataset contains historical records of electric vehicle population across different counties and is used to train the forecasting model.

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/EV-Population-Forecasting.git
```

Move into the project directory:

```bash
cd EV-Population-Forecasting
```

Install the required packages:

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

Open Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
Week1SourceCode.ipynb
```

Run all cells sequentially.

---

## 📈 Machine Learning Model

Algorithm Used:

- Random Forest Regressor

Evaluation metrics include:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

---

## 💾 Model Output

The trained model is saved as:

```
forecasting_ev_model.pkl
```

This model can be reused without retraining.

---

## 📌 Future Improvements

- Hyperparameter tuning
- Compare multiple regression algorithms
- Deploy the model using Flask or Streamlit
- Integrate real-time EV registration data
- Interactive dashboard for forecasting

---

## 👨‍💻 Author

**R. Balaganesh**

B.Tech Computer Science and Engineering (Artificial Intelligence & Machine Learning)

GitHub: https://github.com/Balki07

LinkedIn: https://www.linkedin.com/rbalaganesh

---

## 📄 License

This project is intended for educational and portfolio purposes.
