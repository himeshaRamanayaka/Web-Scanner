# Ultimate Web Pentest Script

🚀 **Automated Reconnaissance + Directory Brute-Force + CMS Fingerprinting + SQLi/Nikto Integration**

This project is designed for **cybersecurity students and pentesters** who want a **one-stop script** for web application penetration testing in labs or CTFs.  

⚠️ **For Educational Purposes Only. Do NOT run this against systems you do not own or have explicit permission to test.**

---

## ✨ Features
- 🔎 **Alive Check** – Verify target availability
- 📂 **Directory/File Brute Force** – With built-in paths or custom wordlists
- 🏗️ **CMS Fingerprinting** – WordPress, Joomla, Drupal, ASP.NET/IIS detection
- 🛡️ **Vulnerability Scans** – Runs **Nikto** (server misconfigs, files)  
- 💉 **SQL Injection Testing** – Integrates **sqlmap** automatically if parameterized pages found
- ⚡ **Multi-threading** – Faster brute force
- 🌍 **Cross-Platform** – Works on **Linux/Kali/Windows**

---

Installation
```bash
git clone https://github.com/<yourname>/ultimate-web-pentest.git
cd ultimate-web-pentest
chmod +x ultimate_web_pentest.py
Install dependencies:

pip install requests
sudo apt install nikto sqlmap

Usage
python3 ultimate_web_pentest.py <target_url> [optional_wordlist]

