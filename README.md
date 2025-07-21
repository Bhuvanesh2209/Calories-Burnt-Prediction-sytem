# Calories-Burnt-Prediction-sytem
A machine learning-based system that predicts the number of calories burnt during physical activities using personal and physiological data.

📊 Features
Predicts calories burnt using attributes like age, gender, height, weight, duration, and heart rate.

Implements regression models (Linear Regression, Random Forest, XGBoost, etc.).

Includes EDA, preprocessing, and model evaluation.

Supports real-time or batch input predictions.

🧠 Tech Stack
Python, Pandas, NumPy, Matplotlib, Seaborn

Scikit-learn, XGBoost, Streamlit (for GUI, optional)

📁 Dataset
Based on public datasets from Kaggle and UCI repositories.

Includes features such as:

Gender, Age, Height, Weight, Duration, Heart Rate, Body Temperature

📈 Model Performance
Achieved R² score ~0.96 with Random Forest Regressor.

Compared multiple regression models with cross-validation.

🚀 How to Run
bash
Copy
Edit
git clone https://github.com/your-username/calories-burnt-prediction.git
cd calories-burnt-prediction
pip install -r requirements.txt
python main.py
Optional (for Streamlit GUI):

bash
Copy
Edit
streamlit run app.py
📂 Folder Structure
bash
Copy
Edit
├── data/                 # Dataset and processed files
├── notebooks/            # Jupyter notebooks for EDA and training
├── models/               # Trained model artifacts
├── main.py               # CLI-based prediction script
├── app.py                # Streamlit web app (optional)
└── README.md
✅ Future Improvements
Add wearable device integration (e.g., Fitbit API).

Deploy as an API using FastAPI/Flask.

Add calorie tracking dashboard.
