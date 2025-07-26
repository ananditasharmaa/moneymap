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
