# Basic-Networking-Lab

This repository contains a simple networking lab created using Cisco Packet Tracer. The lab demonstrates how to connect two PCs through a switch and configure basic IP connectivity between them.

## Objective
The goal of this lab is to familiarize you with basic network configurations and testing connectivity using ICMP (ping).

## Network Topology
The network consists of:
- 2 PCs
- 1 Switch (2960)

### IP Configuration:
- **PC0**: 192.168.1.1 / 255.255.255.0
- **PC1**: 192.168.1.2 / 255.255.255.0

### Steps to Reproduce:

1. **Add Devices**:
   - Add two PCs and one switch to the Packet Tracer workspace.
   - Connect PC0 to the switch using FastEthernet0/1.
   - Connect PC1 to the switch using FastEthernet0/2.

2. **Configure the IPs**:
   - On **PC0**, set the IP to `192.168.1.1` and subnet mask `255.255.255.0`.
   - On **PC1**, set the IP to `192.168.1.2` and subnet mask `255.255.255.0`.

3. **Test Connectivity**:
   - From PC0, open the Command Prompt and ping PC1 by typing: `ping 192.168.1.2`.

## Screenshots
![Packet Tracer Lab](./images/network-lab.png)
![image](https://github.com/user-attachments/assets/6570ec5a-64e4-411b-af34-e7a3b00d7b89)


## License
This project is licensed under the MIT License.


