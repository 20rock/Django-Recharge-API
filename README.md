## 📱 Django Recharge API

A Django-based API for managing mobile recharge plans, operators, and transaction history.

[![Python](https://img.shields.io/badge/Python-3.6+-blue.svg?style=flat-square)](https://www.python.org/)
[![Django](https://img.shields.io/badge/Django-4.0+-green.svg?style=flat-square)](https://www.djangoproject.com/)

This project provides a Django-powered REST API to handle mobile recharge operations. It includes models for operators, plans, and transaction history. This API is designed to be scalable and easily maintainable.

## 📋 Summary

This project is a Django-based API designed to manage mobile recharge functionalities. It allows for managing operators, plans, and transaction history related to mobile recharges. The target audience includes developers needing to integrate mobile recharge functionalities into their applications. The primary technologies used include Django, Django REST framework, and SQLite (for development).

Key capabilities:
- Manages mobile recharge operators
- Manages mobile recharge plans
- Tracks transaction history

## ✨ Features

- 📱 **Operator Management**:
    - ✅ Add, update, and manage mobile recharge operators.
    - 📊 Track operator status (active/inactive).

- 💰 **Plan Management**:
    - ✅ Define and manage different recharge plans.
    - 📅 Assign plans to specific operators.

- 📜 **Transaction History**:
    - ✅ Log and track recharge transaction history.
    - 📈 Monitor transaction amounts.

## 🛠️ Tech Stack

**Languages & Frameworks:**
- **Python** - 29 files (~747 lines of code)

**Key Technologies:**
- **Frameworks**: Django, Django REST Framework
- **Databases**: SQLite
- **Testing**: None detected

**Dependencies** (18 total):
- `asgiref`
- `autopep8`
- `backports.zoneinfo`
- `Django`
- `django-cors-headers`
- `djangorestframework`
- `pycodestyle`
- `pytz`
- `sqlparse`
- `tomli`
- `tzdata`
- `os`
- `sys`
- `django`
- `pathlib`

## 🚀 Project Setup

**Prerequisites:**
- Python 3.6+
- pip

**Installation:**

```bash
# Clone the repository
git clone https://github.com/avinashkr-ai/Django-Recharge-API.git
cd Django-Recharge-API/Recharge

# Create a virtual environment
python3 -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Apply migrations
python manage.py migrate

# Run the development server
python manage.py runserver
```

**Configuration:**
- No environment variables were detected.

**Available Scripts:**
- `python manage.py runserver`: Starts the Django development server.
- `python manage.py migrate`: Applies database migrations.

## 📁 Project Structure

```text
📁 Django-Recharge-API/
├── 📁 Recharge/
│   ├── 📁 MobileRecharge/
│   │   ├── 📁 migrations/
│   │   │   ├── 🐍 0001_initial.py
│   │   │   ├── 🐍 0002_oprators.py
│   │   │   ├── 🐍 0003_alter_oprators_oprator_type.py
│   │   │   ├── 🐍 0004_alter_oprators_oprator_type.py
│   │   │   ├── 🐍 0005_plans_alter_oprators_options_oprators_created_and_more.py
│   │   │   ├── 🐍 0006_rename_oprator_status_oprators_oprator_state_and_more.py
│   │   │   ├── 🐍 0007_history_alter_oprators_oprator_state_and_more.py
│   │   │   ├── 🐍 0008_history_amount_alter_oprators_oprator_state_and_more.py
│   │   │   ├── 🐍 0009_delete_snippet.py
│   │   │   └── 🐍 __init__.py
│   │   ├── 🐍 __init__.py
│   │   ├── 🐍 admin.py
│   │   ├── 🐍 apps.py
│   │   ├── 🐍 models.py
│   │   ├── 🐍 serializers.py
│   │   ├── 🐍 tests.py
│   │   ├── 🐍 urls.py
│   │   └── 🐍 views.py
│   ├── 📁 Recharge/
│   │   ├── 🐍 __init__.py
│   │   ├── 🐍 asgi.py
│   │   ├── 🐍 settings.py
│   │   ├── 🐍 urls.py
│   │   └── 🐍 wsgi.py
│   ├── 🐍 main.py
│   ├── 📋 requirements.txt
│   ├── 📄 db.sqlite3
│   └── 🐍 manage.py
├── 🚫 .gitignore
└── 📄 LICENSE
```

**Key Directories:**
- `Recharge/MobileRecharge/`: Contains the Django app for mobile recharge functionality, including models, views, and serializers.
- `Recharge/Recharge/`: Contains the Django project settings, URLs, and WSGI configuration.
- `Recharge/MobileRecharge/migrations/`: Contains database migration files.
- `Recharge/`: Root directory containing the `manage.py` script and `requirements.txt`.

**Important Files:**
- `Recharge/MobileRecharge/models.py`: Defines the data models for operators, plans, and transaction history.
- `Recharge/MobileRecharge/views.py`: Contains the view logic for handling API requests.
- `Recharge/MobileRecharge/serializers.py`: Defines serializers for converting model instances to JSON.
- `Recharge/Recharge/settings.py`: Configuration file for the Django project.
- `Recharge/urls.py`: Defines URL patterns for the API endpoints.
- `manage.py`: Django management script for running commands.

## 👥 Author and Support

**Author Information:**
- Repository owner: **avinashkr-ai**
- Project: **Django-Recharge-API**
- GitHub: [https://github.com/avinashkr-ai](https://github.com/avinashkr-ai)

**Contributing:**
- Contributions are welcome! Please fork the repository and submit a pull request with your changes.

**Support:**
- For any issues or questions, please open an issue on the GitHub repository.

**License:**
- License: See LICENSE
- This project is licensed under the terms of the MIT license. See the LICENSE file for details.