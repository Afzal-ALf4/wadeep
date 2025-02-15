# wadeep
Uncover hidden endpoints, admin panels &amp; authentication portals with military-grade precision. "The web archivist's Swiss Army knife" – A must-have for pentesters &amp; bug bounty hunters."
# 🔍 WaDeep - Web Reconnaissance Toolkit

# 🔍 WaDeep - Advanced Web Reconnaissance Toolkit

[![Python 3.8+](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)](https://python.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-red)](LICENSE)
![GitHub Release](https://img.shields.io/github/release/AfzalShahDev/WaDeep)

Professional-grade tool for discovering admin interfaces, login portals, and sensitive endpoints.

## Features 🌟
- 🕵️ Wayback Machine Integration
- 🔑 Admin/Login Page Detection
- 🔍 Parameter Analysis
- 💥 Directory Bruteforce
- 📁 Multi-domain Support

## Installation ⚡
```bash
git clone https://github.com/AfzalShahDev/WaDeep.git
cd WaDeep
pip install -r requirements.txt
Usage 🛠️
Basic Scan:

bash
Copy
python wadeep.py -u example.com -w wordlists/full.txt
Advanced Options:

bash
Copy
# Multi-threaded scan with custom timeout
python wadeep.py -l targets.txt -w wordlists/critical.txt -t 30
Wordlists 📚
admin.txt - 250+ admin paths

login.txt - 180+ auth endpoints

full.txt - 1500+ comprehensive list

Output Samples 📂
Copy
example.com_wayback.txt
example.com_admin_logins.txt
example.com_bruteforce.txt
Contribution 🤝
Fork the repository

Create feature branch

Submit PR with changes

License 📜
MIT Licensed - See LICENSE

🔗 Created by: Afzal Shah
💬 Support: Open Issue
