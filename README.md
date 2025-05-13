# 🏢 Real Estate Company Secure Network Infrastructure (Cisco Packet Tracer)

## 📌 Objective
Design and implement a secure, scalable, and reliable network for a small real estate business with over 30 employees. The network supports seamless internal communication, guest access, remote work, and robust cybersecurity through segmentation, encryption, and proactive threat management.

## 🛠️ Technologies & Features Implemented

### 🔐 **Security**
- **VLAN Segmentation** by department and function (Internal, Guest, Server)
- **Cisco ASA Firewall** for advanced perimeter defense
- **Access Control Lists (ACLs)** to control inter-VLAN and outbound traffic
- **AAA Authentication** using RADIUS with centralized login control
- **802.1X Wireless Authentication** with RADIUS for secure Wi-Fi
- **SSHv2 Remote Management** with session timeout & login tracking
- **Intrusion Detection & Prevention System (IDPS)**
- **Account Lockout, Password Policy & Logging** enforcement
- **Site-to-Site VPN (IPsec)** for secure remote office connectivity

### 📶 **Connectivity & Routing**
- **Inter-VLAN Routing** with Layer 3 Switch
- **Dynamic Routing using OSPF**
- **Static & Default Routes** for internal and internet-bound traffic
- **Wireless LAN Controller (WLC)** with LWAPs (CAPWAP protocol)
- **Port Address Translation (PAT)** for internet access

### 🔧 **Switching & Optimization**
- **Rapid-PVST+**, **PortFast**, **BPDU Guard** for Layer 2 loop prevention
- **LACP / PAgP** EtherChannel for redundancy and performance
- **Port Security**, unused port shutdown, and black-hole VLANs
- **CDP/LLDP Disabled** on unused ports for security
- **Manual Speed/Duplex Configuration** on unused interfaces

### 📡 **Infrastructure Services**
- **DHCP**, **DNS**, **NTP**, **SYSLOG**, **TFTP**
- **Web Server**, **Email Server**
- **Logging with Timestamps**, **Service Password Encryption**

### ☎️ **Voice over IP (VoIP)**
- **Dedicated Voice VLANs** for IP Phones
- **QoS Considerations** for optimal call quality

## 🧩 Project Scope
This project simulates a fully operational small business network architecture using **Cisco Packet Tracer**. It demonstrates advanced networking principles including:
- Network segmentation
- Security hardening
- Remote access setup
- Centralized management

## Network Design Architecture
```mermaid
graph TD
    A[Internet] --> B[Firewall]
    B --> C[Core Switch]
    C --> D[Internal VLANs]
    C --> E[Server VLAN]
    C --> F[Guest VLAN]
    D --> G[Employee Workstations]
    E --> H[Application Server]
    F --> I[Guest Wi-Fi]



🎯 **This project is ideal for:**
- Networking students
- CCNA/CCNP learners
- Small business infrastructure designers
- Security-focused network engineers




