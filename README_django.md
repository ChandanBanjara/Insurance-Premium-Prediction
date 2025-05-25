
# 🛡️ Insurance Management System (Django Project)

This is a Django-based Insurance Management System designed to handle and manage insurance-related functionalities efficiently.

## 📁 Project Structure

.
├── manage.py             # Django management script
├── db.sqlite3            # SQLite database file
├── insurance/            # Project settings module (inferred from manage.py)
├── .env                  # (Optional) Environment variables (email, API keys, etc.)
├── app/                  # Your Django app (not uploaded but assumed to exist)

## 🚀 Features

- Django web framework-based architecture
- SQLite3 database for development
- Modular structure for future extension (authentication, claims, policies, etc.)

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/insurance-management-system.git
cd insurance-management-system

### 2. Create Virtual Environment

bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

### 3. Install Dependencies

bash
pip install -r requirements.txt

### 4. Run Migrations

bash
python manage.py migrate

### 5. Run the Development Server

bash
python manage.py runserver

Visit `http://127.0.0.1:8000/` in your browser.

## 🔐 Security

- Keep your `.env` file secret.
- Add `.env` and `__pycache__/` to `.gitignore`.

## 📫 Contact

For queries, contact:
- 📧 chandanbanjara12@gmail.com
