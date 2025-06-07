# 🔐 Python Backdoor Project

This project demonstrates a simple backdoor connection between a target **Windows** machine and a host **Kali Linux** machine using Python's `socket` library.

> ⚠️ This project is for educational and ethical hacking purposes only. Do not use this for any unauthorized or malicious activities.

---

## 📁 Project Structure

- `backdoor.py`: The Python script to be compiled and deployed on the **target Windows machine**.
- `server.py`: The server-side script that runs on the **Kali Linux host machine**, listening for incoming connections.

---

## ⚙️ Requirements

### On Both Machines:

- Python 3.x
- Required Python libraries pre-installed

### On Windows (Target):

- [`pyinstaller`](https://pyinstaller.org/en/stable/) for compiling the backdoor:
  ```bash
  pip install pyinstaller

##🛠️ Setup Instructions
-pyinstaller backdoor.py --onefile --noconsole
