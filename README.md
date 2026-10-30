<div align="center">

# 🚑 ERN Connect — Multi-Company CAD & Dispatch Platform

**Next-generation emergency dispatch, live GPS telematics, NEMSIS 3.5 ePCR, and fleet management platform built for private and municipal ambulance services.**

[![Live Demo](https://img.shields.io/badge/Demo-Live_Preview-success?style=for-the-badge&logo=githubpages&logoColor=white)](https://arabiabdou453-cpu.github.io/ernconnect/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Node.js](https://img.shields.io/badge/Node.js-18%2B-339933?logo=node.js&logoColor=white)](https://nodejs.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/arabiabdou453-cpu/ernconnect/pulls)

[🚀 Live Public Demo](https://arabiabdou453-cpu.github.io/ernconnect/) • [Overview](#-overview) • [Core Features](#-core-features) • [Platform Modules](#-platform-modules) • [Quick Start](#-quick-start) • [Architecture](#-architecture)

---

</div>

## 📖 Overview

**ERN Connect** is an all-in-one operating platform engineered specifically for modern ambulance operations. It unifies Computer-Aided Dispatch (CAD), real-time vehicle GPS tracking, paramedic mobile care reports (ePCR), hospital bed availability portals, and billing workflows into a high-reliability cloud architecture.

Designed for multi-agency flexibility, ERN Connect provides isolated workspaces with separate database instances, custom triage rules, and role-based permissions per ambulance company.

---

## ✨ Core Features

| Feature | Description |
| :--- | :--- |
| 📍 **Live CAD Console** | Real-time map with unit telemetry, geofenced destination zones, and intelligent proximity-based unit recommendations. |
| ⚡ **Sub-Minute Dispatch** | Average 42-second call-to-unit dispatch pipeline with automated address validation and priority triage (Echo, Delta, Charlie). |
| 📋 **NEMSIS 3.5 ePCR** | Rapid electronic patient care reporting with vitals monitor synchronization, voice dictation, and hospital pre-notification. |
| 🏢 **Multi-Tenant Isolation** | Run dozens of private EMS companies independently on a single infrastructure with zero cross-tenant data leaks. |
| ⏱️ **Automated Call Milestones** | Precision timestamps for every phase: Call Intake → Unit Paged → En Route → On Scene → Hospital Arrival → In Service. |
| 🔒 **HIPAA & SOC 2 Ready** | End-to-end 256-bit AES encryption at rest and in transit, comprehensive audit logging, and strict BAA compliance. |

---

## 🧩 Platform Modules

1. **CAD & Dispatch Console:** Central dispatch screen displaying live fleet readiness, pending transfers, active emergency calls, and turn-by-turn routing.
2. **Crew Mobile Companion:** Responsive paramedic & EMT mobile interface for receiving run details, updating unit status with a single tap, and navigation.
3. **Electronic Patient Care Reports (ePCR):** Compliant clinical charting with built-in validation checks to eliminate billing rejections.
4. **Fleet & Telematics Suite:** Automated odometer tracking, preventive maintenance schedule triggers, and on-board medical inventory auditing.
5. **Hospital & Facility Portal:** Direct link for receiving emergency departments to view inbound patient status, vitals, and projected arrival times.
6. **Billing & Revenue Engine:** Seamless export to medical clearinghouses, automatic Medicare/Medicaid coding, and private payer claim generation.

---

## 🚀 Quick Start

### Run Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/arabiabdou453-cpu/ernconnect.git
   cd ernconnect
   ```

2. **Start the local server:**
   ```bash
   npm start
   ```
   *Or run directly:*
   ```bash
   node server.js
   ```

3. **Open in browser:**
   ```
   http://localhost:3000/
   ```

---

## 🏛️ Architecture

```
┌────────────────────────────────────────────────────────┐
│                      Client Layer                      │
├────────────────────────────────────────────────────────┤
│  • High-performance Tailwind CSS Dark Mode Design     │
│  • Responsive Flexbox & Grid for Command Centers       │
│  • Iconography by RemixIcon & FontAwesome 6            │
│  • Typography: Space Grotesk, Inter, & JetBrains Mono  │
├────────────────────────────────────────────────────────┤
│                     Runtime Layer                      │
├────────────────────────────────────────────────────────┤
│  • Zero-dependency Node.js HTTP Server                 │
│  • GitHub Pages Static Deployment with SSL             │
│  • Edge CDN Image Optimization                         │
└────────────────────────────────────────────────────────┘
```

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

<div align="center">
  <sub>Built with precision for emergency medical services by <a href="https://github.com/arabiabdou453-cpu">Abdou Arabi</a>.</sub>
</div>
