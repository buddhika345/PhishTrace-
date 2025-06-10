🛡️ PhishTrace – Email Forensics & Phishing Detection Tool

A Python-based command-line tool that analyzes raw email headers, traces the sender’s IP and location, and checks for phishing indicators in email content. Designed for students, researchers, and cybersecurity enthusiasts interested in digital forensics and email threat analysis.

phishtrace project structure

├── email_analyzer.py   
├── README.md          


📌 Features

📥 **Raw Email Header Input**  
  Accepts full raw email headers pasted directly into the terminal.

🌍 **IP Geolocation Lookup**  
  Extracts IP address from the email header and uses the IP-API to get geolocation, ISP, and country information.

🚨 **Phishing Detection**  
  Analyzes the email content for common phishing keywords and suspicious phrases.

🔍 **Email Forensics**  
  Identifies failed SPF/DKIM/DMARC authentication results and flags inconsistencies.

⚙️ **Command-Line Interface**  
  Simple, interactive terminal interface for single-session analysis.

🧠 **AI Email Detection (Coming Soon)**  
  Planned integration with NLP models to detect AI-generated phishing emails.

 🎯 Use Cases

- Academic research on phishing and email security  
- Training tool for students learning email forensics  
- Quick phishing check for suspicious messages  
- Hands-on practice for ethical hacking and analysis

📸 Demo

$ python email_analyzer.py
Paste the full email header and body (end with '__END__'): 
[...your email content here...]

--- EMAIL ANALYSIS REPORT ---
Sender IP Address: 203.0.113.101
Location: United States
ISP: FakeBank ISP

SPF Result: softfail
DKIM Result: fail
DMARC Result: fail

⚠️ This email is likely a PHISHING attempt.



🔍 Tool developed by: pradeep B wijerathna
⚙️ Powered by: Python + IP-API + Regex Analysis  
📅 Year: 2025 | 🔒 Project: Email Forensics & Phishing Detection

