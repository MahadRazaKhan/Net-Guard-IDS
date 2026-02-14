# NetGuard Security System

**NetGuard Security System** is a real-time network monitoring and cybersecurity tool built with **Node.js** and **Express.js**. It captures live network traffic, analyzes packets, detects potential threats, and provides an interactive dashboard for monitoring and alert management. This project is suitable for network security enthusiasts, penetration testers, and cybersecurity learners.

---

## Features

- Real-time **network traffic capture** using **Wireshark / Tshark**  
- Live **WebSocket-based dashboard** for packets and security alerts  
- **Threat detection**, including:
  - DDoS Attacks
  - Port Scanning
  - Large Data Transfers
  - ICMP Floods
  - SQL Injection & XSS attempts
- Detailed **analytics** and **protocol statistics** (TCP, UDP, HTTP, ICMP, DNS, Others)  
- Top source IP tracking and bandwidth monitoring  
- **Alert management**: mark as read, resolve, clear old alerts  
- **REST API endpoints** for integration with other tools or dashboards  

---

## Cybersecurity Concepts Implemented

- **Intrusion Detection System (IDS)** concepts  
- Real-time **packet inspection** and **protocol analysis**  
- **Traffic anomaly detection**  
- **Threat classification** based on severity  
- **Network monitoring** and alerting  
- **Time-series analytics** for traffic and alerts  

---

## Technologies & Tools Used

- **Backend:** Node.js, Express.js  
- **WebSocket:** Real-time client-server communication  
- **Network Capture:** Wireshark / Tshark  
- **Frontend (optional for dashboard):** HTML, CSS, JavaScript  
- **Data Structures:** Arrays, Maps for analytics  
- **OS Compatibility:** Windows, Linux, MacOS  

---

## Protocols Monitored

- **TCP** (Transmission Control Protocol)  
- **UDP** (User Datagram Protocol)  
- **HTTP / HTTPS**  
- **ICMP** (Ping / Echo Requests)  
- **DNS** (Domain Name System)  
- **Other Custom Protocols**  

---
## Run

- node index.js
- localhost:3000

---

# Install dependencies
- npm install

# Start server
node index.js
