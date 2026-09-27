<div align="center">

```text
                                     ███                                               ████ 
                                    ░░░                                               ░░███ 
 █████ ███ █████  ██████  ████████  ████   ██████  ████████  █████ ███ █████  ██████   ░███ 
░░███ ░███░░███  ███░░███░░███░░███░░███  ███░░███░░███░░███░░███ ░███░░███  ░░░░░███  ░███ 
 ░███ ░███ ░███ ░███████  ░███ ░███ ░███ ░███ ░░░  ░███ ░░░  ░███ ░███ ░███   ███████  ░███ 
 ░░███████████  ░███░░░   ░███ ░███ ░███ ░███  ███ ░███      ░░███████████   ███░░███  ░███ 
  ░░████░████   ░░██████  ░███████  █████░░██████  █████      ░░████░████   ░░████████ █████
   ░░░░ ░░░░     ░░░░░░   ░███░░░  ░░░░░  ░░░░░░  ░░░░░        ░░░░ ░░░░     ░░░░░░░░ ░░░░░ 
                          ░███                                                              
                          █████       wepicrwal - Web Vuln Scanner               
                         ░░░░░        
    -----------------------------------------------------
          Developed by: Md Zishan Raza
    -----------------------------------------------------
```
# --
```
<div align="center">

# 🛡️ WEPICRWAL
### **Advanced Web Port & Vulnerability Scanner**

[![Python Version](https://img.shields.io/badge/python-3.x-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Security: Authorized Use Only](https://img.shields.io/badge/Security-Authorized%20Only-red.svg)](#-legal-disclaimer)

*Developed with ❤️ by **Md Zishan Raza***

</div>

---

## 🚀 Overview

**Wepicrwal** ek powerful, lightweight aur fast Python-based security tool hai jo web applications aur servers ki security posture ko test karne ke liye design kiya gaya hai. Yeh automated TCP/UDP port scanning ke sath-sath common web vulnerabilities (jaise XSS, SQL Injection, aur CSRF) ko detect karta hai aur ek stunning, executive-ready HTML report generate karta hai.

---

## ✨ Key Features

*   🔍 **Comprehensive Port Scanning**: TCP aur UDP ports ki deep scanning karke open services identify karta hai aur unke risk levels (Safe, Moderate, Unsafe, Critical) batata hai.
*   ⚡ **Web Vulnerability Checks**:
    *   **Reflected XSS (Cross-Site Scripting)** via URL parameters & forms.
    *   **SQL Injection (SQLi)** error-based signature detection.
    *   **CSRF (Cross-Site Request Forgery)** protection token analysis on POST forms.
*   🔒 **Mandatory Authorization Gate**: Safety aur legal compliance ke liye built-in confirmation prompt jo unauthorized scanning ko rokta hai.
*   📊 **Stunning HTML Reports**: Dark-themed, modern, mobile-responsive HTML reports generate karta hai jisme complete summary cards aur detailed findings hoti hain.
*   🧵 **Multithreaded Performance**: Fast execution ke liye Python threading ka use karta hai.

---

## 🛠️ Manual Step-by-Step Installation & Setup

Apne local machine par is tool ko setup karne ke liye yeh steps follow karein:

### Step 1: Clone the Repository
Terminal ya Command Prompt open karein aur repository ko clone karein:
```bash
git clone [https://github.com/YOUR_USERNAME/wepicrwal.git](https://github.com/YOUR_USERNAME/wepicrwal.git)
cd wepicrwal
Step 2: Verify Python Installation
Check karein ki aapke system me Python 3 installed hai ya nahi:

Bash
python3 --version
Step 3: Install Required Dependencies
Required Python libraries (requests aur beautifulsoup4) ko install karein:

Bash
pip install requests beautifulsoup4
(Agar permission error aaye, toh --user flag use kar sakte hain: pip install --user requests beautifulsoup4)

Step 4: Make the Script Executable (Linux/macOS)
Script ko run karne ke liye execution permission dein:

Bash
chmod +x Wepicrwal.py
💻 Usage & Examples
Tool ko run karne ke liye target URL ya domain pass karein:

Bash
python3 Wepicrwal.py [http://example.com](http://example.com)
Advanced Options:
Sirf Port Scan karne ke liye:

Bash
python3 Wepicrwal.py target.com --ports-only
Sirf Vulnerability Scan karne ke liye:

Bash
python3 Wepicrwal.py [http://target.com](http://target.com) --vuln-only
Custom HTML Report Output Name dene ke liye:

Bash
python3 Wepicrwal.py [http://target.com](http://target.com) -o my_custom_report.html
📸 Preview / Workflow
Banner & Authorization: Tool start hote hi banner dikhayega aur target confirm karne ke liye legal disclaimer/authorization maangega.

Scanning: TCP/UDP ports aur web forms test honge.

Report Generation: Ek unique timestamped HTML file generate hogi (e.g., wepicrwal_target_com_20260328.html).

⚠️ Legal Disclaimer
Disclaimer: Wepicrwal ko sirf educational purposes aur authorized penetration testing / security audits ke liye banaya gaya hai. Bina explicit written permission ke kisi bhi system par port scanning ya vulnerability testing karna illegal hai aur isse severe legal consequences ho sakte hain. Developers is tool ke kisi bhi misuse ke zimmedaar nahi hain.

👤 Author
Md Zishan Raza

Feel free to contribute, report issues, or suggest new features!
