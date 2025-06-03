# 🎣Task 2: Phishing Email Analysis - Case Study

This repository contains a sample phishing email and a detailed analysis to demonstrate email threat detection and analysis techniques.

## 🔍 Objective
To analyze a legitimate-looking phishing email using both manual inspection and automated tools to understand its malicious intent, techniques, and potential impact.

## 📨 Sample Email
- **Subject**: Immediate Action Required: Verify Your Account
- **Sender**: it-support@secure-notices.com
- **Body**: Urges the recipient to click a link to verify credentials under threat of account suspension.
- **Link**: Redirects to a fake login page (`https://secure-notices.com/verify-account`).

## 🛠 Tools Used
### Offline (Linux):
- `emlAnalyzer`, `oletools`, `exiftool`, `strings`, `tcpdump`, `Wireshark`

### Online:
- [VirusTotal](https://virustotal.com)
- [Any.Run](https://any.run)
- [urlscan.io](https://urlscan.io)
- [PhishTool](https://phishtool.com)

## 🧠 Key Findings
- Spoofed domain impersonating IT support
- URL leads to phishing site collecting credentials
- No SPF/DKIM validation passed
- Link hosted on recently registered domain

## 🚨 Conclusion
Always verify email headers, scan suspicious links, and educate users on recognizing social engineering tactics.

---

📁 **Refer to the txt [TXT Report](./Email_report.txt)** for detailed analysis.
