# 🌐 OSI Model - Explained Layer by Layer

The **OSI (Open Systems Interconnection) Model** is a conceptual framework that standardizes the functions of a telecommunication or computing system into **seven abstraction layers**.

---

## 📚 Table of Contents

1. [Layer 1 - Physical](#1-physical-layer)
2. [Layer 2 - Data Link](#2-data-link-layer)
3. [Layer 3 - Network](#3-network-layer)
4. [Layer 4 - Transport](#4-transport-layer)
5. [Layer 5 - Session](#5-session-layer)
6. [Layer 6 - Presentation](#6-presentation-layer)
7. [Layer 7 - Application](#7-application-layer)

---

## 1. 📡 Physical Layer

- **Function**: Transmits raw binary data (0s and 1s) over physical medium.
- **Data Unit**: **Bits**
- **Devices**: Hubs, Cables, Repeaters, Network Interface Cards (NICs)
- **Mediums**: Copper wires, Fiber optics, Radio signals
- **Key Concepts**: Voltage levels, Timing, Bit rate, Physical connectors

---

## 2. 🧱 Data Link Layer

- **Function**: Error detection, MAC addressing, and framing of data.
- **Data Unit**: **Frames**
- **Devices**: Switches, Bridges
- **Protocols**: Ethernet, PPP, ARP, HDLC
- **Sub-layers**:
  - **MAC (Media Access Control)**: Controls how devices access the medium
  - **LLC (Logical Link Control)**: Error checking and frame synchronization

---

## 3. 🌍 Network Layer

- **Function**: Routing, logical addressing (IP), and path determination.
- **Data Unit**: **Packets**
- **Devices**: Routers, Layer 3 switches
- **Protocols**: IP (IPv4/IPv6), ICMP, IGMP
- **Key Concepts**: Subnetting, Routing tables, Congestion control

---

## 4. 📦 Transport Layer

- **Function**: Reliable or unreliable data delivery, segmentation, and reassembly.
- **Data Unit**: **Segments (TCP)** / **Datagrams (UDP)**
- **Devices**: Gateways, Firewalls
- **Protocols**: TCP, UDP, SCTP
- **Key Concepts**: Port numbers, Flow control, Error correction, Multiplexing

---

## 5. 🧑‍💻 Session Layer

- **Function**: Establish, manage, and terminate communication sessions.
- **Data Unit**: **Data**
- **Protocols**: NetBIOS, PPTP, RPC
- **Key Concepts**: Session management, Dialog control, Token management

---

## 6. 🧠 Presentation Layer

- **Function**: Data translation, encryption, compression.
- **Data Unit**: **Data**
- **Protocols**: SSL/TLS, JPEG, MPEG, ASCII, EBCDIC
- **Key Concepts**: Syntax and semantics of the information, Data encoding

---

## 7. 🖥️ Application Layer

- **Function**: Provides network services directly to user applications.
- **Data Unit**: **Data**
- **Protocols**: HTTP, FTP, SMTP, DNS, Telnet, POP3
- **Key Concepts**: Application access, File transfers, Email, Web browsing

---

## 🔁 Summary Table

| Layer No. | Layer Name      | Data Unit   | Devices Used           | Key Protocols             |
|-----------|------------------|-------------|--------------------------|----------------------------|
| 7         | Application       | Data        | Computer, Servers        | HTTP, FTP, DNS, SMTP       |
| 6         | Presentation      | Data        | N/A                      | SSL, JPEG, MPEG            |
| 5         | Session           | Data        | N/A                      | NetBIOS, PPTP              |
| 4         | Transport         | Segments    | Gateways, Firewalls      | TCP, UDP                   |
| 3         | Network           | Packets     | Routers                  | IP, ICMP, IGMP             |
| 2         | Data Link         | Frames      | Switches, NICs, Bridges  | Ethernet, ARP, PPP         |
| 1         | Physical          | Bits        | Hubs, Cables, Repeaters  | N/A                        |

---

## 🧠 Mnemonic to Remember Layers:

> **All People Seem To Need Data Processing**  
> (Application, Presentation, Session, Transport, Network, Data Link, Physical)

Or, for reverse:

> **Please Do Not Throw Sausage Pizza Away**  
> (Physical → Application)

---

## 🚀 Bonus Tips

- Layers **1–4** are known as **Lower Layers** (hardware + transport).
- Layers **5–7** are **Upper Layers** (software & application interaction).
- OSI is theoretical; real-world networking uses **TCP/IP model**, which maps differently.

---
