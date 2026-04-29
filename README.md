# 💰 Expense Management System

This is a full-stack **Expense Management System** designed to help users track their spending across various categories with an intuitive web interface. The project is built with **Streamlit** for the frontend and **FastAPI** for the backend, using a SQL database for data storage.

---

## 🚀 Technologies Used

- **Python**
- **Streamlit** (Frontend)
- **FastAPI** (Backend)
- **SQL** (Database)
- **Postman** (API Testing)
- **Git Bash** (Version Control and CLI)

---

## 🧱 Project Structure

- **Frontend/**: Contains the Streamlit application code.
- **Backend/**: Contains the FastAPI backend server code.
- **Tests/**: Contains the test cases for both frontend and backend.
- **requirements.txt**: Lists the required Python packages.
- **README.md**: Provides an overview and instructions for the project.

---

## ⚙️ Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/Python-Expense-Management-System.git
cd Python-Expense-Management-System
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the FastAPI Server
```bash
cd Backend
uvicorn server:app --reload
```

### 4. Run the Streamlit App
```bash
cd Frontend
streamlit run ./app.py
```

---

## 🧩 Problem Statement

Managing expenses across various categories like rent, food, and shopping can become chaotic without a proper tracking system. This project solves that problem by providing a user-friendly web interface to:

1. **Add and update expenses by date**.
2. **Visualize expenses by category** within a specified date range.
3. **Analyze monthly spending trends**.

---

## 🖥️ Project Overview (with Screenshots)

### 1. **Add/Update**
Users can add new expenses or update existing ones by selecting a date and entering the amount, category and an optional notes.

![Add or Update](<img width="954" height="731" alt="add_update_ui" src="https://github.com/user-attachments/assets/cf560e6d-c3a0-4456-945e-17d27806898c" />
)

---

### 2. **Analytics by Category**
Generates visualizations of spending by category within a custom date range.

![Analytics by Category](<img width="616" height="759" alt="analytics_by_category" src="https://github.com/user-attachments/assets/f7f3906c-b9a0-4300-b516-d3fe63787ffb" />
)

---

### 3. **Analytics by Months**
Shows monthly trends of spending across all categories.

![Analytics by Months](<img width="617" height="823" alt="analytics_by_month" src="https://github.com/user-attachments/assets/a25bc7b3-b461-4a7b-a56a-577f93ee1638" />
)

---

## 🎯 Project Outcome

- Simplifies **budget tracking** and helps identify overspending areas.
- Enables users to make **data-driven decisions** for saving money.
- Encourages **financial discipline** through visual feedback and organized records.
- Modular design allows easy extension for features like authentication or export to Excel.

---

## 🧠 Skills Learned

- Full-stack development with **FastAPI** and **Streamlit**.
- Building and consuming **REST APIs**.
- Data visualization using **bar charts** and **tables**.
- Structuring a scalable Python project.
- Implementing Database **CRUD** Opreations.
- Establishing automated **tests** setups for **CRUD**.
- Testing APIs with **Postman**.
- Version control with **Git**.

---

