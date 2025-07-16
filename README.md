# 🚀 Flask CI/CD Demo with GitHub Actions

This is a simple **Flask web application** integrated with **GitHub Actions CI/CD**.  
It demonstrates how to automate testing and deployment steps for a Python app.

---

## 📂 Project Structure

flask-cicd-demo/
├── app.py # Simple Flask web app
├── requirements.txt # Dependencies for the app
└── .github/
└── workflows/
└── python-app.yml # GitHub Actions CI/CD workflow


---

## ⚙️ What This Project Does

✅ Creates a simple **Flask Hello World** app  
✅ Uses a **virtual environment** for dependencies  
✅ Generates `requirements.txt` for reproducible builds  
✅ Adds a **GitHub Actions CI/CD pipeline** to automate builds  
✅ Runs CI pipeline automatically when you push code  

---

## 🔄 CI/CD Pipeline Flow

The GitHub Actions workflow (`python-app.yml`) does the following:

1. **Triggers on every push** to the `main` branch  
2. **Checks out the repository**  
3. **Sets up Python 3.9**  
4. **Installs dependencies** from `requirements.txt`  
5. **Builds & validates the app**  

✅ If all steps succeed, you see a **green checkmark** in GitHub Actions  
❌ If anything fails, it shows an error log  

---

## 🛠️ Tech Stack

- **Python 3.13**
- **Flask 3.1**
- **GitHub Actions** (for CI/CD)
- **pip** for dependency management

---

## ▶️ How to Run Locally

1. Clone the repo:
   ```bash
   git clone https://github.com/DhrumilR/flask-cicd-demo.git
   cd flask-cicd-demo
2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate   # Linux/Mac
   venv\Scripts\activate      # Windows
   pip install -r requirements.txt
python app.py
http://127.0.0.1:5000
How CI/CD Works Here
When you push any change to main, GitHub Actions automatically runs the workflow.

It installs dependencies from requirements.txt, then validates the app.

If everything works, you’ll see a green checkmark in Actions tab.

If it fails, you’ll get logs with the exact error.

Tech Used
Python 3.13

Flask 3.1

GitHub Actions for CI/CD

pip for dependencies

Author
Dhrumil Raval
GitHub Profile


