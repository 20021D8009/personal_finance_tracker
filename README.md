# Personal Finance Tracker

A command-line application to help you track income and expenses, visualize your financial data, and predict future expenses using machine learning. Built with Python, SQLite, Pandas, and Scikit-learn.

---

## 🚀 Features

* Add and manage income/expense transactions
* Store financial data in a local SQLite database
* Generate category-wise summaries and monthly income vs expense charts
* Predict next month's expenses using a linear regression model
* Simple CLI-based interface for easy usage

---

## 🛠️ Tech Stack

* **Backend & Data Storage:** Python, SQLite
* **Data Analysis & ML:** Pandas, Scikit-learn
* **Visualization:** Matplotlib

---

## 📂 Project Structure

```
personal_finance_tracker/
├── app.py               # Main application file
├── finance.db           # SQLite database (auto-created on first run)
└── README.md            # Project overview and usage instructions
```

---

## ⚙️ Setup Instructions

1. **Clone the Repository**

```bash
git clone https://github.com/yourusername/personal_finance_tracker.git
cd personal_finance_tracker
```

2. **Install Dependencies**

```bash
pip install pandas matplotlib scikit-learn
```

3. **Run the Application**

```bash
python app.py
```

---

## 🧪 How to Use

1. **Add Transaction**
   Input the date, category, amount, type (income/expense), and optional notes.

2. **Show Dashboard**
   View a summary of your expenses and a chart comparing monthly income vs expense.

3. **Predict Next Month's Expense**
   Use linear regression to estimate next month’s spending based on historical data.

---

## 💡 Example Use Cases

* Track monthly spending and categorize expenses
* Analyze your budgeting habits visually
* Predict future spending trends for better financial planning

---

## 📌 Notes

* Make sure to enter dates in the format `YYYY-MM-DD`
* Minimum two months of expense data are required for ML prediction
* All data is stored locally in `finance.db`

---
