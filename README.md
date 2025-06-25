# CRM Software using AI/ML

This project is a lightweight Customer Relationship Management (CRM) software that leverages AI/ML for intelligent customer handling, lead scoring, and sales prediction. Built for scalability and easy local setup.

---

# CRM‑Software‑using‑AI‑ML

🚀 **AI‑powered CRM** built with Python to intelligently manage leads, customers, and sales using machine learning.

**Key Features:**
- 🧠 **Lead Scoring** — ML-powered prediction of lead conversion likelihood.
- 📊 **Customer Segmentation** — Group customers by behavior & engagement.
- 📈 **Analytics Dashboard** — Track KPI metrics such as conversion rates, pipeline value, and lead sources.
- 🔍 **Smart Search** — Fast search across contacts, companies, and deals.
- 🔐 **User Authentication** — Secure login with JWT tokens.
- 📥 **Import/Export** — Upload and download CSV contact data.
- 🌐 **Local‑First Deployment** — Quick setup with SQLite and offline ready.

**Tech Stack:**
- **Backend**: Python with FastAPI (or Django alternative)
- **Frontend**: React.js + Tailwind CSS (or Django templates)
- **Database**: SQLite (local) or PostgreSQL (production)
- **ML Libraries**: scikit‑learn, pandas, NumPy
- **Model Management**: joblib for serialization
- **Auth**: JWT / OAuth2

---

## 🚀 Quick Start

```bash
git clone https://github.com/akashsingh06/CRM‑software‑using‑AI‑ML.git
cd CRM‑software‑using‑AI‑ML
python3 -m venv venv
source venv/bin/activate           # Windows: venv\Scripts\activate
pip install -r requirements.txt
# Run DB migrations (if Django):
# python manage.py migrate
uvicorn app.main:app --reload     # FastAPI server

**Prerequisites**
Python 3.9+

Node.js 16+

pip

virtualenv (recommended)
