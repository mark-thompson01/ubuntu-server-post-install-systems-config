# Ubuntu Server – Post-Installation Baseline & Hardening Lab

This repository documents a **phase-based Ubuntu Server post-installation baseline lab** focused on establishing a secure, predictable, and operationally sound system before any services are deployed.

The purpose of this lab is not to install applications, but to demonstrate **systems administration discipline** — the decisions and actions that immediately follow an operating system installation that determine whether a server becomes reliable infrastructure or a long-term liability.

---

## Lab Overview

- **Operating System:** Ubuntu Server 24.04 LTS  
- **Environment:** Hyper-V Virtual Machine  
- **Type:** Hands-on systems administration lab  
- **Focus:** Post-installation baseline & hardening  

This lab reflects how an Ubuntu Server system would realistically be prepared in a **production-minded environment** prior to hosting services.

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

## Repository Contents

