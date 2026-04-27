# CompTIA Network+ Study Guide and Practice Quiz (Modules 1–8)

## Study Guide

### Module 1: Network Topologies, OSI, and Troubleshooting
- Understand network types: peer-to-peer, client-server, and LAN.
- Compare topologies: point-to-point, star, and mesh.
- Memorize OSI layers and key responsibilities.
- Explain encapsulation/decapsulation.
- Review SOHO router functions (DHCP, NAT, port forwarding).
- Apply CompTIA troubleshooting methodology and approaches (top-down, bottom-up, divide-and-conquer).

### Module 2: Cabling and Physical Installations
- Review Ethernet standards and media types.
- Identify copper cable types (UTP/STP/coax) and when to use each.
- Identify fiber types (SMF/MMF), connectors, and WDM concepts.
- Understand structured cabling components and installation best practices.
- Troubleshoot attenuation, crosstalk, and EMI/interference.

### Module 3: Interfaces and Switching
- Differentiate NICs and transceivers.
- Understand Ethernet frame fields, including FCS.
- Compare hub, bridge, and switch forwarding behavior.
- Review STP, MTU, link aggregation, and PoE.
- Troubleshoot loops, PoE failures, and interface issues.

### Module 4: Network Addressing
- Compare IPv4 (32-bit) and IPv6 (128-bit).
- Understand subnetting, CIDR, and VLSM.
- Explain private/public ranges and default gateway concepts.
- Use tools: ipconfig/ifconfig/ip, arp, ping.

### Module 5: Routing and VLANs
- Compare static/default and dynamic routing.
- Review RIP, EIGRP, OSPF, and BGP at a high level.
- Understand NAT types: static, dynamic, and PAT.
- Explain VLAN IDs, tagging, trunking, and inter-VLAN routing.
- Troubleshoot VLAN mismatch, loops, and reachability issues.

### Module 6: Network Services
- Compare TCP vs UDP use cases.
- Memorize DHCP DORA process.
- Understand APIPA and SLAAC.
- Review DNS records and zones.
- Troubleshoot with nslookup and dig.

### Module 7: Application Services
- Explain TLS/HTTPS purpose.
- Understand NTP/PTP time synchronization.
- Review HTTP/S, FTP/SFTP, SMB, SMTP, IMAP, VoIP.
- Understand DR concepts: hot/warm/cold sites, clusters, load balancing.

### Module 8: Network Management
- Review change/configuration management and backups.
- Understand discovery/monitoring with Nmap, LLDP, and SNMP.
- Track performance metrics and availability.
- Use logs/syslog/SIEM for event management.
- Perform packet/traffic analysis with Wireshark/tcpdump and flow tools.

---

## Practice Quiz Questions by Module

### Module 1
1. Which topology provides greater redundancy: star or full mesh?
2. Which OSI layer is responsible for logical addressing and routing?
3. In CompTIA troubleshooting, what step comes after testing a theory?
4. Name one advantage of top-down troubleshooting.
5. What does NAT do on a SOHO router?

### Module 2
1. When might STP cable be preferred over UTP?
2. What is one key difference between SMF and MMF?
3. Why are plenum-rated cables used in certain spaces?
4. Name one tool used to validate cable wiring.
5. What is attenuation?

### Module 3
1. What is the purpose of the FCS field in an Ethernet frame?
2. How does a hub handle incoming frames versus a switch?
3. What network problem does STP prevent?
4. Name one reason PoE may fail on a switch port.
5. What does link aggregation improve?

### Module 4
1. How many bits are in IPv4 and IPv6 addresses?
2. What is CIDR used for?
3. What is the role of the default gateway?
4. Which command can quickly test reachability?
5. What does ARP map?

### Module 5
1. What is one difference between static and dynamic routing?
2. What does PAT allow organizations to do?
3. What is a VLAN trunk used for?
4. Why can VLAN/IP mismatches cause outages?
5. Which protocol is commonly used for inter-domain routing?

### Module 6
1. List the DHCP DORA steps in order.
2. Give one scenario where UDP is preferable to TCP.
3. What does SLAAC automate?
4. Which DNS record maps hostnames to IPv4 addresses?
5. Which tool would you use to test DNS query behavior directly?

### Module 7
1. Which protocol typically sends outgoing mail?
2. Which protocol is commonly used to retrieve mail from a server?
3. Why is TLS important for web applications?
4. What is a hot site in disaster recovery?
5. Why is synchronized time important in enterprise networks?

### Module 8
1. What is the difference between packet capture and flow monitoring?
2. What does SNMP help monitor?
3. Why are backup configs part of operational best practice?
4. What role does SIEM play in network operations?
5. Name one tool used for packet-level troubleshooting.

---

## Suggested Next Steps
- Convert this guide into flashcards.
- Add an answer key and scoring rubric.
- Build a timed 50-question mock exam.

## Answer Key (with brief explanations)

### Module 1 Answers
1. **Full mesh** — every node has multiple paths, maximizing redundancy.
2. **Layer 3 (Network)** — handles logical addressing and routing.
3. **Implement a solution** — after validating the theory.
4. **Top-down advantage:** quickly isolates app/service misconfigurations first.
5. **NAT** translates private internal addresses to public addresses for internet access.

### Module 2 Answers
1. **STP preferred** in high-EMI environments (e.g., near heavy electrical equipment).
2. **SMF vs MMF:** SMF supports longer distances with a narrow core; MMF is shorter-range with a wider core.
3. **Plenum cable** has fire-resistant, low-smoke jacket for air-handling spaces.
4. **Cable tester / wire map tool** validates wiring pinout and continuity.
5. **Attenuation** is signal loss over distance/media.

### Module 3 Answers
1. **FCS** detects frame errors using checksum/CRC.
2. **Hub broadcasts** to all ports; **switch forwards** based on MAC table.
3. **STP** prevents Layer 2 switching loops.
4. **PoE failure reasons:** power budget exceeded, incompatible standard, bad cable, disabled PoE.
5. **Link aggregation** increases throughput and adds path resilience.

### Module 4 Answers
1. **IPv4 = 32 bits, IPv6 = 128 bits.**
2. **CIDR** defines prefix length for efficient subnetting and routing.
3. **Default gateway** forwards traffic destined for remote networks.
4. **`ping`** is a quick basic reachability test.
5. **ARP** maps IPv4 addresses to MAC addresses on a LAN.

### Module 5 Answers
1. **Static routing** is manually configured; **dynamic routing** learns/updates routes automatically.
2. **PAT** allows many private hosts to share one/few public IPs using port translation.
3. **Trunk port** carries multiple VLANs between network devices.
4. **VLAN/IP mismatch** places hosts in wrong broadcast/routing domain, breaking connectivity.
5. **BGP** is the common inter-domain routing protocol.

### Module 6 Answers
1. **Discover → Offer → Request → ACK (DORA).**
2. **UDP preferred** for low-latency apps like streaming, VoIP, and some gaming traffic.
3. **SLAAC** automatically assigns IPv6 addressing details to hosts.
4. **A record** maps hostnames to IPv4 addresses.
5. **`dig`** directly tests DNS query/response behavior.

### Module 7 Answers
1. **SMTP** typically sends outgoing mail.
2. **IMAP** is commonly used to retrieve/sync mailbox content.
3. **TLS** provides encryption, integrity, and server authentication for web traffic.
4. **Hot site** is a near-immediate failover facility with ready infrastructure.
5. **Time sync** is critical for logs, auth, certificates, and distributed coordination.

### Module 8 Answers
1. **Packet capture** inspects per-packet detail; **flow monitoring** summarizes conversations/traffic patterns.
2. **SNMP** monitors device/interface health and performance counters.
3. **Backup configs** enable rapid recovery, rollback, and compliance tracking.
4. **SIEM** centralizes logs and correlates events for detection/response.
5. **Wireshark** (or `tcpdump`) supports packet-level troubleshooting.

## Scoring Rubric
- **36–40 correct:** Exam-ready in core concepts.
- **30–35 correct:** Strong progress; review weak modules.
- **24–29 correct:** Needs targeted reinforcement.
- **0–23 correct:** Rebuild fundamentals module-by-module.

## 7-Day Review Plan
- **Day 1:** Modules 1–2 + 20 quiz questions.
- **Day 2:** Modules 3–4 + subnetting drills.
- **Day 3:** Modules 5–6 + command-line practice.
- **Day 4:** Modules 7–8 + monitoring/log analysis.
- **Day 5:** Retake missed questions only.
- **Day 6:** Full mixed 40-question run.
- **Day 7:** Final weak-area review + rapid recall cards.
