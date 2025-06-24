 HEAD
# nikto-scan-project
CEH project using Nikto to scan a legal web server for vulnerabilities. Includes findings, command used, and screenshot.

# Nikto Web Vulnerability Scan

This project uses **Nikto** to scan a legal test server for web vulnerabilities. It is part of my CEH practical learning.

---

## 🔧 Tool Used

- Nikto v2.5.0

---

## 📡 Target

- Website: http://testphp.vulnweb.com  
- IP: 44.228.249.3  
- Server: nginx/1.19.0

---

## 🧾 Command Used

```bash
nikto -h http://testphp.vulnweb.com -o scans/nikto-output.txt
>>>>>>> 7656b7c (Initial commit for Nikto scan project)
