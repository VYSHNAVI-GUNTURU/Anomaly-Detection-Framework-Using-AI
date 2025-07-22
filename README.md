# Anomaly-Detection-Framework-Using-AI

🧠 Anomaly Detection Framework Using AI
This project is an AI-powered anomaly detection framework that classifies system logs into known categories or flags them as anomalies using Google Gemini (Generative AI) and LangChain.

📌 Features
Classifies system log entries based on predefined labels
Detects anomalies or novel patterns in system behavior
Utilizes Google Gemini (gemini-1.5-flash) for natural language understanding
Easy-to-extend and context-aware using LangChain prompts

🏷️ Log Categories
The system attempts to classify log entries into the following categories:
HTTP Status
Critical Error
Security Alert
Error
System Notification
Resource Usage
User Action
Workflow Error
Depreciation Warning

If a log does not clearly match one of the above or indicates unusual behavior, it will be labeled as:
Anomaly Detected


<img width="542" height="139" alt="Screenshot 2025-07-22 204343" src="https://github.com/user-attachments/assets/0c33ca1e-588b-4e30-9343-7605cf231a19" />
