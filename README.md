# 🌐 BGP Masterclass: From Zero to Hero

Welcome to the official repository for the **BGP Masterclass** YouTube series.
This course is designed to take you from a complete beginner to an advanced BGP expert (CCIE level), using a "slow-pace" learning approach.

## 📺 The Series
You can watch the full playlist on YouTube here: **https://www.youtube.com/watch?v=s6V7PClhuN8**

## 🗺️ Lab Topology (The Butterfly)
We use a consistent 10-router topology throughout the series, simulating a real-world Service Provider environment.

![BGP Lab Topology](images/topology-full.png)

### Network Roles:
* **AS 65000 (Our Core):** R1, R2 (Edge) & R3, R4 (Core/RR).
* **AS 100 & AS 200 (Internet):** R5 (ISP1) & R6 (ISP2).
* **AS 300 (IXP):** R7 acts as an Internet Exchange Point.
* **Customers:** R8, R9, R10 simulating various client scenarios (L3VPN, Dual-homing).

## 🚀 Getting Started

If you want to follow along with the videos, you need to set up the initial IP addressing and OSPF (IGP) routing within AS 65000.

1.  **Download the Configs:** Go to the folder [`00_initial_bootstrap`](./00_initial_bootstrap).
2.  **Apply to Routers:** Copy and paste the content of each text file into the corresponding router CLI.
3.  **Verify:** Ensure R1 can ping R4's loopback (`4.4.4.4`).

### Hardware/Software Used
* **Platform:** Cisco CML (Modeling Labs) / EVE-NG / GNS3
* **Images:** * CSR1000v (for Edge Routers R1, R2)
    * IOSv (for Core & External Routers)

## 📂 Repository Structure

* `/00_initial_bootstrap` - Base configurations (IPs + OSPF) to get the lab ready for Episode 1.
* `/01_basic_peering` - Final configurations after Episode 2.
* *(More folders will be added as new episodes are released)*

## 🤝 Contributing
Found a typo? Pull requests are welcome!

---
*Created by [Your Name / Channel Name]*
