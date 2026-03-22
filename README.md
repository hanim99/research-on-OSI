# research-on-OSI
The Open Systems Interconnection (OSI) model is a conceptual, seven-layer framework developed by the International Organization for Standardization (ISO) in 1984. It defines how data communication takes place between different computing systems, regardless of their underlying architecture, vendor, or technology. It serves as a universal language for networking, providing a standardized blueprint for how data flows from an application on one machine, through the network media, and to an application on another. 
Cloudflare
Cloudflare
 +2
The 7 Layers of the OSI Model (Top to Bottom)
The layers are ordered from the user-facing application down to the raw physical connection. Data flows from the top layer down (on the sender's side) and from the bottom layer up (on the receiver's side). 
A1 Digital
A1 Digital
 +1
Layer 7: Application Layer
This is the closest layer to the end user and provides network services directly to applications (e.g., web browsers, email clients). 
www.glasshouse.com.tr
www.glasshouse.com.tr
Function: Serves as the interface between user-facing applications and network services.
Examples: HTTP (web), FTP (file transfer), SMTP (email), DNS. 
www.glasshouse.com.tr
www.glasshouse.com.tr
Layer 6: Presentation Layer
This layer translates data between the application layer and the network format. It is also known as the "syntax layer". 
Imperva
Imperva
 +2
Function: Data formatting, data encryption/decryption, and data compression.
Examples: SSL/TLS (encryption), JPEG, GIF, ASCII. 
A1 Digital
A1 Digital
 +1
Layer 5: Session Layer
This layer manages the dialogue between computers, establishing, maintaining, and terminating connections (sessions) between applications. 
Zero Networks
Zero Networks
 +1
Function: Session checkpointing and recovery, ensuring communication resumes after interruptions.
Examples: NetBIOS, RPC, PPTP. 
Imperva
Imperva
 +1
Layer 4: Transport Layer
This layer ensures complete, error-free, and sequential delivery of data between hosts. It breaks data into smaller units called segments. 
A1 Digital
A1 Digital
Function: End-to-end connection, flow control, and error correction.
Examples: TCP (reliable), UDP (fast). 
www.glasshouse.com.tr
www.glasshouse.com.tr
Layer 3: Network Layer
Responsible for moving data between different networks (routing) and logical addressing. It breaks segments into packets. 
Imperva
Imperva
 +1
Function: Routing, logical addressing (IP addresses), and packet forwarding.
Examples: IP (Internet Protocol), ICMP, Routers. 
Imperva
Imperva
 +4
Layer 2: Data Link Layer
Responsible for node-to-node data transfer on the same network segment. It breaks packets into frames. 
Fastly
Fastly
 +1
Function: Physical addressing (MAC addresses), error detection, and flow control.
Examples: Ethernet, Switches, MAC addresses. 
NetCom Learning
NetCom Learning
 +4
Layer 1: Physical Layer
The lowest layer, responsible for transmitting raw bits (0s and 1s) over a physical medium (cables, radio waves). 
www.glasshouse.com.tr
www.glasshouse.com.tr
Function: Transmission of raw data over physical media, managing voltage levels and cable specifications.
Examples: Ethernet cables, Fiber optics, Hubs, Repeaters. 
NetCom Learning
NetCom Learning
 +2
Why the OSI Model is Needed
Although the modern internet primarily uses the TCP/IP model, the OSI model remains essential for several reasons: 
Troubleshooting: It allows IT professionals to narrow down problems. If the network isn't working, a technician can check if the issue is in the physical cables (L1), routing (L3), or the application itself (L7).
Interoperability: It provides a universal standard, enabling hardware and software from different manufacturers to communicate.
Modular Development: Developers can focus on a single layer, improving its functionality without needing to rewrite the entire network protocol stack.
Educational Foundation: It provides a structured, visual framework to understand how networks operate.
Security Management: Security teams use the model to apply protections at specific, vulnerable layers, such as using firewalls at the Network layer or TLS at the Presentation layer. 
Imperva
Imperva
 +3
Summary Table: OSI Data Units
Layer 	Name	Data Unit
7	Application	Data
6	Presentation	Data
5	Session	Data
4	Transport	Segments
3	Network	Packets
2	Data Link	Frames
1	Physical	Bits
Mnemonic for Remembering Layers 
