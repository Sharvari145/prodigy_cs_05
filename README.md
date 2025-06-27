# prodigy_cs_05
📡 Packet Sniffer using Scapy (Python)

This project is a simple **packet sniffer tool** built with Python and the Scapy library. It captures network packets in real-time, extracts essential information such as source and destination IP addresses, protocol types (TCP/UDP), and optionally shows the first 50 bytes of the payload.

 🔍 Features:

* Captures up to 20 packets using `scapy.sniff()`
* Displays:

  * Source IP
  * Destination IP
  * Protocol type (TCP, UDP, or other)
  * Raw payload (first 50 bytes, if available)
* Differentiates protocol types dynamically during runtime
* Neatly formats the output for easy analysis

🛠️ Technologies Used:

* Python 3.13
* Scapy library
📦 How to Run:

bash
pip install scapy
python task5.py

 🖼️ Sample Output:

* Shows source/destination IPs, protocol info, and payload
* Segregates each packet visually with dashed lines for readability

