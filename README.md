# Honeyscan - Port Scanner

## Overview
Honeyscan is a powerful and efficient **port scanner** designed for cybersecurity professionals and ethical hackers. It helps identify open ports, detect vulnerabilities, and analyze network security with speed and accuracy.

## Features
- Fast and lightweight scanning
- Supports **TCP & UDP** scanning
- Scans **specific ports** or a **range of ports**
- Detects open and closed ports
- Customizable timeout settings
- User-friendly CLI interface

## Installation
### Prerequisites
Ensure you have **Python 3.x** installed. You can download it from [Python.org](https://www.python.org/downloads/).

### Clone the Repository
```bash
git clone https://github.com/imrootuser/honeyscan.git
cd honeyscan
```

### Install Required Dependencies
```bash
pip install -r requirements.txt
```

## Usage
### Basic Scan
```bash
python honeyscan.py -t <TARGET_IP> -p 1-65535
```
Example:
```bash
python honeyscan.py -t 192.168.1.1 -p 22,80,443
```

### Scan with Custom Timeout
```bash
python honeyscan.py -t <TARGET_IP> -p 1-1000 --timeout 2
```

### UDP Scan Mode
```bash
python honeyscan.py -t <TARGET_IP> -p 53,123 --udp
```

## Example Output
```
Scanning 192.168.1.1...
Port 22 (SSH) is open
Port 80 (HTTP) is open
Port 443 (HTTPS) is open
Scan completed in 4.75 seconds
```

## Contribution
Contributions are welcome! Feel free to open an issue or submit a pull request.

## Disclaimer
This tool is intended for **educational and authorized security testing purposes only**. Unauthorized scanning of networks is illegal. Use responsibly.

## License
This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---
**Author:** Root User  
**GitHub:** [imrootuser](https://github.com/imrootuser)
