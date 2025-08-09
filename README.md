# AI-Powered-Phishing-Simulation-on-Cloned-UPI-Interfaces-for-Financial-Fraud-Analysis
AI-Powered Phishing Simulation on Cloned UPI Interfaces
This project presents a controlled phishing simulation replicating the PhonePe UPI payment interface to study interface mimicry, social engineering tactics, and vulnerabilities in digital payment systems. It was developed under the guidance of the Digital Forensics Division, CFSL Hyderabad as part of a research initiative in cybersecurity awareness and education.

📌 Overview
The simulation demonstrates how attackers exploit visual trust and UI similarity to deceive users into sharing sensitive information. Built with Python (Flask), it integrates real-time credential logging, live desktop alerts, and public hosting via Ngrok for demonstration in secure environments.

Purpose:

Analyze phishing workflows in UPI ecosystems.

Study user susceptibility to interface cloning.

Propose countermeasures like MFA, AI-driven detection, and awareness programs.

🛠 Technologies
Backend: Python, Flask

Frontend: HTML, CSS

Monitoring: Watchdog (file monitoring), Plyer (desktop notifications)

Hosting: Ngrok

Tools: VS Code, Chrome

📊 Key Features
Realistic clone of PhonePe login, OTP, and payment pages.

Dummy data capture (mobile numbers, OTPs, UPI PINs) in real time.

Instant desktop notifications upon data capture.

Secure public access via HTTPS tunnel for ethical demonstrations.

📖 Research Context & Findings
This project was conducted to explore how minimal technical resources, combined with psychological manipulation, can result in high-impact phishing attacks.

Research Insights:

UI Deception Effectiveness – Users often overlook minor inconsistencies (domain, SSL, layout) when presented with a familiar interface.

Human Factor Vulnerability – Even with OTP-based security, users can be socially engineered into disclosing sensitive credentials.

Attack Accessibility – The tools and frameworks required for such attacks are lightweight, open-source, and easily deployable, increasing risk.

Preventive Measures –

Multi-factor authentication with biometric verification.

AI-driven real-time phishing detection in browsers and payment apps.

Large-scale awareness training focusing on social engineering threats.

Research Impact:
This simulation bridges theory and practice by providing a safe, hands-on platform for students, researchers, and security practitioners to study real-world attack vectors without endangering actual systems or users.

⚠️ Disclaimer
This project is developed strictly for educational and research purposes. No real user data or live financial transactions are involved. Misuse of this code for malicious intent is illegal and against ethical guidelines.
