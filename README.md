# Mediaz - Twitter-like Clone (CP Project)

A lightweight social media web application built with **Flask (Python)** simulating core Twitter functionalities, including user profiles, posting updates, feed querying, comments, and deployment-ready architecture.

🔗 **Live Demo:** [https://mediaz-ten.vercel.app](https://mediaz-ten.vercel.app)

---

## 👥 Team Members

- **Khushal**
- **Jivesh**
- **Agrim**
- **Vansh**

---

## 🚀 Features

- **User Authentication & Profiles:** Custom profile pages and session management.
- **Feed & Timeline:** Query-optimized timeline with pagination for viewing posts.
- **Posting & Interactions:** Create text posts and comment directly under posts.
- **Cloud Deployment:** Configured for serverless hosting via Vercel.

---

## 🛠️ Tech Stack & Architecture

- **Backend:** Python (Flask)
- **Frontend:** HTML, CSS, Jinja Templates (located in `/templates` & `/static`)
- **Database/ORM:** SQLAlchemy / SQLite (`models.py`, `extensions.py`)
- **Deployment:** Vercel Serverless (`vercel.json`)

---

## 📁 Project Structure

```text
├── static/             # Static assets (CSS, JS, images)
├── templates/          # Jinja2 HTML templates
├── app.py              # Application entry point & configuration
├── extensions.py       # Flask extensions setup
├── models.py           # Database schema & models
├── routes.py           # Application routes & endpoint controllers
├── requirements.txt    # Project dependencies
└── vercel.json         # Deployment configuration for Vercel
