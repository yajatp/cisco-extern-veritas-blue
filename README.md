# Veritas Blue — Project Glass Ocean
### Cisco High School Externship Capstone Pitch (Austin Cohort)

[![Live Presentation](https://img.shields.io/badge/Vercel-Live_Presentation-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://cisco-extern-veritas-blue.vercel.app)
[![Cisco Externship](https://img.shields.io/badge/Cisco-Externship_2026-049FD9?style=for-the-badge&logo=cisco&logoColor=white)](https://cisco-extern-veritas-blue.vercel.app)

---

## 🌊 Overview & Context

**Veritas Blue** (developed by **Bat Bridge Partners**, Austin Cohort) is an interactive 3D presentation deck and Cisco consulting proposal built for **The Metals Company (TMC)** — a public deep-sea mining firm harvesting battery-metal nodules from the Pacific seafloor at 4,000 meters depth.

TMC faces a critical **proof and trust deficit**: environmental groups, regulators, and investors publicly distrust their ecological impact claims. Our proposal turns security into the core product: **verified environmental truth makes deep-sea mining licensable, insurable, and fundable.**

> *"Give the machines eyes. Give the ocean a voice. Lock both behind doors nobody can pick."*

---

## 👥 Team & Mentors

- **Program:** Cisco High School Externship (Austin Cohort)
- **Team:** Bat Bridge Partners (6 Members)
- **Cisco Mentors:** Cecelia Croman & Demetrius Christian
- **Team Contributions:** All members actively contributed across research, technical architecture, 3D simulation design, and pitch presentation delivery.

---

## 🚀 Key Solution Pillars

1. **Glass Ocean (Tamper-Proof Environmental Monitoring)**
   - Sensor data is signed and hash-chained directly into **Splunk** over a one-way physical network architecture.
   - **Cisco Products:** Splunk, Catalyst Industrial Ethernet, ThousandEyes, Webex.

2. **AI Selective Harvesting (Mining in the Dark)**
   - Real-time computer-vision retrofit on collector vehicles: automatically detects and skips epifauna (marine life), auto-throttles when sediment plumes spike, and logs signed decisions into an immutable ledger.
   - **Cisco Products:** UCS AI POD, CURWB (Ultra-Reliable Wireless Backhaul), Catalyst IE.

3. **Zero Trust Architecture (Cyber & Operational Security)**
   - Microsegmentation and defense against ransomware, data poisoning, and vessel spoofing.
   - **Cisco Products:** Duo, ISE (Segmentation), Cyber Vision (OT), Umbrella, Secure Access (ZTNA), XDR, Splunk.

---

## 💻 Tech Stack & Architecture

- **Build System & Runtime:** Vite + Vanilla JavaScript (ES Modules)
- **3D Graphics & Stage Engine:** Three.js + WebGL rendering engine driving an ambient deep-sea environment with procedural marine snow, caustics, and bubble particle bursts (`stage.js`, `bubbles.js`).
- **Deck Engine:** Custom 21-cue presentation sequencer (`deck.js`, `sequence.js`, `slides.js`) with fluid slide-sink and surface transitions.
- **Embedded Interactive Demos:** Three full-screen, pre-warmed HTML5/WebGL simulation scenes:
  - **Demo 1 (`demo-1.dc.html`):** Glass Ocean Live Telemetry Dashboard & Tamper Detection.
  - **Demo 2 (`demo-2.dc.html`):** Robot Cam Selective Nodule Harvesting Interactive Simulation.
  - **Demo 3 (`demo-3.dc.html`):** Shark Attack Zero Trust Threat Metaphor 3D Scene.
- **Styling:** Custom glassmorphism UI with bioluminescent cyan/teal accents.

---

## ⌨️ Controls & Navigation

### Presentation Keys
| Key | Action |
| --- | --- |
| `→` / `Space` / `PageDown` / `Click` | Advance to next slide or next simulation beat |
| `←` / `PageUp` | Step back to previous slide or beat |
| `S` / `s` | **Escape Hatch** — instantly bail out of any live demo to the next slide |
| `Home` / `↑` | Jump to Title slide (Cue 1) |
| `End` / `↓` | Jump to Thank You slide (Cue 21) |
| `1`, `2`, `3` | Jump directly to Demo 1, Demo 2, or Demo 3 |
| `⛶` Button | Toggle full-screen mode |

---

## 🎯 Show Sequence (21 Cues)

1. **Title** (`page-01`)
2. **Team** (`page-02`)
3. **Client** (`page-03`)
4. **Roadmap** (`page-04`)
5. **Implementation & Risk** (`page-05`)
6. **Glass Ocean — Our Problem** (`page-06`)
7. **Glass Ocean — Our Solution** (`page-07`)
8. **Glass Ocean — Cisco Tech** (`page-08`)
9. **SINK → Demo 1: Glass Ocean Live Dashboard**
10. **Mining in the Dark — Our Problem** (`page-10`)
11. **Mining in the Dark — Our Solution** (`page-11`)
12. **Mining in the Dark — Cisco Tech** (`page-12`)
13. **Mining in the Dark — Where Cisco Starts** (`page-13`)
14. **SINK → Demo 2: Robot Cam Selective Harvesting**
15. **Zero Trust — Our Problem** (`page-15`)
16. **Zero Trust — Our Solution** (`page-16`)
17. **Zero Trust — Cisco Tech** (`page-17`)
18. **SINK → Demo 3: Shark Attack Live Threat View**
19. **Scalability** (`page-19`)
20. **The Deciding Metric — Ocean Trust Index** (`page-20`)
21. **Thank You** (`page-21`)

---

## ⚙️ Development & Deployment

```bash
# Navigate to the web app directory
cd glass-ocean

# Install dependencies
npm install

# Launch development server
npm run dev

# Build for production
npm run build
```

Deployed live at [https://cisco-extern-veritas-blue.vercel.app](https://cisco-extern-veritas-blue.vercel.app).
