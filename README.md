# Network Optimization Script

This repository contains a script that optimizes various TCP/IP and network settings on Windows machines. The script modifies system parameters to improve network performance by tweaking TCP settings, disabling unnecessary services, and adjusting network adapter configurations. It is aimed at improving network throughput, latency, and overall system efficiency.

## Features

- **TCP/IP Optimization**: Adjusts various TCP parameters like autotuning, window size, and more.
- **Disabling Unnecessary Services**: Disables services like Teredo, 6to4, and ISATAP to reduce network overhead.
- **PowerShell Integration**: Uses PowerShell to disable Link State Offload (LSO) and manage adapter power settings.
- **Registry Tweaks**: Modifies Windows registry for network-related settings like ICMP redirects, PMTU discovery, and more.

### Prerequisites
- A Windows-based machine (Windows 7/8/10/11).
- Administrator privileges to run the script.
