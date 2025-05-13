Secure Network Infrastructure for Real Estate Company
Project Overview
This project designs and implements a secure, reliable, and scalable network infrastructure for a small real estate business with 30+ employees. The network ensures seamless connectivity for workstations, printers, servers, and guest Wi-Fi while enforcing strong cybersecurity measures to protect against threats.

Key Features
✔ VLAN Segmentation – Isolates traffic by department (e.g., HR, Finance, Sales) for improved security and performance.
✔ Secure Remote Access – VPN support for employees working remotely.
✔ Multi-Zone Security – Separates internal, guest, and server networks with firewall policies.
✔ Wireless Access – Dedicated employee and guest Wi-Fi with proper authentication.
✔ Centralized Management – AAA (Authentication, Authorization, Accounting), IDPS (Intrusion Detection & Prevention), and logging via SYSLOG.
✔ Essential Services – DHCP, DNS, NTP, HTTP/HTTPS, and TFTP for efficient operations.

Network Design
The infrastructure follows a layered security approach:

1. VLAN Segmentation
Internal VLANs (HR, Finance, IT, Sales)

Guest VLAN (Internet-only access)

Server VLAN (Hosts critical services)

2. Security Measures
Firewall Rules – Restrict unauthorized access between VLANs.

IDPS – Monitors and blocks malicious traffic.

VPN – Encrypted remote access for employees.

AAA (RADIUS/TACACS+) – Controls user access to network devices.

3. Wireless Network
Employee Wi-Fi (WPA2-Enterprise with 802.1X authentication)

Guest Wi-Fi (Captive portal with limited bandwidth)

4. Core Services
DHCP & DNS – Automated IP assignment and domain resolution.

NTP – Time synchronization across devices.

Centralized Logging – SYSLOG for monitoring and audits.

Why This Design?
Improved Security – Prevents lateral movement of threats with VLANs and firewalls.

Better Performance – Reduces broadcast traffic via segmentation.

Compliance – Helps meet data protection regulations for real estate businesses.

Scalability – Supports future growth with modular design.
