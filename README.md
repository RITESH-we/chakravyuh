# CHAKRAVYUH: AI-Powered Red Team Simulation Platform
### Master Architecture & Interactive Documentation — Version 4.0

[![GitHub Pages](https://img.shields.io/badge/Hosted%20on-GitHub%20Pages-blue?logo=github)](https://pages.github.com/)
[![Specification](https://img.shields.io/badge/Specification-v4.0-cyan)](#)
[![Execution Environment](https://img.shields.io/badge/Environment-Isolated%20Lab%20Only-amber)](#)

---

## 📖 Overview

**CHAKRAVYUH** is an AI-powered Red Team simulation platform designed to coordinate controlled cybersecurity experiments through a centralized AI Planner and deterministic Python guardrails.

This repository hosts the **Full Interactive Web Handbook & Architecture Explorer**, ready for **1-click static deployment via GitHub Pages**.

### The Foundational Golden Rule

> **AI plans. Python validates. The Safety Gateway authorizes. Adapters execute. The Observation Engine measures.**

---

## 🚀 Live Interactive Web Page Features

The included `index.html` is a self-contained, responsive, dark-mode technical handbook equipped with:
- **Mermaid.js Architecture Diagrams:** Renders real-time vector flowcharts, sequence diagrams, class hierarchies, state machines, and ER schemas.
- **Interactive Simulation Pipeline:** Step-by-step walkthrough simulating an authentication experiment from user prompt to telemetry observation.
- **Safety Gateway Sandbox:** Test legitimate vs. unauthorized IP targets and parameter overflow rejections in real time.
- **Dynamic 20-Part Acceptance Checklist:** Track implementation milestones with local progress calculation.
- **Search & Quick-Nav:** Instant jump across all 20 parts of the Master Handbook v4.0.

---

## 🌐 How to Host on GitHub Pages (Step-by-Step)

To host this interactive documentation on your GitHub repository:

### Step 1: Initialize Git and Commit
```bash
git init
git add .
git commit -m "feat: initial release of CHAKRAVYUH v4.0 interactive handbook"
```

### Step 2: Push to Your GitHub Repository
```bash
git branch -M main
git remote add origin https://github.com/<your-username>/<your-repo-name>.git
git push -u origin main
```

### Step 3: Enable GitHub Pages in 3 Clicks
1. Navigate to your repository on **GitHub.com**.
2. Go to **Settings** ➔ **Pages** (under "Code and automation" in the left sidebar).
3. Under **Build and deployment**:
   - **Source:** Select `Deploy from a branch`.
   - **Branch:** Select `main` and folder `/ (root)`.
4. Click **Save**.

Your site will be live within seconds at:
```text
https://<your-username>.github.io/<your-repo-name>/
```

---

## 💻 Local Preview

You can open `index.html` directly in any web browser without needing a server:
- Double-click `index.html` in File Explorer, or
- Run a lightweight Python web server:
  ```bash
  python -m http.server 8000
  ```
  and visit `http://localhost:8000` in your browser.

---

## 🛡️ Core Simulation Modules Supported

1. **Authentication Simulation:** Synthetic Windows Event logs (4624, 4625, 4771) with `simulated: true`.
2. **Service-Load Simulation:** Bounded Locust workloads evaluating latency and error rates against authorized local endpoints.
3. **Phishing-Awareness Simulation:** Educational awareness drills with synthetic recipients; credential collection strictly disabled.
4. **Wireless-Security Simulation:** Synthetic 802.11 frame event telemetry without physical radio emissions.

---

## 📜 License & Lab Usage

Designed exclusively for authorized testing in isolated cybersecurity laboratories. No public or unauthorized targeting permitted.
