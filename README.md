# 🛡️ Cybersecurity Log Analysis Agent

## 📌 Project Overview

The **Cybersecurity Log Analysis Agent** is a rule-based **Agentic AI system** designed to autonomously analyze system and authentication logs, detect suspicious activities, and generate security alerts.
It simulates the real-world responsibilities of a **SOC Level-1 Analyst** by identifying brute-force login attempts and producing incident reports.

This project demonstrates **agentic behavior** through automated decision-making without human intervention.

---

## 🎯 Objectives

* Analyze system and authentication logs
* Detect suspicious activities such as multiple failed login attempts
* Identify potential brute-force attacks
* Generate alert summaries for SOC analysts
* Demonstrate agentic AI using rule-based logic

---

## 🧠 Agent Architecture

```
Log File
   ↓
Log Ingestion Module
   ↓
Detection Engine
   ↓
Decision Agent
   ↓
Alert Generator (Report)
```

### 🔹 Components

1. **Log Ingestion Module** – Reads raw log files
2. **Detection Engine** – Applies security rules
3. **Decision Agent** – Determines if an alert is required
4. **Alert Generator** – Produces SOC-ready reports

---

## ⚙️ Technologies Used

* Python 3
* Rule-based Agentic Logic
* Regular Expressions (Regex)
* Log File Analysis
* Report Generation

---

## 📂 Project Structure

```
cyber_log_agent/
│
├── agent.py        # Main agent code
├── logs.txt        # Sample log file
├── report.txt      # Generated alert report
└── README.md       # Project documentation
```

---

## 🧪 Detection Logic

The agent flags a **possible brute-force attack** when:

* Multiple failed login attempts
* From the same IP address
* Exceed a predefined threshold

```text
If failed login attempts from a single IP ≥ threshold
→ Generate HIGH severity alert
```

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/cybersecurity-log-analysis-agent.git
cd cybersecurity-log-analysis-agent
```

### 2️⃣ Run the Agent

```bash
python agent.py
```

### 3️⃣ View the Report

```bash
cat report.txt
```

---

## 📄 Sample Output

```
IP Address   : 192.168.1.10
Attempts     : 4
Threat       : Possible Brute Force Attack
Severity     : HIGH
```

---

## 🧠 Why This Is Agentic AI

* Operates autonomously
* Makes security decisions based on rules
* No human intervention during analysis
* Implements Detect → Decide → Act workflow

> Note: This project uses **rule-based agentic logic**, not machine learning.

---

## 👨‍💻 Use Case

* SOC Level-1 log triage
* Security monitoring practice
* Internship / academic project
* Cybersecurity portfolio demonstration

---

## 🔮 Future Enhancements

* Machine Learning–based anomaly detection
* LLM-powered reasoning agent
* Flask-based web dashboard
* Real-time log ingestion
* Email / Slack alert integration

---

## 📜 License

This project is for **educational and demonstration purposes only**.

---

## ✨ Author

**Space Dog**
Cybersecurity & Agentic AI Enthusiast

---

If you want, I can also:

* ✔️ Create a **GitHub description & tags**
* ✔️ Convert this into **PDF documentation**
* ✔️ Add **screenshots & diagrams**
* ✔️ Upgrade this to **LLM-based Agentic AI**

Just say the word 👍
