# 🐚 ReverseShellMaster

ReverseShellMaster is a **fully-featured, modular, and encrypted reverse shell framework** written in Python. It combines persistence, API integration, encryption, and modular extensibility into one tool — designed for ethical hacking, red teaming, and cybersecurity research.

---

## 🚀 Features

- 🔁 Persistent client with auto-reconnect
- 🔐 XOR-based encrypted communication
- 🖥️ System command execution
- 📁 File upload/download with Base64
- 🗺️ IP Geolocation using IPInfo API
- 🧪 File scan using VirusTotal API
- 🧠 System Information retrieval
- 📝 Command/session logging
- 🔧 Easily extensible with modular scripts
- 👾 Optional `/utils` tools like obfuscators and stubs

---

## 📦 Installation

git clone https://github.com/ABHAYKUMARTRIPATHI/ReverseShellMaster.git
cd ReverseShellMaster
pip install -r requirements.txt
python3 ReverseShellMaster.py

##📂 File Structure
ReverseShellMaster/
├── ReverseShellMaster.py       # Main powerful listener/client script
├── README.md                   # Project documentation
├── requirements.txt            # Python module requirements
├── reverse_shell.log           # Logs all shell commands & sessions
└── utils/
    ├── obfuscator.py           # Optional: Encode Python payloads
    └── client_stub.py          # Optional: Standalone client reverse connector

⚙️ Usage
	1.	Run the script:
 python3 ReverseShellMaster.py
 	2.	Provide:
	•	Listener IP and Port
	•	XOR Encryption Key
	•	Optional VirusTotal API
	•	Optional IPInfo Geolocation API
	3.	On successful connection, available commands:
	•	cd <dir> — Change working directory
	•	sysinfo — Get system info
	•	download <filepath> — Receive file from victim
	•	upload <filepath> <base64> — Send file to victim
	•	geolocate — Locate victim IP
	•	scan <filepath> — Scan file using VirusTotal
	•	Any other shell commands (e.g., ls, whoami, ipconfig)
	•	exit — Close session

 ⚠️ Disclaimer

This tool is for educational and authorized penetration testing purposes only.
Unauthorized use of this tool against targets without explicit permission is illegal.

**Abhay Kumar Tripathi**  
[GitHub](https://github.com/ABHAYKUMARTRIPATHI)  
[LinkedIn](https://www.linkedin.com/in/abhay-kumar-tripathi-54899b31a)  
[Instagram](https://www.instagram.com/abhaytripathi_46)"
