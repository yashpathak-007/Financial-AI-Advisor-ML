# 💰 Financial AI Advisor  
*Smart Expense Prediction & Budget Planning using Machine Learning*

The **Financial AI Advisor** is an AI-powered personal finance assistant that predicts monthly expenses and automatically generates a **personalized savings & investment strategy** based on the user's **income, lifestyle, and risk appetite**.  
Yeh app un logon ke liye perfect hai jo **apne kharch ko track**, **budget plan**, aur **future investment** plan karna chahte hain.

---

## ✨ Features

| Feature | Description |
|--------|-------------|
| **Expense Prediction** | ML model user ke profile ke base par monthly kharch predict karta hai |
| **Smart Budget Planning** | Income aur risk appetite ke hisaab se savings vs investment allocation deta hai |
| **Risk Analysis** | (Low / Medium / High) risk type ke according personalized strategy |
| **Interactive UI** | Streamlit based clean, modern, and user-friendly interface |
| **Visual Insights** | Pie charts & bar graphs for clear financial visualization |

---

## 🧠 How It Works

1. User inputs personal finance details (Age, Income, City Tier, Occupation, Dependents, Risk Level)
2. Model input ko encode + preprocess karta hai
3. **Random Forest Regression** model prediction deta hai
4. System budget + investment recommendation generate karta hai
5. Beautiful charts ke through financial view dikhaya jata hai

---

## 🛠️ Tech Stack

| Layer | Technologies Used |
|------|-------------------|
| **Machine Learning** | RandomForestRegressor, Pandas, NumPy |
| **Frontend UI** | Streamlit |
| **Visualization** | Plotly, Matplotlib, Seaborn |
| **Model Saving** | Joblib |
| **Environment** | Python 3.x |

---

## 📂 Project Folder Structure

Financial-AI-Advisor/
│── app.py # Streamlit app UI
│── model_offline.ipynb # Model training notebook
│── models/
│ ├── expense_model.pkl # Trained Random Forest Model
│ ├── occupation_encoder.pkl
│ └── city_encoder.pkl
│── dataset/
│── utils/
│── requirements.txt
│── README.md



## 🚀 Run the Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/Financial-AI-Advisor.git
cd Financial-AI-Advisor
2️⃣ Install Dependencies
bash
Copy code
pip install -r requirements.txt
3️⃣ (Optional) Retrain the Model
bash
Copy code
jupyter notebook model_offline.ipynb
4️⃣ Run the App
bash
Copy code
streamlit run app.py
Now visit in browser:
👉 http://localhost:8501/

📸 Sample Output Screenshots
Expense Prediction Screen	Budget Visualization Screen
	

🌟 Future Enhancements
User Login + Personalized Dashboard

Cloud-Based Data Storage

Advanced Investment Advisory Algorithms

Multi-Language Support (Hindi / English)

Android Mobile App Version

👨‍💻 Author
Yash Pathak
MCA | Machine Learning Enthusiast