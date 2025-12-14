# 🎣 Phishing Email Investigation

## 📌 Incident Summary
A suspicious email was reported by a user claiming to be from a trusted organization and requesting credential verification.

## 🕵️ Detection
- User-reported suspicious email
- Email contained urgent language and a suspicious link

## 🔍 Analysis
- Reviewed sender address and email headers
- Identified spoofed domain impersonating a legitimate service
- Analyzed embedded URL leading to a fake login page

## 🚩 Indicators of Compromise (IOCs)
- Malicious URL
- Spoofed sender domain

## 🧠 MITRE ATT&CK
- T1566 – Phishing

## 🛠️ Response Actions
- Blocked malicious domain and URL
- Removed email from affected mailbox
- Notified users of phishing attempt

## ✅ Outcome
No credentials were compromised.

## 📝 Lessons Learned
- User awareness is critical for early detection
- Email filtering rules help reduce phishing risk
