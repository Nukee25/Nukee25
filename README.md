<div align="center">

# Hey There, The Name's Kshitij
### Systems Engineer • Local AI Architect • Founder @ Kode Insignia

[![GitHub](https://img.shields.io/badge/GitHub-nukee25-181717?style=for-the-badge&logo=github)](https://github.com/nukee25)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/)
[![Fedora](https://img.shields.io/badge/OS-Fedora%20Linux-51A2DA?style=for-the-badge&logo=fedora&logoColor=white)](https://getfedora.org)
[![Status](https://img.shields.io/badge/Focus-Systems%20%7C%20Local%20AI%20%7C%20High--Perf%20Compute-critical?style=for-the-badge)]()

<br />

> Computer Science undergraduate at Galgotias College of Engineering & Technology. Focused on low-level compute optimization, air-gapped local LLM orchestrations, distributed client-server systems, and open-source tooling.

</div>

---

### 📌 Summary

I build deterministic, privacy-first software spanning POSIX socket architectures, low-latency computational engines, and edge-native AI pipelines. As the Founder and Technical Lead of **Kode Insignia**, I orchestrate developer sprints, lead hardware-in-the-loop robotics workshops, and build hardened, containerized microservice architectures. My workflow lives entirely in Linux (Fedora), with a focus on C++ systems, local model deployment (Ollama/ggml), and full-stack systems with zero exposed attack surface.

---

### 🛠️ Technical Skillset
```
┌─────────────────────────┬────────────────────────────────────────────────────────┐
│ Category                │ Technologies & Disciplines                             │
├─────────────────────────┼────────────────────────────────────────────────────────┤
│ Core & Systems          │ C, Modern C++ (C++17/20), Python 3, POSIX Threads,     │
│                         │ Berkeley Sockets, Bash, Linux Systems (Fedora)         │
├─────────────────────────┼────────────────────────────────────────────────────────┤
│ Machine Learning & CV   │ Ollama, ggml / GGUF 4-bit Quantization, Local LLMs,    │
│                         │ YOLOv8, OpenCV, Q-Learning (Reinforcement Learning)    │
├─────────────────────────┼────────────────────────────────────────────────────────┤
│ Backend & Architecture  │ Django, Django REST Framework, FastAPI, Express.js,    │
│                         │ Microservice Isolation, Client-Server Architectures    │
├─────────────────────────┼────────────────────────────────────────────────────────┤
│ Frontend & Visuals      │ React.js, Next.js, TypeScript, Tailwind CSS,           │
│                         │ Dynamic JSON-Schema Dashboards                         │
├─────────────────────────┼────────────────────────────────────────────────────────┤
│ Databases & Infra       │ Docker, Docker Compose, Nginx (Zero-Port Reverse Proxy)│
│                         │ MariaDB, MongoDB, Git, CI/CD Automations               │
├─────────────────────────┼────────────────────────────────────────────────────────┤
│ Hardware & Embedded     │ Sensor Integration, Microcontrollers, Testbenches,     │
│                         │ Line Followers, Robotic Arms, Spherical Bots           │
└─────────────────────────┴────────────────────────────────────────────────────────┘
```
---

### 💼 Experience & Leadership

#### 🏛️ Founder & Technical Lead — **Kode Insignia** *(2025 – Present)*
* Architected end-to-end project roadmaps, microservice deployments, and developer tooling across the organization.
* Conducted offline technical training sessions including the **Kode Insignia Robotics Workshop**, mentoring students through hands-on fabrication and firmware for Line Followers, Robotic Arms, and Spherical Bots.
* Orchestrated a 20-team virtual Pitchathon in collaboration with **E-Cell IIT Bombay** and **Eureka!**.

#### 🌐 Open Source Contributor — **GirlScript Summer of Code (GSSoC 2026)** *(2026)*
* Contributed to the **Open Source** and **AI/Agents** tracks, shipping modular features, bug fixes, and documentation across ecosystem repos.

#### ⚡ Open Source Contributor — **Epic Games / Unreal Engine Ecosystem** *(2026)*
* Contributed to runtime pipeline profiling, low-level engine compute performance, and resource benchmarking tools.

#### 🤝 Community & Campus Leadership
* **Campus Lead & Contributor** — *Open Source Connect India (2026)*: Mentoring student developers in Git hygiene, open-source standards, and collaboration.
* **Campus Ambassador** — *E-Cell IIT Bombay (2026)*: Driving student entrepreneurship initiatives and national competition roadshows.
* **Regional Coordinator & Ambassador** — *Techfest IIT Bombay (2026)*: Managing regional technical outreach, logistics, and student participation.
* **Campus Ambassador** — *Rendezvous IIT Delhi (2026)*: Coordinating institute outreach and festival operations.

---

### 🚀 Featured Engineering Projects

#### 1. Systems & Low-Level Engineering

* **[Sanchaar-CLI](https://github.com/nukee25/Sanchaar-CLI)**
  * A lightweight, cross-platform CLI chat application implemented in Modern C++ using Berkeley Sockets and POSIX threads (`pthreads`).
  * Features concurrent non-blocking socket handling, ANSI terminal styling, and robust client-server heartbeat isolation.
  * *Tech:* `C++17`, `POSIX Threads`, `Sockets API`, `Linux`

* **MatrixC, MatrixPy & PolynomialPy**
  * High-performance numerical libraries designed for linear algebra and polynomial computations without heavy external dependencies.
  * Implemented cache-friendly memory layouts in C and optimized algorithmic routines in Python.
  * *Tech:* `C`, `Python`, `Algorithms`, `Linear Algebra`

* **Runtime Profiling & Engine Compute Optimization**
  * Micro-benchmarking suites and compute analysis tools targeted at profiling runtime frame pipelines and memory hotspots.
  * *Tech:* `C++`, `Profiling Tools`, `Compute Optimization`

---

#### 2. Local AI, Computer Vision & Privacy-First Engines

* **[Chitralekha (Chitra Pipeline)](https://github.com/nukee25/chitra-pipeline)**
  * Automated CCTV surveillance and hazard detection engine combining OpenCV temporal frame chunking with real-time YOLOv8 object recognition.
  * Feeds frame context directly to an air-gapped local Qwen model for threat validation and reasoning, backed by a Django and MongoDB API with a React dashboard.
  * *Tech:* `OpenCV`, `YOLOv8`, `Qwen LLM`, `Ollama`, `Django`, `MongoDB`, `React`

* **[Vaidya](https://github.com/nukee25/vaidya)**
  * Privacy-preserving clinical decision support system ensuring total data sovereignty by keeping health data local.
  * Leverages local LLM inference over Ollama paired with deterministic algorithmic health scoring, MariaDB, and a hardened Django backend.
  * *Tech:* `Ollama`, `MariaDB`, `Django`, `Local Inference`, `Health-Tech`

* **Minesweeper Reinforcement Learning Agent**
  * An autonomous agent built from scratch using custom Q-learning strategies to solve variable-grid Minesweeper without external heuristics.
  * *Tech:* `Python`, `Reinforcement Learning`, `Q-Learning`, `NumPy`

* **FactChecker**
  * An automated claim-verification engine migrated from cloud APIs to an offline, privacy-first local LLM runner via Ollama.
  * *Tech:* `Python`, `Ollama`, `NLP`, `Information Retrieval`

---

#### 3. Full-Stack Architectures & Research Systems

* **[Swaraj Setu](https://github.com/nukee25/swaraj-setu)**
  * Production-grade civic grievance management and prioritization system.
  * Integrates an offline NLP microservice using Ollama for automatic ticket categorization and routing, a Django REST backend, MongoDB, and React, fully orchestrated via Docker Compose behind a zero-exposed-port Nginx reverse proxy.
  * *Tech:* `React`, `Django REST Framework`, `Docker Compose`, `Nginx`, `MongoDB`, `Ollama`

* **Dynamic Intelligent Dashboard Generator**
  * Engine that consumes raw, arbitrarily nested JSON schemas and dynamically renders structured, responsive React analytics interfaces.
  * *Tech:* `React.js`, `TypeScript`, `Schema Parsers`, `Tailwind CSS`

* **NewsFront**
  * Responsive, mobile-first feed reader that ingests multi-source data streams and provides on-device automated text summarization.
  * *Tech:* `JavaScript`, `REST APIs`, `Web Components`, `CSS3`

* **Urban Infrastructure Proposals: Dilli360 & Edge Road Quality Monitoring**
  * *Dilli360:* A smart transit model coordinating multi-modal transport with the Delhi Metro Rail Corporation (DMRC) network to balance heritage site foot traffic.
  * *Edge Road Quality Monitoring:* Architectural design for edge-mounted camera units running spatial graphs to detect and map asphalt degradation in real time.

---

### 🏆 Honors & Recognition

* 🏅 **National Finalist** — *India Innovates Hackathon* (Bharat Mandapam, New Delhi)
* 🏆 **Winner** — *GeeksforGeeks x Nerds Room HackFest*

---

<div align="center">
  <sub>Engineered with precision on Fedora Linux. Reach out at your preferred channel for collaborations!</sub>
</div>
