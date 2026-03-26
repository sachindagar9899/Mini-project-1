# 🔐 Packet-Based Malware Communication Detection

## 👨‍💻 Team Members

* Sachin Dagar (Leader)
* Tarun Thakur
* Dev Sharma

---

## 📌 Project Description

This project detects suspicious network activity by analyzing packet data.
It identifies IP addresses that are repeatedly contacted, which may indicate malware communication.

---

## 🎯 Objectives

* Capture network traffic using Wireshark
* Analyze packets using Python
* Detect repeated communication with specific IPs
* Log suspicious activity

---

## 🛠️ Tools & Technologies

* Python
* Wireshark
* Linux / Windows

---

## 📚 Libraries Used

* Scapy
* NumPy

---

## ⚙️ How It Works

1. Capture network packets using Wireshark
2. Save file as `.pcap`
3. Python script reads the file
4. Counts how many times each IP is contacted
5. If count exceeds threshold → marked as suspicious

---

## ▶️ How to Run

1. Install dependencies:
   pip install scapy numpy

2. Run the program:
   python main.py

---

## 📊 Output

* Displays suspicious IP addresses in terminal
* Generates `log.txt` file

---

## ⚠️ Note

This system detects suspicious patterns based on frequency. 
It does not guarantee that detected IPs are malicious.

---

## 🔮 Future Scope

* Real-time packet monitoring
* Machine learning-based detection
* Integration with firewall systems

---

## 📁 Project Structure

malware-detection-project/
│
├── main.py
├── sample.pcap
├── log.txt
├── README.md

---

## ✅ Conclusion

This project demonstrates how network packet analysis can be used to detect suspicious communication patterns.
By analyzing repeated connections to specific IP addresses, the system helps identify potential malware activity. 
Although it does not guarantee exact malware detection, it provides a strong foundation for building advanced cybersecurity tools.
This approach can be further improved using real-time monitoring and machine learning techniques.
