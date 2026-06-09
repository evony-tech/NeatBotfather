# 👑 The NEAT Botfather

The ultimate, modern C# Command Center for NEATBOT. The NEAT Botfather is a high-performance, multi-threaded orchestration engine designed to manage, monitor, and automate your entire neatbot swarm. Built to replace outdated legacy tools, Botfather bridges the gap between 2009 Flash games and 2026 server architecture.

---

## ⚡ Key Features

* **Live Swarm Dashboard:** Monitor your entire bot army from a single, dark-mode GUI. View live CPU/Memory consumption, process IDs, and real-time status updates with dynamic color-coded alerts.
* **Autopilot "Upsert" Engine:** True plug-and-play architecture. When a new account runs an Autopilot script, Botfather instantly intercepts the C2 payload, builds the account in its local SQLite database, and auto-populates the dashboard.
* **Zombie Hunter & Smart Auto-Recovery:** Features a strict background monitor that hunts down frozen game clients (0.0% CPU / 0.0 MB RAM). Combined with a 15-Minute Watchdog and Auto-Stop enforcements, Botfather automatically terminates hanging processes and revives crashed instances to keep your Swarm healthy 24/7.
* **Whale Hunter & Telegram Integration:** A highly advanced Report Processor parses incoming Scout and Battle XMLs in real-time. It translates combat data, calculates resource burns, and dispatches detailed tactical alerts directly to your Telegram rooms.
* **Multi-Monitor Window Hijacker:** Automatically detects new bot instances, bypasses the splash screen, and securely teleports the window to the center of your designated monitor at your preferred "Rescue Resolution."
* **Flash Storage Double-Lock:** Built-in tools to permanently lock your Flash Local Storage (`settings.sol`), preventing race conditions from resetting your storage limit when launching massive swarms simultaneously.

---

## 🛡️ Recommended Companion: Neat Flash Browser

While Botfather operates the backend, we highly recommend using our custom-built **Neat Flash Browser** to view Botfather's local web dashboards and play the game. Modern browsers have abandoned Flash, and legacy browsers are too bloated to render Botfather's modern HTML5/CSS3 UI. 

Our browser is perfectly sandboxed—local Botfather UI and game traffic are allowed, but secure external links (`https://`) are instantly bounced to your default Windows browser to keep your botting environment isolated.

👉 **Download the Neat Flash Browser here:** [https://github.com/evony-tech/NeatFlashBrowser/releases](https://github.com/evony-tech/NeatFlashBrowser/releases)

---

## 🚀 Getting Started

> **Note:** The C# source code for The NEAT Botfather is maintained in a private repository to protect proprietary routing and Anti-Ban algorithms. Official compiled binaries are distributed here.

### 1. Installation
1. Navigate to the **Releases** tab on the right side of this page.
2. Download the latest `Botfather-Setup.exe`.
3. Run the installer and launch The NEAT Botfather.

### 2. Authentication
Upon your first boot, you will be prompted for a NEATOKey. This key verifies your Omni-Net clearance and unlocks the premium routing modules. Paste your key in the **Settings** menu to authenticate.

### 3. Adding Accounts
You can manually add accounts using the "Search / New Account" bar at the top of the grid, or simply let the Autopilot Engine auto-discover and build your accounts the moment they connect to the local server.

---

## 🐛 Support & Documentation

Found a bug or have a feature request? Please use the **Issues** tab at the top of this repository. Be sure to include your current Botfather version and any relevant (but sanitized) error logs!

For official documentation, guides, and FAQ, please visit the official knowledge base at: [https://neato3.com](https://neato3.com)
