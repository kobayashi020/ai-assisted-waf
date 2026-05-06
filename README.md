# AI-Assisted WAF (Web Application Firewall)

An AI-assisted Web Application Firewall (WAF) for detecting and classifying web application attacks such as SQL Injection and Cross-Site Scripting (XSS) using machine learning.

This project explores how machine learning models can be applied to HTTP request analysis for intrusion detection, with a focus on interpretability and practical security insights rather than production deployment.

---

## 🎯 Objective

The goal of this project is to:

- Detect malicious HTTP requests (e.g., SQLi, XSS)
- Explore machine learning approaches for web attack detection
- Evaluate feature importance and model interpretability
- Demonstrate how AI can assist traditional WAF systems

---

## 📊 Dataset

This project uses the CSIC 2010 HTTP dataset provided via:

https://github.com/msudol/Web-Application-Attack-Datasets

- License: GNU General Public License v3.0 (GPL-3.0)
- Note: This is a processed version of the original CSIC dataset.

---

## ⚠️ Remarks

- The dataset is relatively old and does not fully reflect modern web attack patterns.
- This project is intended for educational and research purposes.
- It demonstrates anomaly detection techniques rather than a production-ready security system.

---

## 🧠 Focus Areas

- HTTP request feature engineering
- Machine learning-based anomaly detection
- Model evaluation (precision, recall, F1-score)
- Explainability (feature importance / interpretability analysis)

---

## 🛠️ Future Improvements

- Integration of modern datasets (e.g., CIC-IDS2017)
- Real-time request inspection API
- Explainable AI integration (e.g., SHAP-based analysis)
- Lightweight WAF deployment prototype
