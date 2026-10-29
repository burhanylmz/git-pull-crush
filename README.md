<div align="center">

# ⚡ git-pull-crush

### **Neural Core v4.2 — Distributed Inference Engine Workspace Simulator**

*A zero-dependency, dark-themed live IDE, cluster telemetry monitor, and polyglot code execution simulator built for modern developer aesthetics.*

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](./LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/Vanilla_JS-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=for-the-badge)](https://github.com/burhanylmz/git-pull-crush/pulls)
[![Live Demo](https://img.shields.io/badge/Live_Demo-GitHub_Pages-2ea44f?style=for-the-badge&logo=github)](https://burhanylmz.github.io/git-pull-crush/)

</div>

---

## 📖 Overview

**`git-pull-crush`** (*Neural Core*) is a lightweight, self-contained interactive IDE and distributed cluster simulation environment written in pure HTML5, CSS3, and Vanilla JavaScript.

Designed with a sleek **GitHub Dark (`#0d1117`)** aesthetic and powered by `JetBrains Mono` typography, it simulates a full-stack distributed AI inference engine workspace—complete with human-cadence syntax-highlighted live coding, automated tab switching across five backend languages, real-time GPU cluster progress bars, and an active telemetry terminal stream.

---

## ✨ Key Features

- 🖥️ **HTML-Aware Human Typing Engine**: Renders syntax-highlighted source code character-by-character with realistic human typing jitter (`60–180ms`) while seamlessly skipping raw HTML/entity tags to prevent visual artifacts.
- 🌐 **Polyglot Architecture Simulation**: Automatically cycles through 5 realistic distributed-systems modules written in **Python 3.12**, **Rust 1.82**, **Go 1.23**, **TypeScript**, and **PostgreSQL**.
- 📊 **Live Cluster Telemetry Sidebar**: Displays active GPU node health (`128 / 128 nodes`), dynamic model training progress bars with smooth CSS transitions, and randomized compute load indicators.
- 📟 **Real-Time Terminal Log Stream**: Continuously emits color-coded cluster events (`handshake complete`, `syncing gradients`, `tensor shard verified`, `latency spike rebalancing`, `AES key rotation`, and `epoch checkpoints`).
- 🎨 **GitHub Dark Native UI**: Features macOS-style window controls, active tab highlights, auto-scrolling line numbers, a blinking block cursor, and a live status bar with real-time system clock.
- 🚀 **Zero Dependencies & Instant Load**: Contained within a single `index.html` file with zero external JavaScript frameworks or build steps required.

---

## 🧩 Simulated Modules

The workspace rotates across five core engineering modules that represent a distributed AI inference pipeline:

| File | Language / Runtime | Simulated Responsibility |
| :--- | :--- | :--- |
| `inference_engine.py` | **Python 3.12** | Async tensor routing, `NodeMesh` hypercube partitioning, `AES256Pipeline` encryption, and gradient clipping across 128 GPU nodes. |
| `cluster.rs` | **Rust 1.82** | Lock-free `AtomicU64` node mesh state synchronization over `tokio::net::TcpStream` and work-stealing task scheduling. |
| `crypto_layer.go` | **Go 1.23** | Zero-knowledge authentication prover using `crypto/sha3` commitments and `crypto/ed25519` signature verification. |
| `dashboard.ts` | **TypeScript** | High-frequency (`250ms`) WebSocket telemetry streamer (`port 8443`) with automated thermal throttling above `82°C`. |
| `analytics.sql` | **PostgreSQL** | Regional `p99` inference latency aggregation using `percentile_cont(0.99)` window functions. |

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/burhanylmz/git-pull-crush.git
cd git-pull-crush
```

### 2. Run Locally

Since `git-pull-crush` has zero build dependencies, you can launch it directly in any modern browser:

```bash
# Windows (PowerShell)
Start-Process .\index.html

# macOS
open index.html

# Linux
xdg-open index.html
```

Or serve it via a local HTTP server:

```bash
# Using Python
python -m http.server 8080

# Using Node.js
npx serve .
```

Then navigate to `http://localhost:8080` in your browser.

---

## 🛠️ Customization

You can easily tailor the simulation inside [`index.html`](./index.html):

- **Typing Speed**: Adjust the timeout interval in `typeStep()` (`60 + Math.random() * 120` ms) to speed up or slow down code rendering.
- **Code Snippets**: Modify the `py`, `rs`, `go`, `ts`, or `sql` arrays or register new tabs in the `files` array.
- **Terminal Events**: Add custom log templates and severity classes (`ok`, `info`, `warn`) in the `logs` array.

---

## 📁 Project Structure

```text
git-pull-crush/
├── index.html      # Main application (UI, styles, polyglot snippets & simulation engine)
├── README.md       # Project documentation
├── LICENSE         # MIT License
└── .gitignore      # Git ignore rules
```

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'feat: add AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

Distributed under the **MIT License**. See [`LICENSE`](./LICENSE) for more information.

---

<div align="center">

**Developed by [Burhan YILMAZ](https://github.com/burhanylmz)**

</div>

