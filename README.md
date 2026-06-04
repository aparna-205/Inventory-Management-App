# Flask Inventory Management App

A full-stack inventory management web application built with **Flask** and **SQLite**. Manage products, vendors, warehouse locations, and stock movements through a clean dashboard interface.

---

## 🚀 Live Demo

> _Add your deployment link here (e.g. Render, Railway, PythonAnywhere)_

---

## ✨ Features

- 📦 **Product Management** — add, edit, and remove products from inventory
- 🏭 **Vendor Management** — track suppliers and vendor details
- 🗺️ **Location Management** — manage warehouse and storage locations
- 👤 **User Tracking** — log who is making changes to the dashboard
- 📊 **Summary Dashboard** — see which products are available at which warehouse at a glance

---

## 🛠 Tech Stack

| Layer | Technology |
|-------|------------|
| Backend | Python, Flask |
| Frontend | HTML, jQuery |
| Database | SQLite, SQLAlchemy |
| Server | Localhost (Flask dev server) |

---

## ⚙️ Setup & Installation

**1. Clone the repo**
```bash
git clone https://github.com/aparna-205/Inventory-Management-App
cd flask-inventory-app
```

**2. Create a virtual environment and install dependencies**

Option A — using pip + virtualenv:
```bash
virtualenv venv

# On Windows:
venv\Scripts\activate

# On Mac/Linux:
. venv/bin/activate

pip install -r requirements.txt
```

Option B — using Pipenv:
```bash
pipenv install
pipenv shell
```

**3. Run the application**

Make sure your virtual environment is activated, then:
```bash
flask run
```

Open your browser at `http://localhost:5000`

---

## 📂 Project Structure

```
flask-inventory-app/
├── app.py                  # Main Flask application
├── models.py               # SQLAlchemy database models
├── templates/              # HTML templates
├── static/                 # CSS, JS, jQuery assets
├── requirements.txt        # Python dependencies
└── README.md
```

---

## 📋 Requirements

```
Flask
Flask-SQLAlchemy
```

Install all at once:
```bash
pip install -r requirements.txt
```

---

## 📸 Screenshots

#### Main dashboard
![Main Dashboard](https://i.imgur.com/Ad7tJuM.jpg)

#### Add products
![Add Products](https://i.imgur.com/MIirapE.png)

#### Manage vendors
![Vendors](https://i.imgur.com/0zswrFW.jpg)

#### Manage locations
![Locations](https://i.imgur.com/CVmws9c.jpg)

#### User / change tracking
![User Tracking](https://i.imgur.com/YFafEVW.jpg)

#### Warehouse summary
![Warehouse Summary](https://i.imgur.com/X4bwBg9.jpg)

---

## 🗺 Roadmap

- [ ] Add user authentication (login/logout)
- [ ] REST API endpoints for mobile integration
- [ ] Export inventory report as CSV/PDF
- [ ] Low stock alerts

---

## 📄 License

MIT License — free to use and modify.

---

## 🙋 About

Built by **Aparna** · [GitHub](https://github.com/aparna-205)

> Open to freelance projects in Python, Flask, and Streamlit. Feel free to reach out!
