# 💼 PaySphere – Comprehensive Payroll Management System

PaySphere is a feature-rich payroll management system built with Django. It is designed to automate and simplify payroll processes such as employee management, salary generation, leave tracking, and attendance. Ideal for startups, SMEs, and HR departments aiming to reduce manual efforts and enhance accuracy.

---

## 🛠️ Technologies Used

- **Backend**: Django (Python)
- **Frontend**: HTML, CSS, Bootstrap
- **Database**: SQLite (default), can be switched to PostgreSQL/MySQL
- **Other Tools**: Django Admin, Django Templates

---

## 📌 Features

### 👤 Employee Management
- Add, update, and delete employee profiles
- Store contact, job, and bank details
- Role-based access control

### 🧾 Salary Management
- Automated salary calculation (basic, HRA, allowances, deductions)
- Monthly payslip generation and download (PDF format)
- Tax and PF calculations

### 📅 Leave Management
- Leave request, approval, and history tracking
- Configurable leave types and policies
- Leave balance and carry forward

### 📌 Admin Dashboard
- Centralized panel for HR/Admin operations
- Graphs and reports on employee and payroll data
- Notifications and activity logs

---

## 🚀 Getting Started

### 📦 Prerequisites
- Python 3.8+
- Django 3.2+ (or latest LTS)
- Virtualenv (recommended)

### 🔧 Installation

```bash
# Clone the repository
git clone https://github.com/your-username/paysphere.git
cd paysphere

# Create virtual environment
python -m venv env
source env/bin/activate  # for Linux/macOS
env\Scripts\activate     # for Windows

# Install dependencies
pip install -r requirements.txt

# Apply migrations
python manage.py migrate

# Create a superuser
python manage.py createsuperuser

# Run the server
python manage.py runserver
