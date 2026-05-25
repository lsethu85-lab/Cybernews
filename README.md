# Vulnerability News Monitor

A lightweight, GitHub-ready, responsive cybersecurity monitoring dashboard designed to provide real-time visibility into critical vulnerability disclosures, active exploits, and threat intelligence feeds. 

This standalone front-end application serves as a central hub for security operations center (SOC) analysts, security researchers, and DevOps teams to track critical zero-days, exploit payloads, and emergency remediation patches.

## 🚀 Key Features

- **Real-Time Feed Simulation**: Simulates the retrieval of fresh cybersecurity intelligence feeds directly from authoritative bodies and threat research groups.
- **Dynamic Search Filtering**: Client-side instant filtering enables rapid searching by CVE IDs, application names (e.g., *Apache Tomcat*, *Cisco*, *Windows*), threat actors, or specific intelligence sources.
- **Visual Severity Badging**: Highlights threat categories with intuitive, color-coded components indicating **Critical**, **High**, **Medium**, or **Low** danger metrics.
- **Curated Intelligence Directory**: Includes embedded quick-access portals to the most reputable threat databases across the cybersecurity landscape.

## 📁 Monitored Threat Intelligence Sources

The platform establishes visual links and monitoring workflows for the following primary sources:

1. **CISA KEV**: Cybersecurity and Infrastructure Security Agency's Known Exploited Vulnerabilities catalog.
2. **NVD New CVEs**: National Vulnerability Database raw daily vulnerability streams.
3. **Exploit-DB**: Public database of Proof-of-Concept (PoC) exploit scripts and shellcode payloads.
4. **BleepingComputer**: Leading industry publisher for ransomware campaigns and data breaches.
5. **Cisco Talos / SANS ISC**: Premier technical threat laboratories and malware incident logging diaries.
6. **The Hacker News & SecurityWeek**: Enterprise security reporting channels for zero-day outbreaks.

## 🛠️ Architecture & Tech Stack

- **HTML5 & Vanilla JavaScript (ES6+)**: Structural blueprints and dynamic DOM manipulation routines.
- **Tailwind CSS**: Utility-first styling framework loaded via secure Content Delivery Network (CDN).
- **Responsive Layout Architecture**: Built using a fluid grid system optimized for desktop, tablet, and mobile displays.

## 📦 Getting Started & Deployment

As a zero-dependency static web artifact, the application can be deployed instantly using multiple workflows:

### Option 1: Local Setup
1. Download or clone this repository containing `index.html`.
2. Double-click the `index.html` file to launch the dashboard natively in any modern browser (Chrome, Firefox, Edge, Safari).

### Option 2: GitHub Pages Deployment
1. Create a public or private GitHub repository.
2. Commit the `index.html` file into the root directory of the `main` branch.
3. Navigate to **Settings** -> **Pages**.
4. Set the build source to the `main` branch and directory to `/root`, then hit **Save**.
5. Your application will be live at `https://<your-username>.github.io/<repository-name>/`.

## 🖥️ Usage & Demonstration

- **Initial Load**: Displays a baseline curated log of recent active exploits (e.g., Microsoft Defender Zero-Day, Linux Kernel escalations).
- **Interactive Search**: Use the search bar at the top right to filter down items instantly. Typing `CISA` or `Critical` will dynamically redraw cards meeting that criteria.
- **Pull Latest Data**: Click the **Refresh** button to pull live simulated updates (such as newly disclosed Apache Tomcat and Fortinet SSL VPN vulnerabilities).
