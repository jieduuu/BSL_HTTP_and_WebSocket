# 🚀 CCC181 Lab 1: BSL HTTP & WebSocket Portfolio Landing Page

> **Developer:** Jeddrick Amarga  
> **Program & Track:** BSIT – 3rd Year (Network Systems)  
> **Institution:** Mindanao State University – Iligan Institute of Technology (MSU-IIT)  
> **Course:** CCC181 – Application Development and Emerging Technologies  

---

## 📌 1. Project Overview

This repository features a custom portfolio web application built and served using the **Bonezegei Scripting Language (BSL v1.3.3)** HTTP web server engine. Developed for **CCC181 Laboratory 1**, this project highlights low-level web routing, static asset distribution, and real-time client-server communication over WebSockets.

### Key Highlights
* **Custom Server Architecture:** Built on native BSL server primitives with modular asset routing handlers.
* **Responsive Dark Interface:** Styled portfolio displaying student bio, network systems specialization, technical skill sets, and project highlights.
* **Real-Time WebSocket Client:** Integrated client engine enabling live bidirectional WebSocket (`ws://` / `wss://`) data streams.
* **Cloud-Native Runtime:** Standardized and executed inside an isolated Linux container on GitHub Codespaces.

---

## ⚙️ Tech Stack & Architecture

| System Layer | Technology / Specification | Purpose |
| :--- | :--- | :--- |
| **Engine Runtime** | Bonezegei Scripting Language (BSL v1.3.3) | Core scripting environment & HTTP server interpreter |
| **Backend Router** | `lib/http.bzg` | Custom route handling and static file delivery |
| **Frontend UI** | HTML5, CSS3, Vanilla JavaScript | Responsive dark-mode interface and dynamic components |
| **Protocol** | WebSockets (`ws://`) | Real-time event communication |
| **Development OS** | Linux (`x86_64` container) | Cloud-hosted GitHub Codespaces environment |

---

## 📂 Repository Directory Layout

```text
BSL_HTTP_and_WebSocket/
├── lib/
│   └── http.bzg           # Core BSL HTTP & WebSocket server library
├── public/
│   ├── index.html         # Portfolio landing page frontend
│   └── 404.html           # Custom fallback error page handler
├── screenshots/
│   ├── terminal.png       # Execution log verification screenshot
│   ├── browser.png        # Portfolio homepage browser verification
│   └── browser2.png       # WebSocket feature & live status screenshot
├── app.bzg                # Main application entry point & GET route handlers
├── Bonezegei-x86.deb      # BSL Debian installation package
├── LICENSE                # Open-source MIT License
└── README.md              # Project documentation
