# Veritas Blue — Project Glass Ocean
### Cisco High School Externship Capstone Pitch (Austin Cohort)

[![Live Demo](https://img.shields.io/badge/Vercel-Live_Demo-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://cisco-extern-veritas-blue.vercel.app)
[![Cisco Externship](https://img.shields.io/badge/Cisco-Externship_2026-049FD9?style=for-the-badge&logo=cisco&logoColor=white)](https://cisco-extern-veritas-blue.vercel.app)

---

## 🌊 Overview & Context

**Veritas Blue** (by team *Bat Bridge Partners*, Austin Cohort) is a Cisco consulting proposal and interactive 3D pitch deck built for **The Metals Company (TMC)** — a deep-sea mining firm harvesting battery-metal nodules from the Pacific seafloor at 4,000m depth.

TMC faces a massive **proof and trust problem**: environmental groups, regulators, and investors publicly distrust their ecological impact claims. Our core thesis makes security and immutable proof the product: **verified truth is what makes deep-sea mining licensable, insurable, and fundable.**

> *"Give the machines eyes. Give the ocean a voice. Lock both behind doors nobody can pick."*

---

## 🚀 Key Solution Pillars

1. **Glass Ocean (Tamper-Proof Environmental Monitoring)**
   - Sensor telemetry hash-chained & signed into **Splunk** at capture over a one-way hardware network.
   - **Cisco Tech:** Splunk, Catalyst Industrial Ethernet, ThousandEyes, Webex.

2. **AI Selective Harvesting**
   - Real-time computer vision retrofit on collector vehicles: auto-detect & skip marine life (epifauna), auto-throttle sediment plumes, and sign every decision onto an immutable ledger.
   - **Cisco Tech:** UCS AI POD, CURWB (Ultra-Reliable Wireless Backhaul), Catalyst IE.

3. **Zero Trust Architecture**
   - Hardened floating industrial plant security against ransomware, AIS spoofing, and data poisoning.
   - **Cisco Tech:** Duo, ISE (Microsegmentation), Cyber Vision (OT Monitoring), Umbrella, Secure Access (ZTNA), XDR, Splunk.

---

## 👥 Team & Contributions

- **Program:** Cisco Externship (Austin Cohort)
- **Team Name:** Bat Bridge Partners (6 Members)
- **Technical Coach:** Demetrius
- **Team Collaboration:** All team members collaborated on research, slide design, technical architecture, and pitch presentation across the 3 core problem/solution pairs.

---

## 💻 Tech Stack & Features

- **Frontend & 3D Engine:** Vite, Vanilla JavaScript, Three.js (WebGL 3D Simulations)
- **Styling:** Custom CSS with Glassmorphism & Bioluminescent Ocean Palette
- **Interactive Pitch Deck:** Seamless transitions where slides "sink" into full-screen 3D ocean simulations (Glass Bridge, Interactive Nodule Harvester, Zero Trust Threat Metaphor).
- **Deployment:** Live on Vercel at [https://cisco-extern-veritas-blue.vercel.app](https://cisco-extern-veritas-blue.vercel.app)

---

## ⌨️ Controls & Standalone Demos

### Keyboard Navigation
- **`→` / `Space` / `PageDown`**: Advance slides & simulation beats
- **`←` / `PageUp`**: Go back
- **`S`**: **Escape Hatch** — instantly skip any simulation beat
- **`R`**: Restart the interactive robot harvesting demo
- **`Mouse Click / Enter`**: Collect green nodules (in Robot Sim)
- **`Hold W`**: Boost thrusters (spikes plume meter to trigger Auto-Throttle)

### Direct Demo Routes
- **Interactive Robot Harvester:** [`/#/robot`](https://cisco-extern-veritas-blue.vercel.app/#/robot)
- **Glass Bridge Simulation:** [`/#/bridge`](https://cisco-extern-veritas-blue.vercel.app/#/bridge)
- **Zero Trust Threat Visualizer:** [`/#/sharks`](https://cisco-extern-veritas-blue.vercel.app/#/sharks)

---

## ⚙️ Running Locally

```bash
# Navigate to application directory
cd glass-ocean

# Install dependencies
npm install

# Start local development server
npm run dev
```
