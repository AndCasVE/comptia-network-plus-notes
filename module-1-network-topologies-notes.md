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
