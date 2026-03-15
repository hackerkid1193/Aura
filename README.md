# Aura Ecosystem 🌌

A unified automation framework designed to streamline workflows across Windows, macOS, and Cloud environments.

## 📦 The Suite
* **Aura-PS:** Native PowerShell automation for restricted Windows environments.
* **Aura-Py:** Cross-platform Python tools for advanced data handling and logic.
* **Aura-Mac:** Zsh-based shell scripts optimized for macOS productivity.

## 🚀 Quick Start
Choose your environment and run the corresponding entry script:

### Windows (PowerShell)
`.\Aura-PS\Core.ps1 -Action sort`

### Linux/Cloud (Python)
`python Aura-Py/main.py --task timer`

### macOS (Zsh)
`./Aura-Mac/aura.sh --cleanup`

## 🛡️ Integrity & Licensing
To ensure the suite is running correctly and has not been covertly edited or tampered with, you must use the **Aura Guard** handler.

## 🚩 Anti-Tamper Protocol (ATP)
The Guard scripts are equipped with **ATP**. If a signature mismatch is detected:
* **Windows:** Triggers a terminal lockdown and session termination.
* **Python:** Initiates a memory dump simulation and process kill.
* **macOS:** Revokes script execution privileges and triggers an audible alert.

**To safely update Aura:**
1. Make your changes.
2. Run the platform Guard with the `seal` argument to update the digital signature.

## 🛠️ Unified Features
- **File Warden:** Consistent file organization logic across all OS types.
- **Neuro-Focus:** Synced Pomodoro and task-tracking logic.
- **Brain Dump:** Universal timestamped logging.

