# DHCP Office Network Lab (Cisco Packet Tracer)

## Overview
This project simulates a small office network in Cisco Packet Tracer where a router provides automatic IP address assignment using DHCP.

## Objective
Build and configure a working network where client devices automatically receive IP configuration from the router and successfully communicate with each other.

## What I Configured
- Configured a Cisco 1941 router interface with a static IP address
- Enabled the router interface for network communication
- Configured the router as a DHCP server
- Created a DHCP address pool for client devices
- Reserved IP addresses for infrastructure devices
- Assigned DNS and default gateway settings
- Configured a server with a static IP
- Tested connectivity using ICMP ping

## Devices Used
- Cisco 1941 Router
- Cisco 2960 Switch
- 4 PCs
- 1 Server

## Network Configuration
Network: 192.168.10.0/24

Router / Default Gateway:
192.168.10.1

Server:
192.168.10.10

DHCP Client Range:
192.168.10.21+

DNS:
8.8.8.8

## Skills Demonstrated
- DHCP Configuration
- Router CLI Configuration
- IPv4 Address Management
- Static vs Dynamic Addressing
- Default Gateway Configuration
- DNS Configuration
- Network Troubleshooting
- ICMP Connectivity Testing

## Validation
Verified successful connectivity between clients, server, and router through ping testing.
