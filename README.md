![PHOTO-2026-04-13-13-13-41](https://github.com/user-attachments/assets/60cd6e74-d401-4f67-8c72-d0b2b9158059) 
.
.
.
.
.
This project is a Deep Packet Inspection (DPI) based network traffic analyzer built using C++. The main idea behind this project is to simulate how Internet Service Providers (ISPs) inspect and manage network traffic in real-world systems.
Instead of building common projects like clones or CRUD apps, I wanted to work on something that demonstrates core computer networking and system-level concepts such as packet inspection, connection tracking, multithreading, and rule-based filtering.
The program reads real network traffic from PCAP (Packet Capture) files, extracts important packet details like source/destination IP, ports, protocol type, and SNI, and then groups packets into logical connections. 
To handle traffic efficiently, the project uses a multithreaded architecture where load balancer threads distribute packet workloads and worker threads process them in parallel, making the system scalable.

~ Key Features : -

1. Reads and analyzes real packet data from PCAP files
2. Tracks network connections based on source/destination and protocol
3. Supports rule-based filtering (block specific IPs/websites, etc.)
4. Uses multithreading for faster packet processing
5. Simulates real-world ISP-level traffic handling logic.
   
                   This project helped me strengthen my understanding of Computer Networks, multithreading, and real-world system design.
