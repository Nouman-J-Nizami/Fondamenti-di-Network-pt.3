# Network Fundamentals Pt.3 – DHCP, DNS and HTTP Services

## Overview
This project demonstrates the configuration and validation of essential network services in Cisco Packet Tracer, including DHCP, DNS, and HTTP.

The objective was to simulate a small enterprise LAN where clients automatically obtain network settings, resolve internal domain names, and access web resources hosted on a local HTTP server.

## Technologies & Services
- Cisco Packet Tracer
- DHCP
- DNS
- HTTP
- IPv4 Networking
- LAN Configuration

## Project Activities

### DHCP Configuration
- Created and configured a DHCP server
- Defined IP address pool
- Configured subnet mask, default gateway, and DNS server
- Verified automatic IP assignment on client devices

### HTTP Server Configuration
- Deployed a web server with a static IP address
- Enabled HTTP service
- Verified web page accessibility from client hosts

### DNS Configuration
- Configured DNS service
- Created an A Record:
  - `epicode.internal → 192.168.1.90`
- Tested successful hostname resolution

### Connectivity Testing
- Verified DHCP lease assignment
- Tested DNS name resolution
- Accessed the web server using the domain name:
  - `http://epicode.internal`
- Analyzed the DNS Query → DNS Reply → HTTP GET → HTTP Response workflow

## Key Learning Outcomes
- DHCP automation and address management
- DNS hostname resolution
- HTTP service deployment
- Client-server communication flow
- OSI model application in real-world networking scenarios

## Author
Nouman J Nizami – Network & Cybersecurity 
