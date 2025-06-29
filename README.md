# 🐍 Remote Access Trojan (RAT1) - GitHub-Based Command & Control

This project is a proof-of-concept Remote Access Trojan (RAT) framework written in Python, inspired by the techniques from *Black Hat Python* by Justin Seitz and Tim Arnold.

---

## 🎯 Project Objective

To build a modular Python-based RAT that connects to GitHub as a Command and Control (C2) server. The goal is to simulate how attackers can:
- Maintain remote access to a victim machine
- Dynamically update modules and tasks
- Collect data without direct connection

> 🚨 For educational and ethical hacking purposes only. Do not use this tool on unauthorized systems.

---

## 🧠 Key Features

- 🔁 **GitHub C2**: Uses a private GitHub repo as command & control
- 📂 **Modular Design**: Easily extendable with additional scripts
- 🧾 **Directory Listing Module**: Basic module to list victim’s current working directory
- 🔐 **Stealth**: Avoids direct connections between attacker and target
- 🧬 **Data Exfiltration**: Collects and uploads results to GitHub

---

## 🗂️ Directory Structure

