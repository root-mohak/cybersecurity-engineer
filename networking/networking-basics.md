# Networking Basics for Cybersecurity

## What is a Network?
A network is a group of connected devices that communicate.

## Network Types
- Private Network
- Public Network (Internet)

## Why Networking Matters
- Traffic analysis
- Intrusion detection

- # Networking Basics for Cybersecurity

## What is Networking?
If two or more devices can connect to each other and transfer data, this is called a **computer network**.  
The study and implementation of how these devices connect and communicate is known as **networking**.

Networking forms the **foundation of all cyber attacks and defensive strategies**.  
Without understanding networking, it is impossible to properly detect, analyze, or respond to cyber incidents.

---

## Why Networking is Important in Cybersecurity
Networking gives us **visibility into how systems communicate**, which helps in:

- Understanding how many devices and IPs exist in a network
- Detecting suspicious or malicious traffic
- Creating effective **incident response plans**
- Containing attacks like **ransomware**
- Isolating (quarantining) one infected asset while protecting others
- Preventing full network compromise in small and large organizations

Without networking knowledge, defenders cannot properly respond to attacks or protect critical assets.

---

## History of the Internet (Brief)
Originally, there were **no phones, no modern communication systems**.  
The internet started as a military research project called **ARPANET**, developed by the **Advanced Research Projects Agency (ARPA)**.

The goal was to create a network that could still function even if parts of it were destroyed.  
Over time, this evolved into the modern **Internet**, often described as a:

> **“Network of Networks”**

The **World Wide Web (WWW)** later enabled global information sharing.

---

## Types of Computer Networks

### LAN (Local Area Network)
- Small geographical area (home, office, college)
- Example: Wi-Fi in a house

### WAN (Wide Area Network)
- Large geographical area
- Example: The Internet

### MAN (Metropolitan Area Network)
- Covers a city or large campus
- Example: City-wide ISP networks

### PAN (Personal Area Network)
- Very short range
- Example: Bluetooth connection between phone and earphones

---

## Data Transfer Terms

### Latency
- Time taken for data to travel from source to destination
- Lower latency = faster response

### Bandwidth
- Maximum amount of data that can be transmitted per second

### Throughput
- Actual speed of data transfer
- Usually less than bandwidth due to overhead

### Jitter
- Variation in data packet delivery time
- High jitter affects voice and video communication

---

## Network Topology
**Topology** refers to the arrangement and structure of devices in a network.

### Ring Topology
- Devices connected in a circular manner
- Commonly used in some industrial environments

### Mesh Topology
- Devices are interconnected with multiple paths
- Highly resilient and fault-tolerant
- Commonly used in **military and critical systems**

---

## Cybersecurity Perspective
Understanding networking allows security professionals to:
- Monitor traffic flow
- Detect anomalies
- Respond to attacks efficiently
- Design secure and resilient networks

Networking is not optional in cybersecurity — **it is the base layer of everything**.


🌐 Networking Fundamentals for Cybersecurity & Ethical Hacking

This document covers core networking concepts required for cybersecurity, ethical hacking, and IT fundamentals. The notes are structured for learning, revision, exams, interviews, and GitHub documentation.

1️⃣ Client-Server vs Peer-to-Peer Architecture
Client-Server Architecture

One central server provides services

Clients request resources

Examples

Web applications

Email servers

Databases

Pros

Centralized control

Better security

Easy management

Cons

Single point of failure

Costly infrastructure

Peer-to-Peer (P2P) Architecture

All devices act as both client and server

No central authority

Examples

File sharing (BitTorrent)

LAN file sharing

Pros

No single failure point

Cost-effective

Cons

Weak security

Difficult management

2️⃣ OSI Model (7 Layers)
Layer	Name	Purpose
7	Application	User interaction (HTTP, FTP)
6	Presentation	Encryption, compression
5	Session	Session management
4	Transport	Reliable delivery (TCP/UDP)
3	Network	IP addressing & routing
2	Data Link	MAC addressing
1	Physical	Cables & signals

Mnemonic:
👉 All People Seem To Need Data Processing

3️⃣ Encapsulation & Decapsulation
Encapsulation

Data wrapped with headers as it moves down the OSI layers

Application Data
↓
TCP/UDP Header
↓
IP Header
↓
Ethernet Frame

Decapsulation

Reverse process at receiver

Headers removed layer by layer

4️⃣ TCP/IP Model (4 Layers)
TCP/IP Layer	OSI Mapping
Application	OSI 7–5
Transport	OSI 4
Internet	OSI 3
Network Access	OSI 2–1

Used in real-world networking and hacking labs

