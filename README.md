# SafeSight Edge: An Edge AI-Based Industrial Safety Intelligence Platform with Digital Twin

## Overview

SafeSight Edge is an Edge AI-powered industrial safety platform designed to improve workplace safety in factories and heavy machinery environments. The project combines computer vision, wearable sensing, predictive risk intelligence, and Digital Twin visualization to help identify unsafe situations before accidents occur.

Instead of analysing individual safety events independently, SafeSight Edge integrates environmental observations and worker state information to estimate an overall workplace risk level and support proactive decision-making.

---

## Problem Statement

Industrial workplaces involve continuous interaction between workers, heavy machinery, and hazardous work areas. Although CCTV surveillance, PPE policies, and safety procedures are widely adopted, accidents continue to occur because many unsafe situations are identified only after they become critical.

Most existing systems focus on isolated events such as PPE violations or restricted zone entry. They rarely combine multiple safety factors to understand the complete workplace context and overall risk.

SafeSight Edge aims to bridge this gap by providing an integrated, intelligent, and proactive industrial safety platform.

---

## Proposed Solution

The proposed solution consists of three intelligence layers:

### Environment Intelligence

* Worker detection
* PPE compliance detection
* Heavy machinery detection
* Restricted zone monitoring
* Unsafe behaviour detection
* Crowd congestion analysis

### Human State Intelligence

* Heart rate monitoring
* Heart rate variability (HRV) for stress estimation
* Motion monitoring
* Body temperature (where available)
* Fall event monitoring

### Predictive Risk Intelligence

* Combines environmental observations and wearable data
* Calculates an overall workplace risk score
* Displays live safety information using a Digital Twin dashboard
* Generates recommendations through an AI Safety Copilot

---

## System Workflow

Industrial Cameras + Wearable Devices

↓

Environment Intelligence

↓

Worker Tracking

↓

Unsafe Behaviour Analysis

↓

Human State Intelligence

↓

Predictive Risk Intelligence

↓

Digital Twin Dashboard

↓

AI Safety Copilot

↓

Supervisor Alerts & Recommended Actions

---

## Technology Stack

| Component            | Technology                |
| -------------------- | ------------------------- |
| Programming Language | Python                    |
| Computer Vision      | OpenCV                    |
| Deep Learning        | PyTorch                   |
| Object Detection     | YOLOv8                    |
| Object Tracking      | ByteTrack                 |
| Risk Prediction      | Random Forest             |
| Dashboard            | Streamlit                 |
| Digital Twin         | Interactive Web Dashboard |
| IDE                  | Visual Studio Code        |
| Version Control      | Git & GitHub              |

---

## Planned Modules

* Environment Intelligence
* Human State Intelligence
* Predictive Risk Intelligence
* Digital Twin Dashboard
* AI Safety Copilot
* Analytics Dashboard

---

## Current Status

This project is currently under active development as part of **Tata Technologies InnoVent 2026**.

The current repository includes:

* Project planning
* System architecture
* User interface prototype
* Presentation materials
* Model development roadmap

Implementation of the AI models and system integration will be completed in subsequent development phases.

---

## Future Scope

* Edge AI deployment on embedded hardware
* Wearable device integration
* Real-time Digital Twin synchronization
* Advanced predictive risk models
* Intelligent AI Safety Copilot
* Industrial IoT integration

---

## Team

**Project:** SafeSight Edge

Developed as part of **Tata Technologies InnoVent 2026 Hackathon**.

---

## License

This project is intended for educational, research, and innovation purposes.
