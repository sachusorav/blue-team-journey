Day 1 – Networking Fundamentals
1. What is a Computer Network?
A computer network is a group of connected devices that communicate and share data and resources.

Examples: Wi-Fi, LAN, Internet.
2. What is the OSI Model?
OSI (Open Systems Interconnection) is a 7-layer model that explains how data travels between devices over a network.

7 Layers of OSI Model
7
Application
Provides network services to users
Examples: HTTP, FTP, DNS

6
Presentation
Data translation, encryption and compression
Examples: TLS, JPEG

5
Session
Establishes and manages sessions
Examples: Session management

4
Transport
Reliable or fast data delivery
Examples: TCP, UDP

3
Network
Logical addressing and routing
Examples: IP, ICMP

2
Data Link
Frames and MAC addressing
Examples: Ethernet, Wi-Fi (MAC)

1
Physical
Transmits raw bits through media
Examples: Cables, signals

Mnemonic (7 → 1): All People Seem To Need Data Processing.

3. What is the TCP/IP Model?

TCP/IP is the practical networking model used for communication over the Internet.
It has 4 layers:
Layer	        Function
Application	    Network services
Transport	    End-to-end communication
Internet	    IP addressing and routing
Network Access	Physical network transmission

4. OSI vs TCP/IP

OSI	TCP/IP
7 layers	        4 layers
Reference model	    Practical protocol suite
Developed by ISO	Developed by DARPA

Mapping:
- OSI Application + Presentation + Session → TCP/IP Application
- OSI Transport → TCP/IP Transport
- OSI Network → TCP/IP Internet
- OSI Data Link + Physical → TCP/IP Network Access

5. TCP vs UDP

TCP	UDP
Connection-oriented	Connectionless
Reliable delivery	No delivery guarantee
Error checking and retransmission	Error checking, no retransmission guarantee
Generally slower	Generally faster
Web pages, email	Streaming, gaming, DNS queries

6. What happens when you open a website?
  1. Enter a website URL in the browser.
  2. DNS finds the website's IP address.
  3. Your device connects to the server.
  4. Data is transferred using networking protocols.
  5. Browser receives and displays the webpage.
  7. Important Terms
  
  - IP Address: Identifies a device on an IP network.
  - MAC Address: Identifies a network interface at the Data Link layer.
  - Router: Connects different networks.
  - Switch: Connects devices within a LAN.
  - Packet: Unit of data at the Network layer.
  - Frame: Unit of data at the Data Link layer.
  - Protocol: Rules for communication.