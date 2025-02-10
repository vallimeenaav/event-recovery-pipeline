# 🛠 Solution Demonstration in Google Colab (Python)

## 📌 Overview
This notebook demonstrates how **event failures (missing, duplicate, and incorrect events) are detected and corrected** in Linq’s event-driven system.

*Note:* While implemented in Python, a real-world setup would use:
- **Pub/Sub** for real-time event streaming.
- **Cloud Functions** for event validation and detection.
- **Dataflow** for anomaly detection and cross-system verification.
- **APIs (HubSpot, Stripe, Twilio)** for external validation.

For simplicity, this demonstration simulates these processes in Python instead of an actual cloud deployment.

---

## 🚀 Flow of the Solution
1. **Detect failures** – Identify missing, duplicate, or incorrectly processed events.
2. **Reprocess faulty events** – Use external checks and reconstruction methods.
3. **Publish corrected events** – Feed corrected events back into the system for accurate downstream processing.

---

## ⚡ How to Run the Notebook
1. Open in Google Colab
   - You can either download the .ipynb notebook from by repo or you can [click here](https://colab.research.google.com/drive/1yn_5yn90hIxsFxp3C5o2OV5rcicb06N5?usp=sharing) to open the notebook on your google colab, save a copy in drive and then work with it!

3. Run the cells sequentially  
   The notebook contains step-by-step explanations and code for:
   - **Simulating event failures** (missing, duplicate, incorrect events)
   - **Applying recovery techniques** (inference-based reprocessing)
   - **Validating corrections** before reinserting events into the pipeline

4. Modify parameters as needed 
   You can try changing the input values to test different failure scenarios.

---

## 🔍 Key Functionalities Demonstrated
- **Event failure detection:** Identifying missing, duplicate, and incorrect events.
- **Data validation & correction:** Ensuring consistency before reinserting events.
- **Simulated external API checks:** Mimicking CRM, payment, and communication API verification.
- **Final reprocessing pipeline:** Publishing recovered events for downstream use.

---

## 📌 References
- **[Full Approach Explanation](../approach/)**
- **[Write-Up: Trade-offs & Scalability](../write_up/)**


