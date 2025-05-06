# 📦 Flask CRUD API - Item Management

A simple RESTful API built with Flask that implements CRUD operations (Create, Read, Update, Delete) on an in-memory list of items. Perfect for learning, testing, or as a boilerplate for more complex projects.

---

## 🚀 Features

- 🔍 List all items (`GET /api/items`)
- 📄 Get a specific item by ID (`GET /api/items/<id>`)
- ➕ Create a new item (`POST /api/items`)
- ✏️ Update an existing item (`PUT /api/items/<id>`)
- ❌ Delete an item (`DELETE /api/items/<id>`)

---

## 🛠 Technologies

- Python 3.11.2
- Flask (web microframework)
- JSON for data exchange

---

## ⚙️ How to Run Locally

```bash
# Clone the repository
https://github.com/guilherme-cybersecurity/api-rest.git
cd "your-repo"

# Create and activate a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the app
python app.py
