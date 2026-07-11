# 🌊 Rising Water – AI-Based Flood Prediction System

An AI-powered web application that predicts flood risk using historical weather and rainfall data. The project uses a Machine Learning model to provide early flood predictions, helping users make informed decisions during heavy rainfall.

Live Link :  https://risingwater.streamlit.app/

Git repository : https://github.com/Yakaanil2006/Rising_Water

Video Demo : https://drive.google.com/file/d/1hJDO4q5rC3ItDBWuO5E0m2vqoS4XV95T/view?usp=sharing

---

## 📌 Features

- Predicts flood occurrence using Machine Learning
- User-friendly web interface
- Displays flood prediction and probability
- Data preprocessing using StandardScaler
- Trained Random Forest model
- Flask and Streamlit support
- Responsive design

---

## 🛠️ Tech Stack

### Frontend
- HTML5
- CSS3
- Bootstrap

### Backend
- Python
- Flask

### Machine Learning
- Scikit-learn
- Random Forest Classifier
- Pandas
- NumPy
- Joblib

### Deployment
- Render (Flask)
- Streamlit Community Cloud

---

## 📂 Project Structure

```
Rising_Water/
│
├── app.py
├── streamlit_app.py
├── requirements.txt
├── README.md
│
├── datasets/
│   ├── flood_dataset.xlsx
│   ├── X_train.csv
│   ├── X_test.csv
│   ├── y_train.csv
│   └── y_test.csv
│
├── models/
│   ├── flood_model.pkl
│   └── scaler.pkl
│
├── notebooks/
│   ├── 01_data_analysis.ipynb
│   ├── 02_preprocessing.ipynb
│   ├── 03_Model_Training.ipynb
│   └── 04_model_evaluation.ipynb
│
├── templates/
│   ├── index.html
│   └── result.html
│
└── static/
```

---

## 📊 Dataset Features

- Temperature
- Humidity
- Cloud Cover
- Annual Rainfall
- Jan-Feb Rainfall
- Mar-May Rainfall
- Jun-Sep Rainfall
- Oct-Dec Rainfall
- Average June Rainfall
- Subdivision Rainfall

Target:

- Flood (0 = No Flood, 1 = Flood)

---

## 🤖 Machine Learning Workflow

1. Load Dataset
2. Exploratory Data Analysis (EDA)
3. Data Preprocessing
4. Feature Scaling
5. Train-Test Split
6. Model Training
7. Model Evaluation
8. Save Model
9. Web Deployment

---

## 📈 Model Performance

| Model | Accuracy |
|--------|----------|
| Random Forest | **95.24%** |
| Decision Tree | 95.24% |
| CatBoost | 95.24% |
| Gradient Boosting | 95.24% |
| XGBoost | 95.24% |
| Logistic Regression | 90.48% |

**Selected Model:** Random Forest

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/Yakaanil2006/Rising-water.git
```

Go to the project directory

```bash
cd Rising_Water
```

Create a virtual environment

```bash
python -m venv env
```

Activate the environment

### Windows

```bash
env\Scripts\activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run Flask App

```bash
python app.py
```

Open:

```
http://127.0.0.1:5000
```

---

## ▶️ Run Streamlit App

```bash
streamlit run streamlit_app.py
```

---

## 🌐 Deployment

- Flask: Render
- Streamlit: Streamlit Community Cloud

---

## 📷 Application Workflow

1. Enter weather and rainfall details.
2. Click **Predict Flood**.
3. The model preprocesses the data.
4. Random Forest predicts flood risk.
5. The result and prediction probability are displayed.

---

## 🔮 Future Enhancements

- Real-time weather API integration
- SMS and Email flood alerts
- Mobile application
- Interactive GIS flood map
- User authentication
- Dashboard with historical analytics

---

## 👨‍💻 Author

**Anil Yaka**

Machine Learning Developer

GitHub: https://github.com/Yakaanil2006

---

## 📜 License

This project is developed for educational and academic purposes.
