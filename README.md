# CompTIA Network+ (N10-009) Summary Notes

# CompTIA Network+ - Module 1 Notes

## 📘 Module 1: Explaining Network Topologies

---

### ✅ Learning Objectives
- Explain network types and characteristics.
- Compare and contrast OSI model layers.
- Configure SOHO (Small Office/Home Office) networks.
- Explain and apply CompTIA’s troubleshooting methodology.

---

### 🧩 Lesson 1.1: Networking Overview

#### 💡 Key Concepts:
- A **network** is a group of connected devices sharing data (includes computers, protocols, and transmission media).
- **Peer-to-peer**: Devices communicate directly.
- **Client-server**: Central server provides services to multiple clients.
- **LAN (Local Area Network)**: A network confined to a single physical location (e.g., home or office).

#### 🔌 Network Topologies:
- **Point-to-Point**: Two nodes communicate directly.
- **Star**: All nodes connect to a central point (e.g., a switch).
- **Mesh**: Devices are interconnected (partial or full mesh), offering redundancy.

---

### 📊 Lesson 1.2: OSI Model Concepts

#### 🧱 OSI 7-Layer Model (Mnemonic: **All People Seem To Need Data Processing**):
1. **Application** – Interface for applications (e.g., HTTP, FTP).
2. **Presentation** – Translates, encrypts, compresses data.
3. **Session** – Manages sessions and authentication.
4. **Transport** – Reliable delivery (TCP/UDP).
5. **Network** – Logical addressing and routing (IP).
6. **Data Link** – MAC addressing, switching (Ethernet).
7. **Physical** – Hardware, cables, signals.

#### 📦 Packet Flow:
- Data is **encapsulated** at each layer on the sender side and **decapsulated** on the receiver side.

---

### 🖧 Lesson 1.3: SOHO Networks

#### 🛠 SOHO Router Layer Functions:
- **Physical Layer**: Connects cables and ports.
- **Data Link Layer**: Switch and Wi-Fi; devices identified by MAC addresses.
- **Network Layer**: Routes between LAN and public internet; acts as DHCP server.
- **Transport & Application Layers**: Provides NAT, port forwarding, and web services.
- **Internet Integration**: WAN connection to ISP and beyond.

#### 🔢 Binary & Hex:
- Understanding base-10 and binary systems is essential for IP addressing.
- Example: Converting 205 and 132 into binary.

---

### 🔧 Lesson 1.4: Troubleshooting Methodology

#### 🛠 Steps:
1. **Identify the Problem** – Gather details.
2. **Identify Problem Symptoms** – What exactly is failing?
3. **Establish a Theory** – Make an educated guess.
4. **Test the Theory** – Validate or eliminate possible causes.
5. **Implement a Solution** – Fix the issue.
6. **Verify Functionality** – Make sure it works.
7. **Document Findings** – Write down the issue, solution, and impact.

#### 🧠 Techniques:
- **Top-to-Bottom**: Start at Application layer and work down.
- **Bottom-to-Top**: Start at Physical and work up.
- **Divide-and-Conquer**: Test the middle layer and move up/down based on results.

---

### 📌 Summary
- The **OSI Model** helps with understanding and troubleshooting network communication.
- Use a **structured troubleshooting process** to solve network problems.
- Understand **network topologies** and the role of SOHO routers.
- Know how to **convert between binary and decimal** for IP calculations.


---

# Module 2: Supporting Cabling and Physical Installations

## Learning Objectives
- Summarize Ethernet standards
- Identify copper and fiber optic cables/connectors
- Describe structured cabling and physical installation
- Troubleshoot Ethernet cabling issues

## Key Topics
- **Ethernet**: IEEE 802.3 standards, CSMA/CD, media types
- **Copper Cables**: UTP, STP, coaxial, plenum vs. riser
- **Fiber Cables**: SMF, MMF, WDM, LC/SC/MPO connectors
- **Cabling Tools**: Termination, wire maps, tone generators
- **Installations**: Racks, patch panels, temperature, fire suppression
- **Troubleshooting**: Attenuation, crosstalk, EMI, interference


---

# Module 3: Configuring Interfaces and Switches

## Learning Objectives
- Explain network interfaces and Ethernet switching
- Deploy switching features and troubleshoot issues

## Key Topics
- **NICs vs Transceivers**: NIC connects host to network; transceivers adapt media types
- **Ethernet Frame Format**: MAC source/destination, payload, FCS
- **Switching Devices**: Hubs (broadcast), Bridges (segment), Switches (filter MAC)
- **Switch Features**: STP, MTU, Link Aggregation, PoE
- **Troubleshooting**: Interface counters, port lights, PoE failure, loops


---

# Module 4: Configuring Network Addressing

## Learning Objectives
- Explain IPv4/IPv6 addressing and forwarding
- Subnet and test IP configurations
- Use troubleshooting tools

## Key Topics
- **IPv4**: 32-bit, subnetting, private/public ranges, gateways, broadcast
- **IPv6**: 128-bit, address types, autoconfiguration, transition techniques
- **Subnetting**: Classful/Classless, CIDR, VLSM
- **Tools**: ipconfig, ifconfig/ip, arp, ping


---

# Module 5: Configuring Routing and Advanced Switching

## Learning Objectives
- Understand static/dynamic routing
- Describe VLANs and enterprise switching

## Key Topics
- **Routing**: Tables, default/static routes, RIP, EIGRP, OSPF, BGP
- **NAT**: Static, dynamic, PAT; Edge routers
- **Firewalls**: Stateless, Stateful
- **Topologies**: Tree, Hybrid
- **VLANs**: IDs, tagging, trunking, routing
- **Troubleshooting**: VLAN/IP mismatch, loops, unreachable hosts


---

# Module 6: Implementing Network Services

## Learning Objectives
- Compare transport protocols
- Understand DHCP, DNS, and IP auto-config

## Key Topics
- **TCP**: Reliable, 3-way handshake
- **UDP**: Lightweight, no guarantees
- **DHCP**: Discover → Offer → Request → ACK; relay and reservations
- **APIPA & SLAAC**: Local IPv4 and IPv6 autoconfig
- **DNS**: Resolution, records (A, AAAA, CNAME, etc.), zones, security
- **Troubleshooting**: nslookup, dig


---

# Module 7: Explaining Application Services

## Learning Objectives
- Understand web, file, email, database, and DR services

## Key Topics
- **TLS/HTTPS**: Secure communication
- **NTP/PTP**: Time synchronization
- **Web/File Services**: HTTP/S, FTP/SFTP, SMB, NAS
- **Email**: SMTP (send), IMAP (retrieve)
- **VoIP**: Voice/video services
- **Disaster Recovery**: Hot/warm/cold sites, load balancers, clusters


---

# Module 8: Supporting Management Network

## Learning Objectives
- Manage config documentation, use monitoring tools, and analyze traffic

## Key Topics
- **Config Management**: Change tracking, backups
- **Discovery/Monitoring**: Nmap, LLDP, SNMP
- **Performance Metrics**: Interface, device health, availability
- **Event Management**: Logs, syslog, SIEM, alerts
- **Packet Capture**: Wireshark/tcpdump
- **Traffic Monitoring**: Flow data, shaping, testing tools


---

