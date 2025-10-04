# 🧑‍💻 UserCommands.md — My Local Dev Setup for Streamlit Multi-App

This is my personal guide for setting up, running, and maintaining the **Streamlit Multi-App Dashboard** project locally on Windows.

---

## Setup and commands


py -m venv .venv
.venv\Scripts\Activate.ps1


pip install --upgrade pip
pip install -r requirements.txt

**to run main dashboard**:
py -m streamlit run dashboard.py --server.port 8501


**to test any app manually**:
cd Project1
streamlit run app.py --server.port 8601


**updating and committing**:

git add .

git commit -m "Updated dashboard for Windows subprocess fix"

git push origin main
