# ⚡ AI-Based Intelligent Optimization for Energy-Efficient Green Cloud Computing

<p align="center">
  <img src="https://images.unsplash.com/photo-1558494949-ef010cbdcc31?w=1000&q=80" alt="Datacenter Servers Banner" style="border-radius:15px;"/>
</p>

> **Final Year Project: Working Model / Live Simulator Dashboard**

Welcome to the **Green Cloud AI Optimizer**. This repository hosts an interactive, real-time working model demonstrating advanced dynamic Virtual Machine (VM) consolidation. By leveraging predictive Neural Networks, this dashboard proves that cloud environments can drastically reduce their electricity consumption and carbon footprint without violating Service Level Agreements (SLAs).

## 🚀 Features

- **Live 24-Hour Simulation**: A dynamic visual engine that animates a full diurnal datacenter cycle, directly mapping workload peaks and troughs over time.
- **Side-by-Side Comparison**: Visually compares traditional Reactive (Static) node scaling versus our Proposed AI-Optimized (Dynamic) VM consolidation.
- **Real-Time Analytics**: Evaluates deep KPIs tracking Energy Conserved (kWh), Carbon Offset (kg of CO2), and SLA predictability precisely.
- **Interactive Server Rack UI**: Watch visual physical cluster nodes transition into "Deep Sleep" states dynamically as the Neural Net aggressively groups low-demand VMs into dense, highly-active hosts.
- **Polished Data Visualization**: Gorgeous Altair gradient charts tracing power draw curves alongside interactive executive dashboard styling.

---

## 🛠️ Technology Stack
- **Frontend / Core Engine**: [Streamlit](https://streamlit.io/) (Python)
- **Data Manipulation**: Pandas, NumPy
- **Visualizations**: Altair HD Charts
- **Simulation Logic**: Simulated workload traces weighting an Actor-Critic Reinforcement Learning Engine reacting to Multilayer Perceptron predictions.

---

## 💻 Installation & Execution

It takes less than 60 seconds to get the Green Cloud Simulator running locally on any machine.

### 1. Prerequisites
Ensure you have **Python 3.8+** installed on your system.

### 2. Clone the Repository
```bash
git clone https://github.com/ffaahhimm/green-cloud-ai-optimizer.git
cd green-cloud-ai-optimizer
```

### 3. Install Required Dependencies
```bash
pip install -r requirements.txt
```

### 4. Execute the Dashboard
```bash
streamlit run app.py
```
Your local system will start the application, and a browser window mapping to `http://localhost:8501` will automatically open.

---

## 🔬 How The AI Optimizer Works

The background system simulates a comprehensive multi-stage pipeline:
1. **Workload Tracking**: Continuously maps the incoming simulated cloud server requests dynamically.
2. **Neural Network Prediction**: Instead of waiting for strict threshold crossings (which results in massive latency), the ML model proactively shifts workloads *before* maximum capacity draws near.
3. **VM Live Migration**: Safe parallel movement of active VM states into consolidated host environments forming the densest capacity footprint.
4. **C-State Deep Sleep**: Empty, unused physical hosts are forcefully placed into hibernation (Deep Sleep mechanisms) drawing near-zero watts. 
5. **Continuous Adaptation**: The app acts as an infinite-loop agent adapting to the sinusoidal demand curves while remaining robust against SLA penalties.

---

## 🏆 Project Evaluation Context

This dashboard serves as the master interactive demonstration of our Computer Science final year project. It validates the hypothesis that combining **Workload Predictive Machine Learning** and **Multi-Objective Resource Heuristics** constructs a vastly superior, scalable, and environmentally-aware cloud datacenter.

*Developed & Optimized by the Final Year Project Team. Ready for prime-time evaluation.*
