# 🇮🇳 Pan-India Automotive Market Intelligence Engine & Web Scraper

A production-grade, full-stack data pipeline designed to harvest, cluster, and analyze high-volume used car listings across major Indian metropolitan regions (Delhi-NCR, Mumbai, Bengaluru, Chennai, Hyderabad). 

Built with a professional geometric UI inspired by OLX India, this architecture features high-fidelity background web scraping streams, relational multi-column database filtering, and an integrated **Mini-SLM (Small Language Model)** semantic analytical chatbot.

---

## 🛠️ Tech Stack & Architecture

*   **Frontend:** HTML5, Premium Geometric CSS Variables (Native Light/Dark Mode Transitions), Vanilla JavaScript Async Engine.
*   **Backend:** Node.js, Express.js REST API Architecture.
*   **Data Scraping:** Puppeteer-Extra with `puppeteer-extra-plugin-stealth` to bypass Cloudflare/Akamai CDN anti-bot blocks.
*   **Database Engine:** Serverless relational SQLite3 driver for persistent hardware data logging.
*   **AI Layer:** Deterministic Natural Language Processor (Mini-SLM) mapping human voice tokens directly into executable SQL aggregate functions.

---

## 🚀 Key Engineering Features

1. **Massive Paginated Volume Harvesting:** Implements non-blocking background worker processes capable of streaming 600+ multi-variant database records per execution pass without blocking frontend network sockets.
2. **Strict Multi-Column Relational Queries:** Fixed string-to-integer conversion parsing that enforces mathematical price floors/caps (e.g., filtering strictly under ₹1 Lakh) alongside variant parameters (Owners, Fuel Sub-type, Transmission, Location).
3. **Inline Modal Inspection Framework:** Replaces broken external redirect loops with an integrated deep-view overlay component mapping live database indices natively for direct dealer/user context matching.
4. **Crawl Session History Ledger:** Side-panel state management logging query history, execution records, and background timestamp nodes locally.

---

## ⚙️ Local Development Instructions

### Pre-requisites
Ensure you have Node.js (LTS) installed on your machine.

### 1. Installation
Clone the repository and install the required structural package modules:
* Run command: `npm install`

### 2. Execution
Spin up the persistent backend analytics server:
* Run command: `node server.js`

### 3. Launching Dashboard UI
Right-click on `index.html` inside Visual Studio Code and select **Open with Live Server** to serve the application context interface securely on port `5500`.

---

## 🥷 Anti-Bot Evasion Implementation Note
To prevent enterprise target CDNs from blacklisting local hardware IPs, the scraping core utilizes custom user-agent spoofing algorithms and actively strips automated browser footprints (`navigator.webdriver = true`).
