# ARP Spoofing Lab Tool (Educational Project)

This project is a simple ARP spoofing proof-of-concept built using Python and Scapy.
It is designed to help understand how ARP works and how ARP poisoning can affect communication in a local network.

---

## ⚠️ Disclaimer

This tool is for **educational use only** and should be used only in **authorized lab environments**.
Do NOT use this on networks you do not own or have permission to test.

---

## 📌 Features

* Discover MAC addresses using ARP requests
* Simulate ARP spoofing between a target and gateway
* Continuous packet sending to maintain spoofing
* Restore network state after stopping

---

## 🧠 What I Learned

* ARP protocol and IP ↔ MAC mapping
* ARP spoofing (ARP poisoning) concepts
* Packet crafting using Scapy
* Basics of network security and MITM scenarios
* Building CLI tools using argparse

---

## ⚙️ Requirements

```bash
pip install scapy
```

---

## 🚀 Usage

```bash
sudo python3 arp_spoofer.py --target <TARGET_IP> --gateway <GATEWAY_IP>
```

---

## 🛠️ Technologies Used

* Python 3
* Scapy

---

## 📈 Future Improvements

* ARP spoofing detection
* Logging system
* Network defense techniques

---

## 👨‍💻 Author

Mohammed duaij bin zaiman
