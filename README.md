markdown
# WireGuard VPN Lab — Microsoft Azure

## Overview
Built and deployed a fully functional VPN server in Microsoft Azure 
using WireGuard. This lab demonstrates hands-on skills in Linux 
administration, network security, and cloud infrastructure relevant 
to Cybersecurity and IT roles.

## Tools & Technologies
- Microsoft Azure (Cloud Infrastructure)
- Ubuntu Server 24.04 LTS
- WireGuard VPN
- SSH (Secure Shell)
- Linux Command Line
- UFW Firewall / IPTables

## What I Built

### 1. Cloud Infrastructure
Deployed an Ubuntu Server 24.04 LTS virtual machine in Microsoft 
Azure (East US 2 region). Configured inbound security rules for 
SSH (port 22) and WireGuard UDP (port 51820).

### 2. Server Configuration
- Connected to the server remotely via SSH from macOS
- Updated the server and installed WireGuard
- Enabled IPv4 forwarding for traffic routing
- Configured IPTables rules for NAT and packet forwarding

### 3. VPN Tunnel Setup
- Generated server and client encryption key pairs
- Configured the WireGuard server interface (wg0)
- Set up peer configuration with client public key
- Assigned VPN subnet (10.0.0.1/24)

### 4. Client Configuration
- Generated client-side WireGuard config on macOS
- Imported tunnel config into WireGuard Mac app
- Connected and verified traffic routing through Azure server

### 5. Verification
- Confirmed VPN connection via WireGuard handshake
- Verified public IP changed to Azure server IP (74.249.85.165)
- ISP showed as Microsoft Corporation confirming successful tunnel

## Screenshots
| Screenshot | Description |
|---|---|
| Azure Portal | VPN-Server-01 VM running in cloud |
| WireGuard App | Active tunnel with successful handshake |
| IP Verification | Public IP showing Azure server address |

## Skills Demonstrated
- Linux server administration (Ubuntu)
- SSH remote access and management
- VPN configuration and tunnel setup
- Network security and traffic routing
- Cloud VM deployment and configuration (Azure)
- Encryption key generation and management

## Resume Bullet Point
"Deployed and configured a WireGuard VPN server on Ubuntu 24.04 
in Microsoft Azure. Managed SSH access, IPTables rules, and 
encryption key pairs. Verified secure tunnel routing from macOS 
client to cloud server."
```
