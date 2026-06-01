# SnapBudget: AI & Machine Learning Backend

Welcome to the AI and Machine Learning repository for **SnapBudget**. This repository contains the training notebooks, dataset preprocessing scripts, and saved model weights used to power the intelligent financial tracking features of SnapBudget, such as automated receipt scanning (OCR), expense extraction, and smart budget forecasting.

---

## 🚀 Features

* **Receipt OCR & Extraction:** Automatically extract merchant names, transaction dates, and total amounts from receipt images.
* **Predictive Spending:** Machine Learning models to predict future expenses based on historical user data.
* **Smart Budget Recommendation:** AI-driven budgeting advice tailored for Indonesian university students.

---

## 📂 Repository Structure

```text
.
├── Head1/
├── Head2/          # GRU and MLP Training Model to predicts user spending for the next 7 days based on the past 30 days of transaction history. 
├── Head3/             # BiLSTM Training Model
└── README.md           # Project documentation
```

## 🛠️ Getting Started

Prerequisites
Make sure you have Python 3.9+ installed on your local machine.

Installation & Setup
Clone this repository:

Bash
git clone [https://github.com/SnapBudget-AI-Financial-Tracker/snapbudget-backend-ai.git](https://github.com/SnapBudget-AI-Financial-Tracker/snapbudget-backend-ai.git)
cd snapbudget-backend-ai
Create and activate a virtual environment:

Bash
# Windows (PowerShell)
python -m venv venv
.\venv\Scripts\Activate.ps1

# Linux / MacOS
python3 -m venv venv
source venv/bin/activate
Install dependencies:

Bash
pip install -r requirements.txt
🧠 Model Training & Development
To explore or retrain the models, navigate to the notebooks/ directory and open the files using Jupyter Lab or Notebook:

Bash
pip install jupyterlab
jupyter lab
