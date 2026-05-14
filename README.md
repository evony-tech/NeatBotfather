👑 The NEAT Botfather
The ultimate, modern C# Command Center for NEATBOT. The NEAT Botfather is a high-performance, multi-threaded orchestration engine designed to manage, monitor, and automate your entire Evony Swarm. Built to replace outdated legacy tools, Botfather bridges the gap between 2009 Flash games and 2026 server architecture.

⚡ Key Features
Live Swarm Dashboard: Monitor your entire bot army from a single, dark-mode GUI. View live CPU/Memory consumption, process IDs, and real-time status updates.

Autopilot "Upsert" Engine: True plug-and-play architecture. When a new account runs an Autopilot script, Botfather instantly intercepts the C2 payload, builds the account in its local SQLite database, and auto-populates the dashboard.

Whale Hunter & Telegram Integration: A highly advanced Report Processor parses incoming Scout and Battle XMLs in real-time. It translates combat data, calculates resource burns, and dispatches detailed tactical alerts directly to your Telegram rooms.

Smart Auto-Recovery: Features a 15-Minute Watchdog and Auto-Stop enforcements to automatically revive crashed instances or kill hanging processes, keeping your Swarm healthy 24/7.

Multi-Monitor Window Hijacker: Automatically detects new bot instances, bypasses the splash screen, and securely teleports the window to the center of your designated monitor at your preferred resolution.

🛡️ The Companion: Neat Flash Browser
Botfather is deeply integrated with our custom-built Neat Flash Browser.

Because modern browsers have abandoned Flash, and legacy browsers (like Maxthon 5) are bloated and incapable of rendering modern HTML5/CSS3 Dashboards, we built our own.

The HTTPS Bouncer: Neat Flash Browser is heavily sandboxed. Local Botfather UI and your favorite flash game traffic is allowed, but secure external links (https://) are instantly intercepted and bounced to your standard OS browser (Chrome/Edge) to ensure your botting environment remains perfectly isolated.

👉 Download the Neat Flash Browser here: https://github.com/evony-tech/NeatFlashBrowser/releases

🚀 Getting Started
Note: The C# source code for The NEAT Botfather is maintained in a private repository to protect proprietary routing and Anti-Ban algorithms. Official compiled binaries are distributed here.

1. Installation
Navigate to the Releases tab on the right side of this page.

Download the latest Botfather-Setup.exe.

Run the installer and launch The NEAT Botfather.

2. Authentication
Upon your first boot, you will be prompted for a NEATOKey. This key verifies your Omni-Net clearance and unlocks the premium routing modules. Paste your key in the Settings menu to authenticate.

3. Adding Accounts
You can manually add accounts using the "Search / New Account" bar, or simply let the Autopilot Engine auto-discover and build your accounts the moment they connect to the local server.

🔄 Latest Release: v1.9.5.7
Autopilot Upsert Engine: Brand new accounts are now fully plug-and-play. Botfather intercepts the UPDATE payload and instantly populates the Master Grid.

Smart Command-Line Injection: The launcher now automatically sanitizes and passes -player "Lord Name" directly to the executable.

Intelligence Delay: Upgraded the Report Engine's asynchronous wait-timers. The Swarm now has 120 seconds to execute SCAN_TILE mapping before defaulting to "Unknown" combatants, significantly reducing chat spam.

Legacy Defense Reports Restored: Telegram Incoming Attack alerts have been reverted to the classic tactical format, instantly displaying combat outcomes and exact troop counts sent.

Flash Browser Integration: Ripped out legacy Chrome routing. All Web UI dashboards and 1-click web logins now natively route through the secure Neat Flash Browser.

🐛 Bug Reports & Support
Found a bug or have a feature request? Please use the Issues tab at the top of this repository. Be sure to include your current Botfather version and any relevant (but sanitized) error logs!

For official documentation, guides, and FAQ, please visit the official knowledge base at neato3.com.
