# 🔍 WaDeep - Web Reconnaissance Toolkit

[![Python 3.8+](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)](https://python.org)  
[![License: MIT](https://img.shields.io/badge/License-MIT-red)](LICENSE)  
![GitHub Release](https://img.shields.io/github/release/AfzalShahDev/WaDeep)  

**Uncover hidden endpoints, admin panels & authentication portals with military-grade precision.**  
*"The web archivist's Swiss Army knife" – A must-have for pentesters & bug bounty hunters."*  

---

## 🌟 Features  
- 🕵️ **Wayback Machine Integration** - Retrieve historical URLs  
- 🔑 **Admin/Login Page Detection** - Find hidden authentication portals  
- 🔍 **Parameter Analysis** - Detect URLs with input fields  
- 💥 **Directory Bruteforce** - 1500+ curated paths  
- 📁 **Multi-domain Support** - Scan multiple targets at once  

---

# ⚡ Installation
bash
Copy
git clone https://github.com/AfzalShahDev/WaDeep.git
cd WaDeep
pip install -r requirements.txt

# 🛠️ Usage
✅ Basic Scan
bash
Copy
python wadeep.py -u example.com -w wordlists/full.txt

# 🚀 Advanced Options
bash
Copy
# Multi-threaded scan with custom timeout
python wadeep.py -l targets.txt -w wordlists/critical.txt -t 30
