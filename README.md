# Hydrate mate

3) README.md (paste as-is)

# HydrateMate

**Mini project** — Simple hydration tracker built with Flask + SQLite.

## Aim
Build a lightweight app that lets a user:
- Set a daily water goal (ml)
- Add water-intake entries (ml)
- View today's total and progress (%)
- See recent entries and simple history

## Project structure

HydrateMate/ ├─ app.py ├─ requirements.txt ├─ templates/ └─ static/

## How it works (short)
1. User adds water (ml) on `/add`.  
2. Server stores entry with timestamp and day.  
3. Home page shows today's sum and percentage of goal.

## Run locally
```bash
python -m venv venv
# on Windows:
venv\Scripts\activate
# on mac/linux:
source venv/bin/activate

pip install -r requirements.txt
python app.py
# open http://127.0.0.1:5000/

How to push to GitHub

Replace <GITHUB_USERNAME> and <REPO_NAME> with your info.

git init
git add .
git commit -m "Initial commit: HydrateMate Flask app"
# create remote repo on GitHub web UI named <REPO_NAME>, then:
git remote add origin https://github.com/<GITHUB_USERNAME>/<REPO_NAME>.git
git branch -M main
git push -u origin main

