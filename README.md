# MANET Simulation Project

This repository contains the source code and results for simulating Mobile Adhoc Networks (MANETs) using NS-3. The project explores routing protocols and their performance based on QoS metrics, using tools like NetAnim and Wireshark for visualization and analysis.

---

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Setup](#setup)
- [Simulation Results](#simulation-results)
  - [Node Layout](#node-layout)
  - [QoS Metrics](#qos-metrics)
  - [Packet Analysis](#packet-analysis)
- [Usage](#usage)
- [Contributors](#contributors)

---

## Introduction

This project simulates a MANET environment using NS-3 to compare proactive and reactive routing protocols. The results include node placement, QoS metrics, and packet flow analysis based on PCAP files visualized in Wireshark.

---

## Features
- Visualization of node placement using NetAnim.
- Analysis of routing protocols based on QoS metrics (e.g., latency, throughput).
- Packet flow analysis with Wireshark.

---

## Requirements
- NS-3
- NetAnim
- Wireshark
- Ubuntu 20.04+ (recommended)

---

## Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/habstrakT808/MANET-Routing-Simulation-with-NS-3.git
   ```
2. Build the NS-3 environment and run the simulation file:
   ```bash
   ./waf --run manet-routing-compare
   ```
3. Visualize results using NetAnim and Wireshark.

---

## Simulation Results

### Node Layout
Screenshots of the initial node placement in the simulation visualized using NetAnim:

*Example Screenshot Placeholder*

![AODV NODE 20](https://github.com/user-attachments/assets/13e81eb6-4955-4cdc-b2eb-fe52ff533c4f)

---

### QoS Metrics
Average performance metrics for the simulation (Example : AODV Node 20):

| Metric         | Value |
|----------------|-------|
| Average Delay (s)   | 0.004563 |
| Average Jitter (s) | 0.006817 |
| Average Packet Loss (%) | 46.21 |

---

### Packet Analysis
Example flow of source and destination packets visualized in Wireshark (PCAP file):

![PCAP AODV 20](https://github.com/user-attachments/assets/9900c0ac-0eba-4c18-803f-368fcd7d65a7)

---

## Usage
To analyze the results:
- Open the PCAP file in Wireshark: `path/to/simulation.pcap`
- View the node movement and communication pattern in NetAnim.

---

## Contributors
- **Your Name** ([GitHub Profile](https://github.com/habstrakT808))
