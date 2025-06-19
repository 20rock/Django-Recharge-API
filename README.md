## 📱 Django-Recharge-API
A Django-based REST API for managing mobile recharge operators, plans, and transaction history.

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![Django](https://img.shields.io/badge/Django-4.x-green.svg)](https://www.djangoproject.com/)
[![REST Framework](https://img.shields.io/badge/REST_framework-3.x-yellowgreen.svg)](https://www.django-rest-framework.org/)

This project provides a RESTful API built with Django and Django REST Framework for managing mobile recharge operations. It includes models for operators, plans, and transaction history, with serializers for data representation and API endpoints for CRUD operations.

## 📋 Summary

This project is a Django-based REST API designed to handle mobile recharge operations. It provides key capabilities such as managing recharge operators, plans, and tracking transaction history. The API is intended for use by mobile recharge service providers and developers who need a backend solution for managing recharge-related data. The project utilizes technologies like Django, Django REST Framework, and SQLite for database management.

## ✨ Features

- 🗂️ **Data Models**: Defines models for `Oprators`, `Plans`, and `History` to manage recharge-related data.
- ⚙️ **CRUD Operations**: Implements Create, Read, Update, and Delete operations for managing operators, plans, and transaction history.
- 📝 **Data Serialization**: Uses Django REST Framework serializers to convert model instances into JSON for API responses.
- 🌐 **API Endpoints**: Provides API endpoints for managing operators, plans, and transaction history.
- 💾 **Database Management**: Uses SQLite for database storage and management.

## 🛠️ Tech Stack

**Languages & Frameworks:**
- **Python** - 26 files (29KB)

**Key Technologies:**
- **Frameworks**: Express.js, Django, Flask
- **Build Tools**: 
- **Databases**: Redis, SQLite
- **Testing**: None detected

**Dependencies** (8 total):
- `djangorestframework`
- `os`
- `sys`
- `django`
- `pathlib`
- `rest_framework`
- ``
- `MobileRecharge`

## 🚀 Project Setup

**Prerequisites:**
- Python 3.x
- Django
- Django REST Framework
- `requirements.txt` file

**Installation:**
```bash
pip install -r Recharge/requirements.txt
```

**Configuration:**
No environment variables detected. Project uses SQLite database.

**Available Scripts:**
No specific scripts identified other than standard Django commands.

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
│   │   │   ├── 🐍 0010_remove_oprators_oprator_code_and_more.py
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
- `Recharge/MobileRecharge/`: Contains Django app related to mobile recharge functionality including models, views, serializers, and migrations.
- `Recharge/Recharge/`: Contains core Django project settings, URLs, and WSGI configuration.
- `Recharge/`: Project root, contains `manage.py` and `requirements.txt`.

**Key Files:**
- `manage.py`: Django command-line utility for administrative tasks.
- `Recharge/Recharge/settings.py`: Django project settings file.
- `Recharge/MobileRecharge/models.py`: Defines the database models for operators, plans, and history.
- `Recharge/MobileRecharge/views.py`: Contains view functions/classes for handling API requests.
- `Recharge/MobileRecharge/serializers.py`: Defines serializers for converting model instances to JSON.

## 👥 Author and Support

**Author Information:**
- Repository owner: **avinashkr-ai**
- Project: **Django-Recharge-API**
- GitHub: [https://github.com/avinashkr-ai](https://github.com/avinashkr-ai)

**Contributing:**
- Contributions are welcome. Please fork the repository and submit a pull request with your changes.
- Ensure code adheres to the project's coding standards.

**Support:**
- For issues and bug reports, please open an issue on GitHub.
- For general questions, contact the author via GitHub.

**License:**
- License: See LICENSE
- The project is licensed under the terms specified in the LICENSE file. Usage rights and restrictions are defined in the license.