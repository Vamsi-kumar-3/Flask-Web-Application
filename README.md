# ✅ Flask To-Do List Web Application

A simple yet functional **To-Do List** web application built using the **Flask** framework. This project allows users to add, view, and delete tasks, with task data stored in a SQLite database. The project is deployed on **PythonAnywhere**.

---

## 🚀 Live Demo

🔗 [View the Deployed Application](https://your-pythonanywhere-link.com)  
*(Replace with your actual deployment link)*

---

## ✨ Features

✔️ Add new tasks  
✔️ View all tasks  
✔️ Mark tasks as completed (Optional Feature)  
✔️ Delete tasks  
✔️ Minimal and responsive design  
✔️ Data stored using SQLite  

---

## 🛠️ Tech Stack

- **Backend:** Python, Flask  
- **Database:** SQLite  
- **Frontend:** HTML, CSS (with Jinja2 templates)  
- **Deployment:** PythonAnywhere  

---

## 📁 Project Structure

TodoApp/
├── instance/ # Configuration files (optional)
├── static/ # Static assets (CSS, images)
├── templates/ # HTML templates
│ ├── base.html
│ ├── index.html
│ └── add_task.html
├── app.py # Main Flask application
├── requirements.txt # Python dependencies
└── README.md # Project information

yaml
Copy
Edit

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/flask-todo-app.git
cd flask-todo-app
2. Create a Virtual Environment (Recommended)
bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
3. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
4. Run the Application
bash
Copy
Edit
python app.py
The app will be available at:
http://127.0.0.1:5000/

