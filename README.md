# Secure Network Infrastructure for Real Estate Company

## Project Overview
This project designs and implements a secure, reliable, and scalable network infrastructure for a small real estate business with 30+ employees. The network ensures seamless connectivity while enforcing strong cybersecurity measures.

## Key Features
- **VLAN Segmentation** - Department-based isolation (HR, Finance, Sales)
- **Secure Remote Access** - Enterprise-grade VPN support
- **Multi-Zone Security** - Firewall-protected internal/guest/server segments
- **Wireless Access** - Separate employee and guest Wi-Fi networks
- **Centralized Management** - AAA, IDPS, and SYSLOG monitoring
- **Core Services** - DHCP, DNS, NTP, HTTP/HTTPS, TFTP

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
