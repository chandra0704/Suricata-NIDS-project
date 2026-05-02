# Suricata-NIDS-project
Network Intrusion Detection System using Suricata on Kali Linux
# 🔐 Network Intrusion Detection System (NIDS) using Suricata

## 📌 Overview

This project demonstrates the setup and implementation of a Network Intrusion Detection System using Suricata on Kali Linux.

## 🛠 Tools Used

* Suricata IDS
* Kali Linux
* jq (for JSON parsing)

## ⚙️ Features

* Real-time traffic monitoring
* Custom rule creation (ICMP detection)
* Alert logging and analysis
* JSON-based visualization

## 📊 Results

* Total Alerts: 8
* Unique Signatures: 2
* Protocol: TCP
* Port: 80 (HTTP)

## 🚀 Setup Steps

```bash
sudo apt update
sudo apt install suricata -y
sudo suricata-update
sudo suricata -c /etc/suricata/suricata.yaml -i eth0
``` 
```

## 📌 Conclusion

This project successfully demonstrates detection of network activity using Suricata with real-time alert monitoring.
