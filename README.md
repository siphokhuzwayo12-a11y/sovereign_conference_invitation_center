# sovereign_conference_invitation_center

# Prestige Sovereign Collaboration & Executive Conference Room v16.0

An elite, single-file sovereign command dome engineered for executive presentations, technical dry-runs, document cabinet management, and automated audience dispatching. Built for **Scapush Precision** execution.

---

## 🏛 Key Features

### 1. Sovereign Video Mesh & Controls
* **Asymmetric Workspace Layout:** Dedicated 320px sidebar for continuous audience identification and video mesh while keeping the primary reader workspace maximized (~70% width).
* **Live Video Feed:** Real-time WebRTC camera stream integration (`getUserMedia`) with avatar fallbacks.
* **Audio Loop Synthesizer:** Built-in Web Audio API tone generator for audio path testing.
* **Peer Simulation:** Test peer-joining flows with a single click.

### 2. Audience Invitation & Dispatch Engine
* **Direct Gmail Dispatch:** One-click launch into Gmail Web Compose with pre-filled recipient (`info.lepprojects@gmail.com`), subject, passkey, and access links.
* **Auto-Dispatch Link Generator:** Supports custom domain overrides (e.g., GitHub Pages, Netlify, or local network IPs) to avoid local `file:///` dead-links in webmail.
* **ICS Calendar Exporter:** Generates downloadable `.ics` calendar events for seamless scheduling.
* **Active Invitee Roster:** Dynamic dropdown menu tracking dispatch history, status, and time logs.
* **Dry-Run Test Engine:** Built-in validation suite to verify dispatch sequences prior to live steward onboarding.

### 3. Expanded Document Reader & Cabinet Workspace
* **Collapsible Vertical Shelf:** Drawer toggle allowing full expansion of document workspace up to 620px height.
* **Multi-Format Ingestion:** Instant rendering of uploaded `.html`, `.txt`, `.json`, and `.md` technical briefs via dynamic sandboxed iframes.
* **Pre-Loaded Infrastructure Brief:** Contains default valuation ledgers (e.g., R 3.1M CAPEX-buffered infrastructure models).

### 4. Decision Memory & Whiteboard
* **Architectural Whiteboard:** Canvas engine with responsive mouse/touch support and PNG export capability.
* **Persistent Decision Record:** In-suite meeting notepad backed by browser `localStorage`.

---

## 🚀 Quick Start Guide

### Option 1: Instant GitHub Pages Deployment (Recommended for Live Links)
1. Push `index.html` (or `conference_dome.html`) to this repository.
2. Go to **Settings** ➔ **Pages**.
3. Select **Branch: main**, **Folder: / (root)**, and click **Save**.
4. Paste your live GitHub Pages URL into the **Optional Custom Dome URL** input inside the suite.

### Option 2: Local Python HTTP Server
To run and test locally on port `8000`:
```bash
# Navigate to the project directory
cd sovereign_conference_invitation_center

# Start a lightweight HTTP server
python -m http.server 8000
