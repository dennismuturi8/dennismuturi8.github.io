---
title: "Lab Challenges"
layout: single
permalink: /lab challenges/
author_profile: true
---
## 🧠 LAB CHALLENGES

### **1. HTB Academy: Introduction to Network Traffic Analysis**                                                              
---

**Description:**  
This lab challenge introduced the fundamentals of network traffic analysis using Wireshark. It focused on understanding how data flows within a network, capturing and analyzing packets, and identifying various communication protocols. The exercise helped build a solid foundation in interpreting real network data and recognizing common network behaviors and anomalies.

**Skills Demonstrated:**  
- Packet capture and analysis using Wireshark  
- Identification of network protocols and communication flows  
- Understanding of TCP/IP and OSI model layers  
- Detection of anomalies and potential security threats in network traffic  

**Tools Used:**  
Wireshark, TCP/IP Suite, Virtual Machines
<iframe src="https://drive.google.com/file/d/1kgCMMzi1gKhh124QgAxbREvcqC4JICGM/preview" width="640" height="480" allow="autoplay"></iframe>

### **2. HTB Academy: Web Requests**                                                                                             
---
**Description:**  
This lab focused on understanding how web requests function and how clients interact with web servers over the HTTP protocol. It explored various HTTP methods, headers, and status codes, providing hands-on experience in analyzing and crafting web requests to better understand web communication processes.

**Skills Demonstrated:**  
- Understanding of HTTP request and response structure  
- Practical use of methods such as GET, POST, PUT, and DELETE  
- Analysis of HTTP headers and status codes  
- Troubleshooting and inspecting web traffic using browser developer tools and intercepting proxies  

**Tools Used:**  
Burp Suite, Browser Developer Tools, cURL, HTB Academy Environment
<iframe src="https://drive.google.com/file/d/1r8YTaeftyTS3gOFMJTz8sdtz38_W9j90/preview" width="640" height="480" allow="autoplay"></iframe>

### **3. TryHackMe: DNS In Detail**                                                                                           
---

**Description:**  
This lab deep-dives into the Domain Name System (DNS), covering how names are resolved to IP addresses, common DNS record types, and the roles of authoritative and recursive name servers. The exercises guide you through practical DNS enumeration, diagnosing resolution issues, and identifying common misconfigurations that can be abused during reconnaissance or exploited in attacks (e.g., open zone transfers, subdomain takeovers). The lab also introduces defensive concepts such as caching behavior and a basic overview of DNSSEC.

**Skills Demonstrated:**  
- Understanding DNS architecture: recursive vs authoritative servers, caching, and resolution flow.  
- Interpreting DNS record types: A, AAAA, CNAME, MX, TXT, NS, SOA, SRV, PTR.  
- Performing DNS enumeration and reconnaissance techniques.  
- Detecting and exploiting misconfigurations (e.g., open zone transfers, exposed records).  
- Using tools to query and analyze DNS traffic and responses.  
- Basic awareness of DNS security (DNSSEC) and common mitigation strategies.

**Tools Used:**  
TryHackMe environment, `dig`, `nslookup`, `host`, `dnsenum`, `DNSRecon`, `subfinder`/`amass` (for subdomain enumeration), `nmap` (DNS scripts), Wireshark (for observing DNS traffic).

**Outcome / What I learned:**  
- I can quickly map a domain’s DNS surface (records and name servers) and identify high-value information such as mail servers (MX), delegation points (NS), and TXT records.  
- I’m able to detect insecure configurations (like zone transfers) and perform safe, ethical DNS reconnaissance in a controlled environment.  
- Improved ability to analyze DNS query/response behavior and make recommendations to harden DNS infrastructure against common reconnaissance and attack techniques.
<iframe src="https://drive.google.com/file/d/1QfPirZEjcCQyNxzygNAV2C38MckY7O0q/preview" width="640" height="480" allow="autoplay"></iframe>

### **4. Use Wireshark to Examine Network Traffic**                                                                           
---

**Description:**  
A hands-on exercise using Wireshark to capture, inspect, and analyze network packets. The lab focuses on capturing live traffic, applying display and capture filters, following TCP/UDP streams, reconstructing transferred files, and identifying normal vs suspicious network behaviour. Emphasis is placed on practical techniques for troubleshooting network issues and investigating potential security incidents.

**Skills Demonstrated:**  
- Capturing packets on interfaces and using proper capture filters to reduce noise.  
- Applying display filters (e.g., `ip.addr == x.x.x.x`, `http`, `ftp`, `tcp.port == 80`) to isolate relevant traffic.  
- Following TCP/UDP streams and reconstructing application-layer payloads.  
- Identifying protocol-specific details (HTTP, DNS, TLS, FTP, ARP, ICMP).  
- Recognizing common indicators of compromise (suspicious connections, unusual ports, malformed packets).  
- Exporting packet data and saving PCAPs for further analysis or reporting.

**Tools Used:**  
Wireshark, tshark, tcpdump, Virtual Machines (for isolated captures), browser developer tools (for correlating HTTP traffic).

**Outcome / What I learned:**  
- I can capture and filter network traffic to quickly surface relevant communications.  
- I can follow streams to reconstruct transferred files and analyze application-layer exchanges.  
- I can translate packet-level findings into clear evidence for troubleshooting or incident reports and recommend mitigations (e.g., patching, segmentation, filtering).
<iframe src="https://drive.google.com/file/d/1KeT7F2Lih5nrnFr5X5gE15aCNv4BRmzl/preview" width="640" height="480" allow="autoplay"></iframe>
