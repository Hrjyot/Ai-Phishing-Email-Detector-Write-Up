<div align="center">
  <img width="480" height="480" alt="AI Phishing Email Detector Logo" src="<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/69efe860-319e-489c-9aec-978f3dabf9b5"/>
/>
" />
  <h1>AI Phishing Email Detector</h1>
  <p style="font-size: 16px; color: #333;">
    A machine learning-powered phishing detection system built with a locally hosted <a href="https://ollama.ai">DeepSeek LLM</a> on Ollama. Utilizes NLP to analyze email content, sender behavior, and metadata, achieving <strong>over 95% accuracy</strong> in real-time phishing detection. Privacy-focused, lightweight, and integrated with Postfix for secure email processing.
  </p>
  <p>
    <a href="https://www.python.org/downloads/"><img src="https://img.shields.io/badge/Python-3.8+-blue.svg" alt="Python 3.8+"></a>
    <a href="https://ollama.ai"><img src="https://img.shields.io/badge/Ollama-DeepSeek-orange.svg" alt="Ollama DeepSeek"></a>
  </p>
</div>

## 📋 Overview
This project develops an AI-powered phishing email detection system using a locally hosted DeepSeek Large Language Model (LLM) on the Ollama framework. Leveraging machine learning and natural language processing (NLP), the system identifies malicious patterns in emails with high accuracy while ensuring privacy through local processing.

## 🎯 Objectives
- Build a robust system for real-time phishing email detection.
- Utilize NLP to analyze email content, sender behavior, and metadata.
- Achieve >95% detection accuracy with minimal false positives.
- Deploy locally using DeepSeek on Ollama for secure, offline processing.

## 🛠️ Methodology
### Environment Setup
- Installed Ollama on a local machine to host the DeepSeek LLM, ensuring a privacy-preserving setup without external API dependencies.
- Configured the environment to handle large-scale email datasets efficiently.

### Data Preparation
- Curated real-world email datasets containing both legitimate and phishing emails.
- Preprocessed data to extract features like email content, sender information, and metadata (e.g., headers, links, attachments).

### Model Development
- Employed DeepSeek’s NLP capabilities to identify linguistic and behavioral patterns indicative of phishing.
- Fine-tuned the model on the email dataset to classify emails as malicious or benign using transfer learning.
- Integrated rule-based checks (e.g., suspicious sender domains or URLs) to complement LLM predictions.

### Model Evaluation
- Evaluated performance using precision, recall, and F1-score metrics.
- Achieved a detection rate exceeding 95% on test datasets with minimal false positives.

### Implementation
- Developed a real-time detection pipeline to process incoming emails and flag phishing attempts.
- Integrated with Postfix mail server for secure, local email processing.

<div style="background-color: #f0f8ff; padding: 10px; border-radius: 5px; text-align: center;">
  <strong>Privacy-First Design!</strong> Runs entirely offline with Ollama for maximum security.
</div>

## 📊 Results
| Metric    | Score  |
|-----------|--------|
| Precision | 96%    |
| Recall    | 95%    |
| F1-Score  | 95.5%  |

- Detected over 95% of phishing emails in test scenarios.
- Minimized false positives to ensure legitimate emails are rarely flagged.
- Local hosting via Ollama and DeepSeek ensures low latency and high privacy.

## 🛡️ Challenges and Solutions
- **Challenge**: Limited computational resources for local processing.  
  **Solution**: Optimized preprocessing and inference for consumer-grade hardware.
- **Challenge**: Balancing accuracy and false positives.  
  **Solution**: Combined LLM-based NLP with rule-based checks for enhanced precision.

## 🔮 Future Improvements
- Implement active learning for continuous model improvement.
- Enhance metadata analysis with attachment scanning.
- Explore integration with email clients for automated notifications.

## 📜 Conclusion
The AI Phishing Email Detector combines a locally hosted DeepSeek LLM on Ollama with NLP and machine learning to deliver a scalable, secure solution for real-time phishing detection. With over 95% accuracy and a privacy-first approach, it’s ideal for cybersecurity applications.

<div style="background-color: #e6f3ff; padding: 15px; border-radius: 5px; text-align: center;">
  <strong>Star this repo</strong> if you find it useful! 🌟
</div>
