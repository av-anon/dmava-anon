# Distributed Multi-AV Architecture (DMAVA)

*A distributed simulation architecture for autonomous vehicles (AVs) integrating Autoware Universe, AWSIM Labs, and Zenoh for synchronized multi-vehicle operation.*

![Autoware](https://img.shields.io/badge/Autoware-2024.11-blue?logo=autoware)
![AWSIM Labs](https://img.shields.io/badge/AWSIM%20Labs-Unity-green?logo=unity)
![ROS 2 Humble](https://img.shields.io/badge/ROS2-Humble-purple?logo=ros)
![Zenoh](https://img.shields.io/badge/Zenoh-1.4.0-orange?logo=zenoh)
![License](https://img.shields.io/badge/License-Apache%202.0-blue?logo=apache)

The **DMAVA** provides a complete setup for running **Autoware** and **AWSIM Labs** in a multi-host, multi-vehicle simulation environment for **AVs**, maintaining synchronized perception, localization, planning, and control pipelines.

## Features

- Distributed simulation across multiple hosts
- Zenoh-based ROS 2 topic synchronization
- Multi-vehicle coordination with namespaced topics
- Modular design
- Scalable to larger fleets and more complex simulation scenarios

---

## Getting Started

To get started with running the DMAVA, see the [System Architecture](GettingStarted/SystemArchitecture/index.md) page.

For a condensed list of frequently used commands, see the [Developer Quick Commands](DeveloperGuide/QuickCommands/index.md) page.
