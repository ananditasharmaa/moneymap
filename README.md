# 💰 MoneyMap – AI-Powered Expense Tracker

**MoneyMap** is a personal expense tracker web application built using Django and integrated with machine learning capabilities. It allows users to log their expenses, automatically categorizes them based on transaction descriptions, and predicts future expenses to help with smarter financial planning.

---

## 📌 Features

- **📋 Expense Logging**  
  Record daily expenses with fields like date, amount, category, and description.

- **🤖 Automated Categorization**  
  Uses a machine learning model to auto-categorize expenses based on keywords and historical data.

- **📈 Future Expense Prediction**  
  Predicts monthly spending trends based on user history to assist in budgeting decisions.

- **🔐 User Authentication**  
  Secure login and registration system with session-based user tracking.

- **📊 Visual Dashboards**  
  Interactive visualizations using Chart.js to display spending breakdowns by category and time.

---
## Preview
<img width="1600" height="765" alt="image" src="https://github.com/user-attachments/assets/e5b0caf7-2351-4b5e-9b72-914248519b3a" />
<img width="1600" height="819" alt="image" src="https://github.com/user-attachments/assets/4a1cb8d0-a4ca-4ce8-afe3-b974801557da" />
<img width="1475" height="787" alt="image" src="https://github.com/user-attachments/assets/128e07f4-d0dc-45e0-a5c7-7704cbe6c582" />
<img width="1572" height="769" alt="image" src="https://github.com/user-attachments/assets/9a5f9510-7f0d-4dc2-b91a-56148cd24914" />



## 🛠 Tech Stack

| Layer       | Tech                          |
|-------------|-------------------------------|
| Backend     | Django, Python, SQLite        |
| Machine Learning | Scikit-learn, Pandas, NumPy    |
| Frontend    | HTML, CSS, Bootstrap, Chart.js |
| Auth        | Django Authentication System  |

---

## 🚀 Getting Started

### ✅ Prerequisites

- Python 3.8+
- pip
- virtualenv (optional but recommended)

### 🧑‍💻 Installation Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/ananditasharmaa/moneymap.git
   cd smartspend
   ```
2. **Create and Activate Virtual Environment**
   ```bash
   python -m venv env
   source env/bin/activate    # On Windows: env\Scripts\activate
   ```
3. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```
4. **Run Migrations**
   ```bash
   python manage.py migrate
   ```
5. **Create Superuser**
   ```bash
   python manage.py createsuperuser
   ```
6. **Start the Serverr**
   ```bash
   python manage.py runserver
   ```
7. Open your browser and go to http://127.0.0.1:8000/
