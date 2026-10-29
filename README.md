# Multi-Regional University Network (Cisco Packet Tracer)

A multi-campus university network designed and simulated in **Cisco Packet Tracer**. The project models a university with several regional campuses connected into a single, organized network, and demonstrates core computer networking concepts such as network design, IP addressing, switching, routing, and inter-campus connectivity.

> Developed as a Computer Networks course project.

---

## Table of Contents

- [Overview](#overview)
- [Project Objectives](#project-objectives)
- [Network Design](#network-design)
- [Key Features](#key-features)
- [Technologies & Tools](#technologies--tools)
- [Getting Started](#getting-started)
- [Repository Structure](#repository-structure)
- [Testing & Verification](#testing--verification)
- [Future Improvements](#future-improvements)
- [Author](#author)

---

## Overview

Modern universities operate across multiple campuses and regions, and each location needs reliable local connectivity as well as secure, efficient communication with the other campuses. This project simulates that environment in Cisco Packet Tracer.

The simulation includes the regional campus networks, the devices that connect them, and the end-user devices on each campus, all configured to communicate with one another.

## Project Objectives

- Design a scalable multi-regional network for a university.
- Plan and apply a structured IP addressing scheme.
- Configure switches and routers to connect each campus.
- Enable communication between devices in different regions.
- Verify the network through connectivity tests.

## Network Design

<!-- Add a screenshot of your topology here, for example:
![Network Topology](images/topology.png)
-->

| Item | Details |
|------|---------|
| Number of regions / campuses | _add here_ |
| Routers | _add here_ |
| Switches | _add here_ |
| End devices (PCs, servers, etc.) | _add here_ |
| Addressing scheme | _add here (e.g., subnets per campus)_ |
| Routing | _add here (static / dynamic protocol used)_ |
| Other services | _add here (DHCP, DNS, VLANs, etc., if used)_ |

## Key Features

- Multiple regional campus networks interconnected into one university network
- Structured IP addressing across all regions
- Router and switch configuration for inter-region communication
- End-device connectivity within and between campuses
- Fully simulated in Cisco Packet Tracer, with no physical hardware required

## Technologies & Tools

- **Cisco Packet Tracer** (network simulation)
- **Cisco IOS** command-line configuration

## Getting Started

### Prerequisites

- [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer) installed (free with a Cisco Networking Academy account)

### Run the project

1. Clone the repository:

   ```bash
   git clone https://github.com/nadirhussainstd-gif/Multi-Regional-University-Network-Cisco-Packet-Tracer-.git
   cd Multi-Regional-University-Network-Cisco-Packet-Tracer-
   ```

2. Open `Computer_Network_Project.pkt` with Cisco Packet Tracer (double-click it, or use **File → Open**).
3. Wait for the topology to load, then switch to **Simulation** mode to watch packets travel, or use **Realtime** mode for normal testing.

> **Note:** If the file does not open, make sure your Packet Tracer version is the same as or newer than the version used to create it.

## Repository Structure

```
.
├── Computer_Network_Project.pkt   # Packet Tracer project file
└── README.md                      # Project documentation
```

## Testing & Verification

You can verify the network from any end device in Packet Tracer:

1. Open a PC and go to **Desktop → Command Prompt**.
2. Check the device's IP configuration:

   ```
   ipconfig
   ```

3. Test connectivity within the same campus and across regions:

   ```
   ping <destination-ip>
   ```

4. Use **Simulation mode** to trace packets between campuses and confirm the path they take.

Successful replies from devices in other regions confirm that inter-campus routing is working.

## Future Improvements

- Add VLANs to separate departments (students, faculty, administration)
- Add network security (access control lists, port security)
- Add redundancy for higher availability
- Add wireless access points for campus Wi-Fi

## Author

**Nadir Hussain**
Department of Information Security, Faculty of Computing
The Islamia University of Bahawalpur

GitHub: [@nadirhussainstd-gif](https://github.com/nadirhussainstd-gif)

---

If you find this project useful, consider giving it a ⭐ on GitHub.
