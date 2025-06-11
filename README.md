# 🧠 Multilingual Dynamic Resume Builder – llol_step03

A powerful and modular Flask application for building interactive, multilingual resumes with full admin control.  
This is part of the **llol_step** educational journey under the [Flask University](https://github.com/Flask-University) initiative.

---

## 🚀 Features

- ✅ Dynamic resume builder with full CRUD for sections, paragraphs, and fields
- 🌐 Multilingual support with `flask-babel` and automatic translation via `deep_translator`
- 🎨 Custom styling controls with live preview (section titles, paragraph styles, fonts)
- 🧱 Admin interface to manage visibility, ordering, and content of resume parts
- 🧭 Customizable navigation menu
- 📜 Fully translatable content via `.po` files
- 💼 Public resume view with live language switching

---

## 🗂️ Project Structure

```bash
tameronline-llol_step03/
├── main/
│   ├── routes/            # Main, public, and admin routes (modular)
│   ├── models/            # SQLAlchemy models
│   ├── logic/             # Business logic (e.g., CSS building)
│   ├── tools/             # Utility scripts like database initialization
│   ├── static/            # CSS assets
│   ├── templates/         # Jinja2 templates (admin/public/partials)
│   ├── translations/      # .po/.mo files for supported languages
│   └── config/            # Centralized settings
├── requirements.txt
└── run.py
```

---

## 🌍 Supported Languages

- English (`en`)
- Arabic (`ar`)
- German (`de`)

Easily switchable via the navbar or `?lang=` query parameter.

---

## ⚙️ Tech Stack

- **Backend**: Flask, SQLAlchemy, Flask-Babel
- **Frontend**: Jinja2, HTML5, CSS3
- **i18n**: Babel, Deep Translator (Google)
- **Database**: SQLite (easily swappable)
- **Deployment**: WSGI-ready (gunicorn + nginx compatible)

---

## 🛠️ Setup

```bash
# Clone the repository
git clone https://github.com/TamerOnLine/llol_step03.git
cd llol_step03

# Install dependencies
pip install -r requirements.txt

# Run the app
cd main
python run.py
```

---

## 🔡 Translation Workflow

To extract and translate strings:

```bash
# Run the i18n script
cd main
python i18n_translate.py
```

---


## 🛠️ Next Step

> 👉 [Go to llol_step04 →](https://github.com/TamerOnLine/llol_step04)

The next phase will focus on:
- Organizing admin routes into a dedicated folder
- Improving developer experience and modularity

---

## 📜 License

This project is open-source under the MIT License.  
Feel free to explore and build upon it.

---

## 👨‍💻 Developer

By [@TamerOnLine](https://github.com/TamerOnLine)  
Under the umbrella of [Flask University](https://github.com/Flask-University)
