🏢 **Trading Floor Support Center: Secure & Redundant Network Infrastructure (Cisco Packet Tracer)**

📌 **Objective**
The primary goal of this project is to design and implement a secure, scalable, and highly available network infrastructure for a Trading Floor Support Center employing 600 staff members. The solution covers a three-story building with six distinct departments, ensuring seamless internal communication, redundant internet connectivity, and robust cybersecurity through advanced segmentation and threat mitigation
🛠 Technologies & Features Implemented

🔐 **Security (Cybersecurity)**
* **VLAN Segmentation:** Traffic isolation across 6 departments (Sales, HR, Finance, Admin, ICT, and Server Room) to enhance security and performance.
* **Port Security:** Specifically implemented in the Finance & Accounts department to prevent unauthorized access; configured with a maximum of one device per port, Sticky MAC addresses, and a shutdown violation mode.
* **SSHv2 Remote Management:** Secure, encrypted remote access configured on all routers and Layer 3 switches to replace insecure Telnet sessions.
* **Access Control Lists (ACLs):** Rules implemented to define and permit specific internal networks for translation and to manage outbound traffic.
* **Black-Hole VLANs:** Security hardening through VLAN 99, where all unused switch ports are assigned and administratively disabled to prevent physical intrusion.

📶 **Connectivity & Routing**
* **Hierarchical Model:** Implementation of the Cisco 3-layer model (Core, Distribution, and Access) to provide modularity and redundancy.
* **Dynamic Routing (OSPF):** Configured OSPF (Area 0) across Core routers and Multi-layer switches for fast convergence and dynamic path selection.
* **Dual-ISP Redundancy:** Connection to two separate Internet Service Providers (ISP1 and ISP2) to eliminate single points of failure at the edge.
* **Inter-VLAN Routing:** Performed by Multi-layer switches (Cisco 3650) to allow controlled communication between different departments.
* **Port Address Translation (PAT):** Configured on the outbound router interfaces to translate private internal IP addresses into public routable addresses for internet access.

🔧 **Switching & Optimization**
* **Redundant Distribution:** Dual Multi-layer switches providing high availability for the access layer.
* **Trunking & Access Ports:** Manual configuration of IEEE 802.1Q trunking links between switches and access ports for end-user devices.
* **Wireless LAN (WLAN):** Dedicated Access Points in every department to provide secure Wi-Fi connectivity for mobile users.

📡 **Infrastructure Services**
* **Centralized DHCP:** A dedicated server in the Server Room dynamically assigns IP addresses to all 600 hosts using IP Helper Addresses.
* **DNS & Email Services:** Internal servers for name resolution and corporate email communication.
* **Service Password Encryption:** All device passwords are encrypted in the configuration files for local security

🧩 **Project Scope**
This project simulates a comprehensive enterprise-level network using Cisco Packet Tracer. It demonstrates mastery of complex networking and security principles, including:
* **Enterprise Scaling:** Managing over 120 users per department across multiple floors.
* **High Availability:** Designing for disaster recovery with redundant links and devices.
* **Network Hardening:** Protecting sensitive financial and corporate data through encryption and port-level security


