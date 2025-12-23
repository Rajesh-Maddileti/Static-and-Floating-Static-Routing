Static & Floating Static Routing using Cisco Packet Tracer

This repository demonstrates a CCNA-level hands-on networking lab implementing both Static Routing and Floating Static Routing in a multi-router topology using Cisco Packet Tracer.

The lab focuses on manual route configuration, path selection, and failover behavior using administrative distance.

🎯 Objective
Configure and verify static routing between multiple LANs
Implement floating static routes as a backup path
Validate automatic failover during primary link failure
Ensure reliable end-to-end connectivity

🧩 Lab Topology
Four Cisco routers interconnected via Gigabit Ethernet
Two LAN networks connected using Layer 2 switches
End devices used for connectivity testing
Redundant paths configured for floating static routing

🗺️ Network Topology
[View Network Topology](topology.jpeg)
⚙️ Configuration Summary
IPv4 addressing and subnetting for all LAN and WAN links
Router interface configuration using no shutdown
Primary static routes using the ip route command
Floating static routes configured with higher administrative distance
Configuration saved using write memory

🖥️ Router Configuration Snapshots

### Router R1
- [R1 Interface & Static Route Configuration](R1-config.jpeg)

### Router R2
- [R2 Static Routing Configuration](R2-config.jpeg)

### Router R3
- [R3 LAN & Routing Configuration](R3-config.jpeg)

### Router R4
- [R4 Floating Static Route Configuration](R4-config.jpeg)

📂 Packet Tracer File

- [Download Packet Tracer Lab File](static-floating-routing.pkt)


📘 Concepts Practiced

Static Routing
Floating Static Routing
Administrative Distance
IPv4 Addressing & Subnetting
Router Interface Configuration
Redundancy & Failover
ICMP Connectivity Verification
Basic Network Troubleshooting
