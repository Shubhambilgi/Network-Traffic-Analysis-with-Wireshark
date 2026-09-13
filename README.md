# Network Traffic Analysis with Wireshark

A hands-on network traffic analysis project using **Wireshark and Kali Linux** to capture, inspect, and analyze network packets at the protocol level.

## Overview

This project focuses on understanding how network communication appears at the packet level.

Using Wireshark, I captured network traffic and investigated packet details, TCP communication, protocol distribution, and traffic patterns through different analysis views.

The project demonstrates practical experience with:

- Packet capture and inspection
- TCP traffic analysis
- ARP traffic observation
- TCP stream inspection
- Protocol hierarchy analysis
- Network traffic visualization
- Packet-level troubleshooting and investigation

## Objectives

The main objectives of this project were to:

- Capture live network traffic using Wireshark
- Identify and inspect packets generated during network communication
- Analyze TCP packet exchanges
- Examine ARP traffic
- Follow TCP streams to understand individual conversations
- Analyze protocol distribution using Protocol Hierarchy
- Visualize packet activity using Wireshark I/O Graphs
- Document observations from the captured traffic

## Tools & Environment

| Tool | Purpose |
|---|---|
| **Wireshark** | Network packet capture and protocol analysis |
| **Kali Linux** | Security-focused analysis environment |
| **eth0** | Network interface used for packet capture |

## Analysis Performed

### 1. Packet Capture

Network traffic was captured through the `eth0` interface and inspected directly in Wireshark.

The capture contained multiple types of traffic, including:

- TCP
- ARP
- IPv4 communication

The packet list was used to examine source and destination addresses, protocols, packet lengths, TCP flags, and other packet-level information.

### 2. TCP Traffic Analysis

TCP packets were examined to understand communication between the local system and remote hosts.

The analysis included inspecting:

- Source and destination IP addresses
- Source and destination ports
- TCP sequence and acknowledgment numbers
- TCP flags
- Packet timing
- TCP communication patterns

### 3. TCP Stream Analysis

Wireshark's **Follow TCP Stream** functionality was used to isolate an individual TCP conversation.

This helped provide a focused view of the communication belonging to a specific TCP stream rather than examining the entire packet capture at once.

### 4. Protocol Hierarchy

The **Protocol Hierarchy Statistics** feature was used to understand how the captured traffic was distributed across different protocol layers.

The analysis showed traffic across layers including:

- Ethernet
- IPv4
- TCP
- TLS

This provides a high-level view before moving into individual packet analysis.

### 5. I/O Graph Analysis

Wireshark's **I/O Graphs** were used to visualize packet activity over time.

The graph helped observe changes in packet activity and identify periods of higher traffic within the capture.

## Screenshots

### Packet Capture

![Wireshark Packet Capture](Screenshots/Screenshot%20from%202025-01-19%2017-09-35.png)

### TCP Stream Analysis

![Wireshark TCP Stream](Screenshots/Screenshot%20from%202025-01-19%2017-10-21.png)

### Protocol Hierarchy

![Wireshark Protocol Hierarchy](Screenshots/Screenshot%20from%202025-01-19%2017-11-32.png)

### I/O Graph

![Wireshark I/O Graph](Screenshots/Screenshot%20from%202025-01-19%2017-11-49.png)

## Key Skills Demonstrated

- Network traffic analysis
- Wireshark
- Packet capture
- TCP/IP fundamentals
- TCP stream analysis
- ARP traffic inspection
- Protocol analysis
- Network traffic visualization
- Packet-level troubleshooting
- Kali Linux
- Technical documentation

## Project Files

```text
Network-Traffic-Analysis-with-Wireshark/
│
├── README.md
├── report.pdf
│
└── Screenshots/
    ├── Screenshot from 2025-01-19 17-09-35.png
    ├── Screenshot from 2025-01-19 17-10-21.png
    ├── Screenshot from 2025-01-19 17-11-32.png
    ├── Screenshot from 2025-01-19 17-11-49.png
    └── Screenshot from 2025-01-19 17-17-32.png
```

## Detailed Report

The repository includes the complete project report:

**[View the Network Traffic Analysis Report](report.pdf)**

## What I Learned

This project strengthened my understanding of how network communication can be investigated from raw packet data.

The main practical takeaways were:

- Reading packet-level information instead of relying only on application output
- Understanding TCP communication through individual packets
- Isolating conversations using TCP streams
- Using protocol statistics to understand captured traffic
- Visualizing traffic patterns over time
- Using Wireshark as an investigation and troubleshooting tool

## Disclaimer

This project was performed in a controlled lab environment for educational and cybersecurity learning purposes.

The captured traffic and analysis should not be interpreted as representing a production network environment.

## License

This project is licensed under the MIT License.