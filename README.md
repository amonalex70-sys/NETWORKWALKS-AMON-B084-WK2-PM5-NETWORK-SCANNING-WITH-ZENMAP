<div align="center">

# Network scanning, discovery and network mapping using Zenmap

This is a strong, technically relevant heading. It covers the three main activities of your project.

Network discovery and host identification using Zenmap on Kali Linux.

<p align="center">
  <img src="https://img.shields.io/badge/Project-Network%20Scanning-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Tool-Zenmap-0070C0?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Engine-Nmap-238F89?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Operating%20System-Kali%20Linux-E87500?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Scan%20Type-Ping%20Scan-C00000?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Focus-Network%20Discovery-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Platform-GitHub-404040?style=flat-square&labelColor=0070C0&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Program-NetworkWalks-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Practice-Ethical%20Hacking-E87500?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Mentor-Waqas%20Karim%20(CCIE)-C00000?style=flat-square" />
</p>
</div>


## 🛡️ Network Discovery and Scanning Overview

This project documents the use of **Zenmap on Kali Linux** to perform network scanning, discover active hosts, and identify devices connected to a local network.

The practical exercises involve identifying live hosts, examining their IP and MAC addresses, and generating a network topology map to understand the structure of the local network.

## 🎯 Project Objectives

The primary objectives of this project are to:

- Install and configure Zenmap on Kali Linux.
- Identify the local IP address and LAN subnet.
- Perform network scanning using Zenmap's Ping Scan.
- Discover active hosts within the local network.
- Identify the IP and MAC addresses of discovered hosts.
- Determine the number of active devices on the network.
- Generate and export a network topology map in PDF format.
- Understand network discovery and scanning techniques using Zenmap.

## 🛡️ Lab Purpose and Security Scope

This project provides practical experience in network scanning and host discovery using Zenmap on Kali Linux. It focuses on identifying active devices and understanding the structure of a local network.

The practical activities include:

- Discovering live hosts within a local network.
- Identifying IP and MAC addresses of active devices.
- Examining network connectivity and host availability.
- Visualizing network structure through topology mapping.
- Understanding network scanning and reconnaissance techniques.

**⚠️ Security Notice:** Network scanning must only be performed on networks you own or have explicit permission to assess. Unauthorized scanning is strictly prohibited.

## ⚙️ Cybersecurity Lab System Specifications

| Component | Configuration |
|---|---|
| Host Operating System | Kali Linux 2026.3 |
| Host RAM | 8 GB |
| Processor | Intel Core i5 |
| Network Scanning Tool | Zenmap |
| Scanning Engine | Nmap |
| Scan Type | Ping Scan |
| Network Environment | Local Area Network (LAN) |
| Network Address | To be determined |
| Local IP Address | To be determined |
| Default Gateway | To be determined |
| DNS Server | To be determined |


## ⚙️ Zenmap Installation and Setup Steps

## Step 1: Install Zenmap on Kali Linux

Zenmap, the graphical user interface for Nmap, was installed on Kali Linux to provide a visual interface for network scanning, host discovery, and network mapping.

**Installation command:**
```bash
sudo apt update
sudo apt install zenmap -y
```

## Step 2: Identify the Local IP Address and Network Subnet

Identify the local machine's IP address, network interface, and LAN subnet to determine the network range for scanning with Zenmap.

**Command:**
```bash
ip addr
```

**Network Configuration:**

| Parameter | Identified Value |
|---|---|
| Network Interface | WLAN |
| Local IP Address | `192.168.8.150/24` |
| Subnet Mask | `255.255.255.0` |
| Network ID | `192.168.8.0/24` |


## Step 3: Launch Zenmap and Configure the Scan

Open Zenmap from the Kali Linux applications menu. Enter your local network ID in the **Target** field using preffered CIDR notation then select **quick scan** from the **Profile** dropdown menu.

<img width="1035" height="211" alt="Zenmap" src="https://github.com/user-attachments/assets/8c820dd4-3519-4c36-b35b-838c78b41022" />


## Step 4: Perform Network Discovery

Click the **Scan** button to start the Quick Scan. Zenmap will scan the specified network and display discovered hosts and their available information.

**Identified Hosts:**

| Host | IP Address | Description |
|---|---|---|
| Router | `192.168.8.1` | Network gateway |
| Host PC | `192.168.9.150` | Local computer |









