# 🛡️ Automated Detection and Profiling of Emerging Cyber Threats using NLP

This project uses **Natural Language Processing (NLP)** and **Machine Learning** to detect and profile cyber threats from social media, particularly Twitter. It helps cybersecurity professionals monitor emerging threats in real-time by identifying keywords, threat types, and mapping them to the MITRE ATT&CK framework.

---

## 📌 Overview

Cybercriminals often exploit vulnerabilities shortly after they're discovered. To address this, our system:

- Collects tweets from cybersecurity-related sources.
- Cleans and processes the text data using NLP.
- Detects and classifies potential cyber threats.
- Profiles these threats based on attacker intent and tactics.
- Visualizes results using charts and dashboards.
- Alerts security teams based on severity and risk.

---

## 🧰 Tools & Technologies

- **Language**: Python  
- **Framework**: Django (for web interface)  
- **NLP Libraries**: NLTK, Scikit-learn  
- **Database**: MySQL (via WAMP Server)  
- **Frontend**: HTML, CSS, JavaScript  
- **Machine Learning Models**:
  - Logistic Regression
  - SVM
  - Random Forest
  - CNN
  - Gradient Boosting

---

## 🖥️ System Features

- User & Admin login interfaces
- Tweet preprocessing using stopwords, lemmatization, and tokenization
- Named Entity Recognition (NER)
- Threat classification (Phishing, DDoS, Ransomware, etc.)
- Accuracy tracking of different ML models
- Visualizations (bar, line, and pie charts)
- Export of results to Excel

---

## ⚙️ How to Run

1. Clone the repo:
git clone https://github.com/your-username/cyber-threat-nlp.git

2. Install dependencies:
pip install -r requirements.txt

3.Run the Django server:
python manage.py runserver

4.Open the browser at:
http://127.0.0.1:8000/

📊 Sample Output
CNN Accuracy: 79.03%

Logistic Regression Accuracy: 78.72%

Pie chart showing threat vs. no threat

Tables with tweet predictions and threat metadata

Example Input Tweet:

“A ransomware group just targeted a financial firm in the US!”

Predicted Output:

Threat Found: Yes


🚀 Future Enhancements
Use BERT or GPT models for better contextual analysis

Monitor dark web sources and blogs in addition to Twitter

Improve intent detection using POS tagging

Build a real-time dashboard for live monitoring

#Screenshots
![image](https://github.com/user-attachments/assets/d88d10bf-f006-4ce1-aa42-ab3c17e569c6)
![image](https://github.com/user-attachments/assets/91540d02-8493-4370-84fb-d84fc13c05d5)
![image](https://github.com/user-attachments/assets/a017f2eb-f35c-4a51-800a-2f0ab4df022d)
![image](https://github.com/user-attachments/assets/c280506f-75a0-4fd9-a912-c0687e6d6931)
![image](https://github.com/user-attachments/assets/d28da51e-45c3-4e37-beb8-3c70a7062383)
![image](https://github.com/user-attachments/assets/3276947d-838b-4f23-8aff-75624de0468d)





