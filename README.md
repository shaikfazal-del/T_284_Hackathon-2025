# 🚀 DDoS Protection System for Cloud: Architecture and Tool

*Domain:* Cyber Security  
*Hackathon Team ID:* T 284  
*Team Name:* Cipher  

## 👥 Team Members
- *Sai Vignesh* (2303A53013)  
- *Fazal* (2303A53011)  
- *Abhiram* (2303A53026)  
- *Devadas* (2303A53014)  
- *Mahesh* (2303A54012)  

---

## 🧠 Project Overview

As organizations increasingly host their applications in the cloud, the threat of Distributed Denial-of-Service (DDoS) attacks grows ever more relevant. A DDoS attack overwhelms web infrastructure by flooding it with excessive traffic, rendering websites or services slow or entirely unavailable.

This project proposes a *DDoS Protection System* that includes:

- A *scalable cloud architecture* for resilience  
- An *automated detection and mitigation tool* built using *Python (Flask), with **HTML/CSS* for frontend  
- Smart analytics for traffic anomaly detection

---

## 🏗 Project Architecture

- *Frontend:* HTML/CSS  
- *Backend:* Python (Flask)  
- *Deployment Environment:* Cloud-based (supports horizontal scaling and high availability)  
- *Tool Features:*
  - Real-time traffic monitoring
  - Pattern-based anomaly detection
  - Automatic mitigation of suspicious traffic
  - Logging and alerting system for admins
  - Quick recovery module to restore services post-attack

---

## 🔍 Key DDoS Detection Indicators

- Unusual traffic volume from a single IP or IP range  
- Flood from users sharing the same behavioral profile  
- Sudden spike in requests to a specific page  
- Odd timing patterns in traffic (e.g., regular spikes every few minutes)

---

## 🛡 How It Works

1. *Monitor:* Constant monitoring of incoming traffic using Flask-based backend scripts.  
2. *Detect:* Machine logic identifies traffic anomalies using pre-defined heuristics.  
3. *Mitigate:* Automated IP blocking, rate-limiting, or service rerouting.  
4. *Recover:* Automatic fallback to alternative instances or services to ensure high availability.

---

## ⚙ Setup Instructions

1. Clone this repository:
   bash
   git clone https://github.com/your-repo-url/ddos-protection-system.git
   cd ddos-protection-system
   

2. Install required packages:
   bash
   pip install -r requirements.txt
   

3. Run the Flask application:
   bash
   python app.py
   

4. Access the web interface at http://localhost:5000

---

## 🌐 Final Thoughts

This project demonstrates a practical and scalable approach to combat DDoS attacks on cloud infrastructure, ensuring *high availability, **rapid recovery, and **proactive protection* for hosted services.

> Built with ❤ by *Team Cipher*
