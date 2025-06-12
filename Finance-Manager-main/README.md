# Finance Manager

Finance Manager is a Django-based web application designed to help users efficiently track their personal finances. It enables logging of income and expenses, viewing analytics, setting budgets, and getting an overall understanding of spending habits through intuitive dashboards and category-wise insights.

## 🚀 Features

- User authentication (login/register)
- Add, edit, and delete income and expenses
- Categorized financial tracking
- Monthly summaries
- Visualizations with charts
- Budget monitoring and warnings

## 🛠️ Tech Stack

- Backend: Python, Django
- Frontend: HTML, CSS, Bootstrap, Chart.js
- Database: SQLite (default, can be switched)
- Templates: Django Template Language (DTL)

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Finance-Manager.git
   cd Finance-Manager
Create and activate a virtual environment:

bash
Copy
Edit
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run migrations:

bash
Copy
Edit
python manage.py migrate
Start the development server:

bash
Copy
Edit
python manage.py runserver
Open in browser:

cpp
Copy
Edit
http://127.0.0.1:8000/
✅ Usage
Register and log in as a user.

Navigate to "Add Income" or "Add Expense" to record transactions.

Use the dashboard to view analytics.

Manage categories and budgets under "Settings".

📄 License
This project is licensed under the MIT License.