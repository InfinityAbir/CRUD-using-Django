# CRUD-using-Django
## 📖 Description  This is a basic Django web application that demonstrates how to perform **CRUD operations** on a database model. The app allows users to add, view, update, and delete member records. It’s designed for beginners who are learning Django and want a hands-on example of how to work with models, views, templates, and forms.

# Django CRUD Application

A simple web application using **Django** that performs basic **CRUD (Create, Read, Update, Delete)** operations on a member database.

## 🚀 Features

- List all members (Read)
- Add new member (Create)
- Update existing member (Update)
- Delete a member (Delete)

## 🛠️ Built With

- Python 3.x
- Django 4.x or higher
- SQLite (default Django database)

## 📂 Project Structure

```
myproject/
├── members/
│   ├── migrations/
│   ├── templates/
│   │   ├── index.html
│   │   ├── add.html
│   │   ├── update.html
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── views.py
│   ├── urls.py
├── myproject/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
├── db.sqlite3
├── manage.py
├── README.md
```

## 📦 Installation

1. **Clone the repository:**

```bash
git clone https://github.com/InfinityAbir/CRUD-using-Django.git
cd django-crud-app
```

2. **Create a virtual environment and activate it:**

```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

3. **Install dependencies:**

```bash
pip install -r requirements.txt
```

> If you don't have a `requirements.txt`, you can use:
```bash
pip install django
```

4. **Run migrations:**

```bash
python manage.py migrate
```

5. **Run the development server:**

```bash
python manage.py runserver
```

6. **Open in browser:**

Visit: `http://127.0.0.1:8000/`

## ✍️ How to Use

- Navigate to the homepage to see all members.
- Click "Add Member" to create a new entry.
- Click "Edit" to update an existing member.
- Click "Delete" to remove a member.

## ✅ To-Do 

- Add form validation
- Add Bootstrap for better UI
- Add user authentication

## 📸 Screenshots

<img width="1169" height="417" alt="image" src="https://github.com/user-attachments/assets/a3c20d7a-645a-427b-8908-4be235ab2d76" />
<img width="508" height="518" alt="image" src="https://github.com/user-attachments/assets/0e1ea535-1fba-46a4-8060-b184fac99b0d" />
<img width="381" height="496" alt="image" src="https://github.com/user-attachments/assets/fa0f5bc9-3cb1-4491-9391-8e328c41a9b0" />


## 🧑‍💻 Author

- Abir Hasan — (https://github.com/infinityabir)

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
