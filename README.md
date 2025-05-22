# 🔍 Nmap Port Scanner (Python Script)

This Python script uses the `python-nmap` library to perform a detailed port and service scan on a specified target IP address. It automates `nmap` scanning, retrieves host information, and displays open ports and their states in a readable format.

## 📌 Features

- Scans a target IP using Nmap with options `-sV` (service version) and `-sC` (default scripts)
- Parses and prints:
  - Host IP and hostname
  - Host state (up/down)
  - Open ports and their states
  - Protocols in use

## 🛠 Requirements

- Python 3.x
- `nmap` installed on your system
- Python package `python-nmap`

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/nmap-port-scanner.git
   cd nmap-port-scanner

   
Install required Python package:
pip install python-nmap

Make sure nmap is installed on your system. You can check using:
nmap --version


## 🚀 Usage
Edit the script to change the target IP address:
target = "45.33.32.156"

Run the script:
python scanner.py


## 📄 Example Output
Host: 45.33.32.156 (example.com)
State: up
Protocol: tcp
Port: 22     State: open
Port: 80     State: open
...
⚠️ Disclaimer
This tool is intended for educational and authorized security testing only. Scanning networks or systems without permission is illegal and unethical.

