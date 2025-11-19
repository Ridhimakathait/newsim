# 🧠 AI-Empowered Process Scheduler Simulation

![Project Status](https://img.shields.io/badge/Status-Prototype-success)
![License](https://img.shields.io/badge/License-MIT-blue)
![Tech Stack](https://img.shields.io/badge/Tech-HTML%20%7C%20CSS%20%7C%20JS%20%7C%20Gemini%20API-orange)

A modern, interactive educational tool designed to visualize and analyze CPU scheduling algorithms. This project bridges the gap between theoretical Operating System concepts and practical application by integrating **Google's Gemini Large Language Model (LLM)** to provide intelligent workload generation, predictive modeling, and automated performance analysis.

---

## ✨ Key Features

### 🖥️ Core Simulation
* **Robust Algorithm Suite:** fully functional implementation of 6 classical scheduling algorithms:
    * First-Come-First-Serve (FCFS)
    * Shortest Job First (SJF)
    * Shortest Remaining Time First (SRTF)
    * Round Robin (RR) with variable Time Quantum
    * Priority Scheduling (Non-Preemptive)
    * Priority Scheduling (Preemptive)
* **Real-Time Visualization:** Dynamic Gantt charts that render process execution, idle times, and context switches.
* **Comprehensive Metrics:** Automatic calculation of Waiting Time, Turnaround Time, Response Time, CPU Utilization, and Throughput.

### 🤖 AI-Powered Intelligence (Gemini Integration)
* **Smart Process Generation:** Create complex, realistic simulation workloads simply by describing them in plain English (e.g., *"A mixed workload with 5 processes, one CPU intensive and the rest I/O bound"*).
* **Predictive Modeling:** The AI analyzes your input data *before* execution to predict which algorithm will yield the best performance.
* **Cognitive Analysis:** Generates human-readable insights explaining *why* a specific algorithm performed best, highlighting trade-offs like starvation or convoy effects.

### 📊 Comparative Analytics
* **Side-by-Side Comparison:** Run all algorithms on the same dataset instantly.
* **Visual Graphs:** Integrated Chart.js visualization to compare average waiting times and throughput across all strategies.

---

## 🚀 Getting Started

### Prerequisites
* A modern web browser (Chrome, Firefox, Edge, Safari).
* A text editor (VS Code, Notepad++, etc.).
* **A Google Gemini API Key** (Free via [Google AI Studio](https://aistudio.google.com/)).

---


## 📖 Usage Guide

1.  **Define Processes:**
    * **Manual:** Enter Arrival Time, Burst Time, and Priority for each process.
    * **AI Generation:** Click "Smart Process Generation," describe your workload, and let the LLM build the table for you.
2.  **Select Algorithm:** Choose an algorithm from the dropdown and set a Time Quantum (if using RR).
3.  **Run & Analyze:**
    * Click **"Run Algorithm"** to see the Gantt chart and metrics.
    * Click **"Analyze these Results"** to get an AI explanation of the performance.
4.  **Compare:** Click **"Compare All Algorithms"** to run the entire suite and view comparative graphs.
5.  **Predict:** Before running, click **"Predict Best Algorithm"** to see what the AI recommends for your specific dataset.

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3 (Responsive Grid Layout)
* **Logic:** Vanilla JavaScript (ES6+)
* **AI Model:** Google Gemini 1.5 Flash (via REST API)
* **Visualization:** Custom CSS Gantt Charts + Chart.js

---

*Note: This project runs entirely client-side. Your API key is stored only in your local file and is sent directly to Google's servers; it is not sent to any third-party backend.*


---












