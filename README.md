## Zarif Mohasin

Automotive & Vehicle Engineering Technology at McMaster (B.Tech, class of 2028).
I design mechanical assemblies in CATIA and SolidWorks, and I build the systems that
run around them.

**Looking for a co-op starting January 2027** — automotive design, vehicle systems, or
embedded/software engineering. Ontario or GTA.

---

### Things I've built

| | | |
|---|---|---|
| **[Jarvis 1.0](https://github.com/Zarif-eng/Jarvis-1.0)** | A voice assistant running entirely on hardware I own — no audio or personal data leaves my network. Local model inference on a desktop GPU, speech synthesis on a MacBook, a private mesh network tying them together. Response latency measured and cut **3.94s → 1.18s** by finding a queueing bug between a background task and the inference server. | `Python` `SQLite` `Swift` `Tailscale` |
| **[Jarvis 2.0](https://github.com/Zarif-eng/Jarvis-2.0)** | The redesign, built around a finding from living with v1: most commands don't need the model at all. A deterministic tier answers in under 700 ms without waking the GPU. Design frozen, build starting. | `design` |
| **Audi L5 Inline-5** <sub>repo in preparation</sub> | High-fidelity DOHC inline-5 engine model to a 65 mm bore/stroke constraint. Kinematics simulation synchronising 20+ valves and 5 pistons from a single crankshaft input. 6-person team. | `CATIA V5` `DMU Kinematics` |
| **B58 Engine** <sub>repo in preparation</sub> | Solo build of BMW's B58 inline-6. In progress. | `CATIA V5` |
| **Oil Pump Jack** <sub>repo in preparation</sub> | Assembly and motion analysis of a walking-beam pump jack. Group project. | `SolidWorks` `Motion Analysis` |
| **FPV Drone** <sub>repo in preparation</sub> | Built and tuned a first-person-view quadcopter — flight controller configuration, PID tuning, and the build documentation. | `Betaflight` |

---

### What I actually do

**Mechanical design** — CATIA V5 (part modelling, assemblies, DMU kinematics and fitting),
SolidWorks (assemblies, motion analysis), AutoCAD.

**Systems** — self-hosting and integrating local language models rather than calling a
hosted API: deploying quantised models on consumer GPUs, private mesh networking across
machines, and measuring latency per stage until the numbers are real. C++ for
console applications.

**Testing & analysis** — materials lab work (hardness, tensile, toughness; annealing,
quenching, cold working and tempering, with microstructure analysis), MiniTab.

---

### Elsewhere

[LinkedIn](https://www.linkedin.com/in/zarif-mohasin) · mohasinz@mcmaster.ca
