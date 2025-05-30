<h1 align="center">🔐 Password Generator Web App 🔐</h1>

<p align="center">
    A simple, efficient, and secure web-based password generator built using Python & Django.
    <br>
    <strong>Generate strong passwords, store them safely, and access them anytime!</strong>
</p>

---

## 📂 Project Structure 

---

## 🚀 Features

- 🔑 Generate strong, secure passwords instantly
- 💾 Save generated passwords in a local SQLite database
- 📁 Clean project structure using Django framework
- 🌐 Simple and user-friendly web interface

---

## 🛠️ Tech Stack

- **Backend:** Python, Django
- **Frontend:** HTML (with Django templating)
- **Database:** SQLite3

---

## 💡 How to Run Locally

```bash
# Step 1: Clone the repository
git clone https://github.com/Praveen23-kk/Password-Generator.git
cd Password-Generator

# Step 2: Create a virtual environment
python -m venv env
source env/bin/activate    # On Windows use `env\Scripts\activate`

# Step 3: Install dependencies
pip install -r requirements.txt  # (create this file if not available)

# Step 4: Run migrations
python manage.py migrate

# Step 5: Run the server
python manage.py runserver

# Visit http://127.0.0.1:8000 on your browser
