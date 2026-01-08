# VLAN Routing & DHCP – Cisco Packet Tracer

## Overview
This project demonstrates a basic enterprise-style network using Cisco Packet Tracer. 
The network is segmented using VLANs and provides inter-VLAN routing and DHCP services 
via a router-on-a-stick configuration.

## Network Features
- VLAN 10 and VLAN 20
- Access and trunk ports
- Router-on-a-stick (G0/0/0 subinterfaces)
- DHCP configured on the router
- End-to-end connectivity verified with ping

## IP Addressing
| VLAN | Network | Gateway |
|----|----|----|
| 10 | 192.168.10.0/24 | 192.168.10.254 |
| 20 | 192.168.20.0/24 | 192.168.20.254 |

## Devices Used
- Cisco 2960 Switch
- Cisco Router (G0/0/0)
- Multiple PCs

## Verification
- `show ip dhcp binding`
- `show vlan brief`
- `show interfaces trunk`
- Successful inter-VLAN pings

## Files
- `Small_Office_Network.pkt` – Packet Tracer topology
- `router-config.txt` – Router configuration
- `switch-config.txt` – Switch configuration
- `topology.png` – Network diagram
