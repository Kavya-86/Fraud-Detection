# Fraud-Detection
🛡 AI Model for Flagging Suspicious Transactions

Hackathon: National CyberShield Hackathon 2025
Team: Bug Busters
Institute: Oriental Institute of Science and Technology

📌 Problem Statement

Financial fraud is becoming increasingly sophisticated. Traditional detection methods fail against Phantom Chain Laundering, where:

Fraudsters create chains of synthetic accounts (digital twins).

Each account mimics only one behavioral trait (amounts, vendors, timing, frequency).

Individually accounts appear safe, but together they reconstruct a victim’s profile, making laundering nearly invisible.

Our solution builds an AI-powered fraud detection system capable of identifying these fragmented laundering patterns in real-time.

🎯 Key Features

Fragmented Identity Detection → Detects split behavioral mirroring across multiple accounts.

Graph + Temporal Analysis → Uses graph embeddings and temporal anomaly detection for hidden patterns.

Cross-Dimensional Checks → Flags inconsistencies between vendors, timing, and frequency.

Interactive Dashboard → Real-time fraud visualization with graphs, timelines, and filters.

Automated Reports → Export flagged transactions to PDF for investigators.

🛠 Tech Stack
Languages & Frameworks

Python → AI/ML modeling (TensorFlow / PyTorch)

Java → Backend APIs (secure & scalable)

SQL → Transaction data storage & queries

JavaScript (Vanilla + Chart.js + vis-network) → Web dashboard visualization

jsPDF + AutoTable → Report generation

Infrastructure

Google Colab → AI model prototyping

OneCompiler (HTML) → Web app demo hosting

AWS / Azure → Cloud scalability

GPUs / TPUs → High-performance model training

📊 Dashboard Features

Overview Panel → Metrics (accounts, transactions, fraud detected).

Fraud Network Graph → Interactive graph of suspicious flows.

Suspicious Cases Tab → Auto-filter for risk ≥40%.

Filters → Date, transaction type, amount range, risk level.

Simulation Mode → Play transaction flows in real-time.

Export Reports → Download filtered fraud cases as PDF.

📂 Project Structure
📦 Suspicious_Fraud_Detection
 ┣ 📁 AI_Model/         # Python Colab notebook for ML/AI
 ┣ 📁 Web_Dashboard/    # HTML + JS Fraud Detection Dashboard
 ┣ 📁 Data/             # Synthetic + Kaggle fraud datasets
 ┣ 📁 Reports/          # Exported PDF reports
 ┣ README.md            # Project Documentation

✅ Impact

Banks → Save millions, avoid fines, boost trust

Customers → Protect funds, reduce false flags

Society → Strengthen financial systems, stop organized fraud

⚡ Built with AI + Graph Analytics to safeguard digital finance against next-gen fraud.
