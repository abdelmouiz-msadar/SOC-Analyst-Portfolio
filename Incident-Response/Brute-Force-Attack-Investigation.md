# 🚨 Brute Force Attack Investigation

## 📌 Incident Summary
Multiple failed login attempts were detected on a Windows host, indicating a potential brute-force attack targeting user accounts.

## 🕵️ Detection
- SIEM alert triggered due to repeated failed authentication attempts
- Alert severity: Medium

## 🔍 Analysis
- Reviewed Windows Security Event Logs (Event ID 4625)
- Identified repeated login failures from a single source IP
- Observed automated attack behavior

## 🧠 MITRE ATT&CK
- T1110 – Brute Force

## 🛠️ Response Actions
- Blocked malicious IP address
- Verified account lockout policies
- Escalated incident for continued monitoring

## ✅ Outcome
No successful account compromise detected.

## 📝 Lessons Learned
- Strong password and lockout policies reduce risk
- Early alerting helps prevent account compromise
