# Healthcare Chatbot (Mini Project)


A simple ML-powered healthcare chatbot that: intent classification using TF-IDF + Logistic Regression, a rule-based symptom-to-disease mapper, and a Flask web UI.


## Features
- Intent detection (greeting, symptom_check, health_faq, department, goodbye)
- Symptom → possible disease mapper (rule-based, for demo only)
- Flask frontend (chat UI)


## How to run
1. Create a virtual environment (recommended) and activate it.
2. Install dependencies:
```bash
pip install -r requirements.txt
Train the intent classifier (optional; a pre-trained model will be created if not present):
python train_intent.py
Run the app:
python app.py
Open http://127.0.0.1:5000 in your browser.

Notes

This project is for educational/demo purposes and does not provide medical diagnosis.

You can replace the intent dataset with your own larger dataset for better performance.
