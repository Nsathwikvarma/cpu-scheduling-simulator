# Interactive CPU Scheduling Visual Simulator & Lab Manual

An interactive, self-contained educational simulator for Operating Systems CPU scheduling algorithms, built with pure **HTML5, CSS3, and JavaScript** (zero external dependencies, 100% offline-ready).

This project is tailored for **Operating Systems Laboratory (Assignment III)** coursework, viva preparation, and visual demonstrations.

---

## 🚀 Live Demo on GitHub Pages

You can host this project on GitHub Pages in under a minute:
1. Create a GitHub repository (e.g., `cpu-scheduling-simulator`).
2. Push `index.html` and `README.md` to the `main` branch.
3. Go to **Settings > Pages > Branch: main > Save**.
4. Your live simulation URL will be: `https://<your-username>.github.io/cpu-scheduling-simulator/`

---

## 🌟 Key Features

### 1. Algorithms Supported (Operation 2)
- **FCFS** (First-Come, First-Served) — Demonstrates the classic *Convoy Effect*.
- **SJF** (Shortest Job First - Non-preemptive) — Optimal minimal average waiting time.
- **SRTF** (Shortest Remaining Time First - Preemptive SJF).
- **Round Robin (RR)** — Configurable Time Quantum ($q$) with preemption tracking.
- **Priority (Non-preemptive & Preemptive)** — Lower number = higher priority order.
- **Multi-Level Feedback Queue (MLFQ)** — 3-tier queue model ($Q_0$: RR $q=4 \to Q_1$: RR $q=8 \to Q_2$: FCFS).

### 2. Workload & Process Management (Operation 1)
- Custom process creation: **Process ID (PID)**, **Arrival Time (AT)**, **Burst Time (BT)**, and **Priority**.
- **Dynamic Insertion & Removal**: Add, remove, or modify processes on the fly.
- **Instant Benchmarks & Presets**:
  - *Standard 4-Process Case*
  - *Convoy Effect Demonstration*
  - *Round Robin Time-Slicing Demo*
  - *Priority Preemption Demo*
  - *Random Workload Generator*

### 3. Visual Timeline & Interactive Gantt Chart
- **Step-by-Step Interactive Player**: Play, Pause, Step Forward, and Reset controls.
- **Live CPU Core State Box**: Indicates whether the CPU is *Busy* or *Idle* with animated glow.
- **Live Ready Queue Visualizer**: Dynamically displays queued processes waiting at time $t$.
- **Time-Scaled Gantt Chart**: Color-coded process blocks with mouse hover tooltips for start/end time.
- **Speed Slider**: Adjustable playback speed (0.5x, 1x, 2.5x).

### 4. Mathematical Metrics & Export
- Real-time calculation of:
  - **Completion Time (CT)**
  - **Turnaround Time (TAT = CT - AT)**
  - **Waiting Time (WT = TAT - BT)**
  - **Response Time (RT)**
  - **Average TAT & Average WT**
  - **CPU Utilization (%) & Total Duration**
- **CSV Export**: One-click download of the scheduling metrics table for lab submissions.

### 5. Academic Lab Manual Section
- **Aim & Theoretical Foundations**: Definitions, mathematical formulas, and comparative analysis table.
- **Pseudocode**: Standard academic pseudocode for scheduling algorithms.
- **Tested ANSI C Code**: Full, compilable C source code (`sched.c`) ready to run with `gcc`.
- **Manual Trace & Verification**: Textbook benchmark dataset with step-by-step Gantt calculations.
- **Viva-Voce / FAQ Section**: 6+ essential interview questions on starvation, aging, convoy effect, and context switching.
- **Print / PDF Ready**: Clean printer styles to print the lab report directly from the browser.

---

## 🛠️ Technology Stack & Compliance

- **Pure HTML5, CSS3, & Modern JavaScript (ES6+)**
- **Zero External Libraries / Zero CDNs** — Works fully offline in Chrome, Firefox, Edge, Safari, and mobile browsers.
- **Clean Light Theme UI** — Tailored for readability, accessibility, and academic presentation.

---

## 📂 Repository Structure

```
├── index.html       # Self-contained visual simulator and lab manual
└── README.md        # Documentation and assignment submission guidelines
```

---

## 📋 Assignment Submission Template

When submitting your assignment, you can provide the following:

- **Student Name:** [Your Name]
- **Roll Number / Student ID:** [Your ID]
- **Subject:** Operating Systems Lab (Assignment III)
- **GitHub Repository:** `https://github.com/<your-username>/cpu-scheduling-simulator`
- **Live Simulator Link:** `https://<your-username>.github.io/cpu-scheduling-simulator/`

---

## 📄 License

This project is licensed under the MIT License — feel free to use, modify, and extend it for academic and educational purposes.
