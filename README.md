# Small-3-Tier-Network-Model
This is a 3-Tier Network Architecture project built using Cisco Packet Tracer.
## Network Design

### 1. Core Layer (Layer 3 Switch)
- Handles inter-VLAN routing.
- Connects both distribution switches.
- IP routing enabled.

### 2. Distribution Layer (2 Switches)
- Connects access switches.
- Manages VLAN segmentation and policy control.

### 3. Access Layer (2 Switches)
- Hosts PCs and a network printer.
- Devices assigned to different VLANs.

## Devices Used
- 1 x Core Switch (Layer 3)
- 2 x Distribution Switches
- 2 x Access Switches
- 3 x PCs (VLAN 10, 20, 30)
- 1 x Network Printer (VLAN 30)
- 1 x DHCP Server
- 1 x DNS Server
- Telnet enabled for remote access

## IP Addressing (Examples)
- VLAN 10: 192.168.10.10
- VLAN 20: 192.168.20.10
- VLAN 30: 192.168.30.10 (PC & Printer)

## Features
- Inter-VLAN Routing via Core Switch
- Dynamic IP Allocation using DHCP
- Domain Resolution using DNS
- Remote Switch Access via Telnet
- Network segmentation using VLANs
  
