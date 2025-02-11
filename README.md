# 🚀 EVENT RECOVERY & REPROCESSING IN A REAL-TIME SYSTEM

## 📌 Overview
This repository provides a solution for a **scalable event recovery pipeline** to detect, back-calculate, and correct **missing, duplicate, and incorrectly processed events** in an event-driven system. It ensures real-time event validation, deduplication, and anomaly detection **without relying on historical logs or a traditional database**.

## 🛠 Problem Statement
Linq's platform operates in an event-driven architecture, where actions like **business card scans, CRM syncs, AI-powered follow-ups, and sales tracking** rely on real-time event processing. However, event failures—such as **missed, duplicated, or incorrectly processed events**—can disrupt business operations and customer experience. [these details are assumed]

### 🎯 Solution Overview
- ✅ Detects & recovers missing events using event ID gaps, downstream validation, and anomaly detection.
- 🔄 Prevents duplicate processing with idempotency keys, deduplication checks, and dead-letter queues.
- 🔧 Corrects incorrectly processed events through cross-system validation, real-time recalculations, and API lookups.
- ⚡ Scalable architecture using serverless functions, streaming tools, and parallel processing for high-volume events.

To provide a **quick and easy visual representation** of the event recovery pipeline that I've proposed, I created two flowcharts to outline the key steps involved in detecting and correcting event failures.

<p align="center">
<img width="736" alt="Screenshot 2025-02-10 at 6 27 18 PM" src="https://github.com/user-attachments/assets/a1d03979-4a6a-4c5e-ae7d-12ba853778ec" />
Flowchart 1: The initial event validation and processing pipeline
</p>

<p align="center">
<img width="1084" alt="Screenshot 2025-02-10 at 6 28 06 PM" src="https://github.com/user-attachments/assets/17f7c8a2-2196-4b50-bc6d-c4e36da72063" />
Flowchart 2: The failure recovery mechanism, handling missing, duplicate, and incorrectly processed events
</p>

[Click here to access the flowcharts on Lucid Charts](https://lucid.app/publicSegments/view/7502e54a-e14f-4345-9a0b-6e8e55cada7d/image.png)

## 📂 Repository Structure
```plaintext
📦 event-recovery-pipeline/
│── README.md                  # Main repository overview (this file)
│── approach/          
│   ├── README.md              
│── write_up/
│   ├── README.md              
│── solution/
│   ├── Solution_Demonstration_in_Python.ipynb  
│   ├── README.md              
│── .gitignore                 
│── LICENSE (optional)         
```

## ⚡ Quick Start
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/<your-username>/event-recovery-pipeline.git
cd event-recovery-pipeline
```

### 2️⃣ Run the Solution
Open the Google Colab Notebook and execute:
```bash
Open solution/event_reprocessing.ipynb in Google Colab and run all cells.
```

## 📌 Quick Access
1. **[Approach](approach/README.md)** → Detailed methodology and strategies
2. **[Write-Up](write_up/README.md)** → Summary, trade-offs, scalability, and alternative approaches  
3. **[Solution](solution/README.md)** → Code snippets demonstrating my approach 

