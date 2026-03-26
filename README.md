# 🔍 Python Port Scanner

A simple network scanner built in Python that identifies open ports on a target system using TCP connections.

---

## 🚀 Features

* Scans a range of ports on a given IP address
* Detects open ports using TCP connection attempts
* Displays results in a clean and readable format
* Basic service identification for common ports

---

## 🧠 What I Learned

* How networking works at a basic level (IP addresses & ports)
* How to use Python's `socket` library for network communication
* Difference between open and closed ports
* Importance of timeouts in network scanning
* Writing clean and readable output

---

## ⚠️ Challenges I Faced

* Understanding how port scanning actually works instead of just copying code
* Learning how `socket` connections behave when ports are closed
* Dealing with slow scanning due to timeout settings
* Confusion between `connect()` and `connect_ex()`
* Setting up Python and development environment for the first time

---

## 🛠️ How It Works

1. Takes an IP address as input from the user
2. Iterates through a range of ports
3. Attempts a TCP connection to each port
4. If the connection is successful, the port is marked as open
5. Displays the results

---

## ▶️ How to Run

```bash
python scanner.py
```

Then enter:

```
127.0.0.1
```

---

## 📌 Example Output

```
[OPEN] Port 135 (RPC)
```

---

## ⚠️ Disclaimer

This tool is for educational purposes only. Only scan systems you own or have permission to test.

---

## 📈 Future Improvements

* Add multithreading for faster scanning
* Expand service detection
* Allow custom port ranges
* Improve output formatting

---
## 👤 Author

Muhammad Bilal  
Aspiring Cybersecurity & Networking student  
