# Ubuntu Server Post-Install Systems Configuration

This repository documents a **phase-based Ubuntu Server post-installation baseline lab** focused on establishing a secure, predictable, and operationally sound system before any services are deployed into an operational environment. 

The purpose of this lab is not to install applications, but to demonstrate **systems administration discipline**.

The decisions and actions that immediately follow an operating system installation that determine whether a server becomes reliable infrastructure or a long-term liability.

---

## Lab Overview

- **Operating System:** Ubuntu Server 24.04 LTS  
- **Environment:** Hyper-V Virtual Machine  
- **Type:** Hands-on systems administration lab  
- **Focus:** Post-installation configuration baseline & hardening  

This lab reflects how an Ubuntu Server system would realistically be prepared in a **production-minded environment** prior to hosting services.

---

## 🛠️ Tech Used

- Linux Ubuntu 24.04
- Lenovo Thinkpad E16 Gen 2
- Windows 11 Pro
- Hyper-V
- Ubuntu Server 24.04 LTS
- GitHub Pages for documentation
- Visual demonstration and screenshots

---

🖥️ **Live Project Webpage:**  
👉 [Hyper-V Lab](https://mark-thompson01.github.io/MTPortfolio/Current%20Projects%20&%20Studies/Ubuntu-Server%20Post-Install/)


---

## Lab Structure

The lab is organized into **six operational phases**, mirroring how real infrastructure work is planned and executed.

### Phase 1 — Initial Validation & Environment Awareness
- Verify OS version and kernel
- Inspect system resources (disk, memory, uptime)
- Establish situational awareness before making changes

### Phase 2 — System Updates & Package Baseline
- Apply all available system updates
- Ensure the server starts from a known-good, patched state

### Phase 3 — Identity & Privilege Management
- Create non-root administrative users
- Enforce least privilege
- Reduce operational and security risk

### Phase 4 — Secure Remote Access (SSH)
- Disable direct root login
- Enforce key-based authentication
- Harden remote access pathways

### Phase 5 — Network Configuration & Host Identity
- Verify network configuration
- Establish hostname and local resolution
- Ensure predictable system identity

### Phase 6 — System Readiness & Operational Baseline
- Confirm system state
- Validate readiness for service deployment
- Establish a stable operational foundation

Each phase is visually documented with screenshots and organized to reflect real-world administrative workflows.


---

## 📘 What I Learned

- How to setup and configure a Ubuntu Server VM 
- Best configuration practices post Ubuntu Server OS installation
- How Ubuntu server gets installed as a "headless system" by default (Meaning no GUI environment, just terminal)
- Linux Ubuntu Server Command-Line administration
- Implementing server security-hardening measures (e.g., SSH, UFW, Automatic Path Management, Access Control, etc)


---

## 📁 More from Me

Visit my full GitHub Pages portfolio to explore additional projects:

🔗 [MTPortfolio – Full Project Index](https://mark-thompson01.github.io/MTPortfolio/)


---

## 🛡️ License

The content and structure of this repository (including guides, demonstrations, and screenshots) are licensed under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).  
You're welcome to share, adapt, or build upon it — just please provide credit where it's due.

