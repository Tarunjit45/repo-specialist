# 🔍 Repo Specialist — Terminal CLI for Trending GitHub Discovery

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![GitHub API](https://img.shields.io/badge/API-GitHub%20REST-181717?style=for-the-badge&logo=github&logoColor=white)](https://docs.github.com/en/rest)
[![CLI](https://img.shields.io/badge/Interface-Interactive%20Terminal-4EAA25?style=for-the-badge)](hunt.py)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

**Repo Specialist** is a command-line tool built in Python for developers, security researchers, and engineers to hunt and discover the latest trending open-source projects across **AI, Cybersecurity, Dark Web Intelligence, and Networking**.

---

## ✨ Features

* 🎯 **Curated Sector Intelligence:** Filter repositories specifically across:
  * 🤖 Artificial Intelligence & Machine Learning
  * 🔒 Cybersecurity & Penetration Testing
  * 🌐 Networking & Protocols
  * 🕵️ Dark Web Research & Threat Intelligence
* 🔐 **Secure Token Authentication:** Prompts for your GitHub Personal Access Token via hidden input (`getpass`) to bypass strict unauthenticated rate limits.
* 🚀 **One-Key Browser Launch:** Seamlessly open selected repositories directly in your default web browser using Python's `webbrowser` library.
* 📈 **Growth & Star Filtering:** Sorts by recency, total stars, and active development velocity.

---

## 📁 Repository Structure

```text
repo-specialist/
├── hunt.py             # Interactive CLI search & GitHub API discovery engine
├── LICENSE             # MIT License
└── README.md
```

---

## 🚀 Installation & Usage

### 1. Installation
Clone the repository:

```bash
git clone https://github.com/Tarunjit45/repo-specialist.git
cd repo-specialist

pip install requests
```

### 2. Run Repo Hunter
```bash
python hunt.py
```

1. Enter your GitHub token when prompted (input characters remain hidden for security).
2. Select your domain of interest from the interactive menu.
3. Review trending projects with descriptions, star counts, and direct links.
4. Select a project to instantly open it in your browser!

---

## 📄 License
This project is licensed under the [MIT License](LICENSE).
