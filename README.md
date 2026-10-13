# Campus Network Design and Simulation

A university campus network design developed for **EN 2150 – Communication Network Engineering** at the University of Moratuwa. The project includes a campus backbone and a departmental local area network, modeled in Cisco Packet Tracer.

## Overview

The design explores a hierarchical star-ring hybrid campus backbone with redundant core switches and a separate ENTC departmental LAN. The accompanying report describes network segmentation, addressing, equipment selection, and connectivity tests.

## Main features

- Redundant core design with primary and secondary multilayer switches
- Spanning Tree Protocol (STP) for loop prevention and alternate paths
- VLAN segmentation and IEEE 802.1Q trunking
- IPv4/IPv6 dual-stack addressing plan
- Departmental access and distribution switching
- Wireless access point integration
- Connectivity checks documented using Packet Tracer

## Repository contents

| File | Description |
| --- | --- |
| [`simulations/ENTC_Network.pkt`](simulations/ENTC_Network.pkt) | ENTC departmental LAN simulation |
| [`simulations/Uni_Backbone_new.pkt`](simulations/Uni_Backbone_new.pkt) | University backbone simulation |
| [`docs/Network_Design.pdf`](docs/Network_Design.pdf) | Design report, component breakdown, and simulation results |

## How to explore

1. Install **Cisco Packet Tracer**.
2. Open either `.pkt` file from the `simulations` folder.
3. Inspect the network topology and device configurations.
4. Refer to the [design report](docs/Network_Design.pdf) for the intended architecture and documented tests.
5. Run connectivity tests within Packet Tracer as needed.

## Project context

Developed as a group coursework project by **Team Networkians**, Department of Electronic and Telecommunication Engineering, University of Moratuwa.

## Notes

The IPv6 prefixes in the report use the documentation prefix `2001:db8::/32`. This repository presents an educational simulation and design, not a production deployment. Availability and wireless coverage targets described in the report are design objectives rather than independently verified operational guarantees.
