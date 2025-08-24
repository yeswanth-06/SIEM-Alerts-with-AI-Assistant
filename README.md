# SIEM-Alerts-with-AI-Assistant
# AI-Powered SIEM Alert Triage Assistant

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Machine Learning](https://img.shields.io/badge/ML-LightGBM-orange)
![Security](https://img.shields.io/badge/Security-SIEM-red)
![Email Integration](https://img.shields.io/badge/Email-SMTP-green)

An advanced machine learning system that automatically classifies and prioritizes security alerts from SIEM systems, reducing alert fatigue and improving incident response times.

## 🚀 Features

- **AI-Powered Classification**: LightGBM model classifies alerts into TruePositive, FalsePositive, and BenignPositive
- **Email Notifications**: Automated alerts for high-confidence security incidents
- **Daily Reports**: Comprehensive summary reports for security teams
- **Real-time Processing**: Millisecond response times for incoming alerts
- **Secure Configuration**: Protected email credentials and secure data handling

## 📊 Model Performance

- **Macro F1 Score**: 84.7%
- **Precision**: 87% (weighted average)
- **Recall**: 86% (weighted average)
- **Accuracy**: 86% on test dataset

## 🛠️ Installation

```bash
git clone https://github.com/yourusername/siem-triage-assistant.git
cd siem-triage-assistant
pip install -r requirements.txt
