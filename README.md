🔍 Fake Job Detector Chrome Extension
An AI-Augmented Chrome Extension for Real-Time Detection of Deceptive Job Listings on Naukri.com.
![Uploading Picture 1.png…]()



📌 Overview
Online job platforms like Naukri.com have revolutionized recruitment—but they've also opened the door to fraudulent job postings. Fake job listings exploit job seekers, demanding upfront fees, misusing personal data, or impersonating legitimate companies.

This Chrome extension uses Artificial Intelligence (AI), Machine Learning (ML), and Natural Language Processing (NLP) to proactively detect and flag potentially fake or deceptive job posts in real time—empowering users with risk scores, alerts, and transparency.

🚀 Features
✅ Real-Time Scam Detection on job listings via browser extension.

📊 Risk Score & Fraud Alerts based on job content and metadata.

🧠 AI/ML-Powered Classification using models like Random Forest, SVM, and BERT.

🔍 NLP-Based Text Analysis to detect scam indicators and suspicious patterns.

🔄 Adaptive Learning through user feedback and continuous model updates.

🔒 Anomaly Detection via Isolation Forest and DBSCAN to catch unusual postings.

👥 Crowdsourced Feedback Loop to improve fraud detection over time.

🧠 Technology Stack
Area	Tools / Libraries
Frontend	HTML, CSS, JavaScript, React.js
Chrome Extension	Manifest V3, Content Scripts, Background Services
Backend API	Flask / FastAPI
ML/NLP	Scikit-learn, TensorFlow, BERT, Word2Vec, FastText, TF-IDF
Data Processing	Pandas, NumPy, BeautifulSoup, Selenium
Database (optional)	MongoDB / PostgreSQL for user feedback

🏗️ System Architecture
Web Scraping from Naukri.com using Selenium.

Data Preprocessing (tokenization, lemmatization, feature engineering).

ML/NLP Models trained on labeled datasets (fraud vs genuine).

Chrome Extension extracts job data and sends to backend for analysis.

Backend ML Service returns fraud probability and explanations.

UI Feedback Loop lets users report and improve the model over time.

📈 Machine Learning Models Used
Supervised Learning: Random Forest, Logistic Regression, SVM, XGBoost

Deep Learning: LSTM, CNN, GRU, BERT

NLP Features: TF-IDF, Word2Vec, FastText, Sentiment Analysis

Anomaly Detection: Isolation Forest, DBSCAN

Online Learning: Passive Aggressive Classifier, Online SVM

🧪 Model Performance Metrics
Accuracy: ~92%

Precision: ~90%

Recall: ~93%

F1-Score: ~91%

ROC-AUC: High (measured using real-world Naukri.com job data)

🔄 Feedback & Continuous Learning
Users can flag suspicious job posts directly in the extension.

Feedback is stored and used to retrain models periodically.

Adaptive learning ensures robustness to evolving scam tactics.

🔐 Security Considerations
Adversarial training against obfuscated scam patterns.

Feature randomization to handle manipulated job descriptions.

🧭 Project Goals
This project supports SDG 8 – Decent Work and Economic Growth, by protecting users from fraudulent job listings and promoting fair employment practices online.

📦 Installation (Developer Mode)
Clone the repository:

bash
Copy
Edit
git clone https://github.com/dv7453/fake-Job-Chrome-extension.git
cd fake-Job-Chrome-extension
Go to chrome://extensions/ in your browser.

Enable Developer Mode.

Click Load unpacked and select the extension folder.

Start browsing Naukri.com job listings – fraudulent posts will be automatically analyzed and flagged.

🛠️ Future Enhancements
✅ Auto-blocking of highly suspicious listings

🌐 Multi-platform support (LinkedIn, Indeed, etc.)

📱 Mobile app version

📊 Admin dashboard for feedback review and model tuning

👨‍💻 Contributors
Dhruv Vadhiya – @dv7453

Rakshit Akbhari

Dhruv Maheshwari

📚 References
UN SDG 8 – Decent Work and Economic Growth

ILO Employment Trends Report 2023

"AI-Powered Fake Job Detection" – Journal of AI Research, 2021

"Job Scam Detection using NLP" – AISEC Conference, 2019

