# Part 1 — Theory Questions

Author: Joy Townsend  
Date: March 7, 2026

## 1. Explain the role of the CPU and why it is called the brain of the computer.

The Central Processing Unit (CPU) is the part of the computer that performs calculations and executes instructions from programs. Every action a computer performs, such as opening a website or saving a file, involves the CPU processing instructions.

It is called the brain of the computer because it controls how the system operates and directs other components to perform tasks. The CPU retrieves instructions, interprets them, and executes them to complete operations.

## 2. Describe the Fetch → Decode → Execute → Store cycle.

The CPU processes instructions through a repeating cycle.

- Fetch: The CPU retrieves the next instruction from memory.
- Decode: The Control Unit interprets the instruction and determines what operation must be performed.
- Execute: The CPU performs the operation. This may involve calculations by the ALU or moving data.
- Store: The result of the operation is stored in memory for later use.

This cycle repeats continuously while programs are running.

## 3. What is a computer network?

A computer network is a system of interconnected devices that communicate with each other to exchange data and share resources.

Devices in a network may include computers, servers, smartphones, printers, and networking equipment such as routers and switches.

Networks allow systems to share files, access the internet, communicate through email, and use shared resources.

## 4. Explain the difference between router, switch, and hub.

- Router: A router directs data traffic between different networks. It reads IP addresses and sends data to the correct network destination.
- Switch: A switch connects multiple devices within the same local network and sends data only to the intended device using MAC addresses.
- Hub: A hub connects multiple devices but sends data to all connected devices, which can cause network collisions and reduce efficiency.

## 5. Which protocol assigns IP addresses automatically?

The protocol that assigns IP addresses automatically is DHCP (Dynamic Host Configuration Protocol).

It allows devices to receive an IP address automatically when they connect to a network instead of manually assigning addresses.

## 6. Explain the difference between TCP and UDP.

- TCP (Transmission Control Protocol): ensures reliable data delivery. It breaks data into packets, tracks them, and ensures they arrive in the correct order.
- UDP (User Datagram Protocol): sends data without guaranteeing delivery or order. It is faster but less reliable.
- TCP is used when reliability is important, while UDP is used for applications that require speed.

## 7. What is the TCP/IP model?

The TCP/IP model is a framework that explains how data moves across networks and the internet.

It defines how data is packaged, addressed, transmitted, routed, and received between devices.

The model organizes network communication into layers that work together to move data from one system to another.

## 8. List and explain the four layers of the TCP/IP model.

- Application Layer: This layer provides services directly to user applications such as web browsing and email.
- Transport Layer: This layer manages data transmission between devices using protocols such as TCP and UDP.
- Internet Layer: This layer handles addressing and routing using IP addresses.
- Network Interface Layer: This layer handles the physical transmission of data through network hardware such as Ethernet and Wi-Fi.

## 9. Match these protocols with their functions: HTTP, DNS, IP, FTP.

- HTTP: Transfers web pages between browsers and web servers.
- DNS: Translates domain names into IP addresses.
- IP: Provides addressing and routes data packets across networks.
- FTP: Transfers files between systems over a network.

## 10. Which WiFi band offers longer range but lower speed?

The 2.4 GHz WiFi band provides longer range but lower speed compared to higher frequency bands.

## 11. Explain PAN, LAN, and WAN with examples.

- PAN (Personal Area Network): A small network around a single person. Example: connecting a phone to Bluetooth headphones.
- LAN (Local Area Network): A network within a limited area such as a home, office, or building.
- WAN (Wide Area Network): A network that connects multiple LANs across large geographic areas. The internet is the largest WAN.

## 12. What is authentication and why is it important?

Authentication is the process of verifying the identity of a user before allowing access to a system.

It is important because it ensures that only authorized users can access sensitive systems and information.

Authentication protects systems from unauthorized access and helps protect data confidentiality.

## 13. Explain SFA, 2FA, and MFA.

- SFA (Single Factor Authentication): Authentication using one method, such as a password.
- 2FA (Two Factor Authentication): Authentication using two verification methods, such as a password and a code sent to a phone.
- MFA (Multi-Factor Authentication): Authentication using two or more verification factors such as a password, phone code, or biometric verification.
- These methods improve security by requiring multiple ways to verify identity.

## 14. Which authentication method uses biological traits?

Biometric authentication uses biological traits to verify identity. Examples include fingerprint scanning, facial recognition, and eye scanning.

## 15. Define encryption and explain symmetric vs asymmetric encryption.

- Encryption converts readable data into unreadable code so that only authorized users can access it.
- Symmetric encryption uses one key for both encryption and decryption.
- Asymmetric encryption uses two keys: a public key for encryption and a private key for decryption.

## 16. Which encryption algorithm is asymmetric?

RSA is an example of an asymmetric encryption algorithm.

## 17. What is the primary function of a firewall?

A firewall monitors and filters incoming and outgoing network traffic based on security rules. Its primary purpose is to block unauthorized access while allowing legitimate traffic.

## 18. Explain firewall actions: accept, reject, drop.

- Accept: Allows the network traffic to pass through.
- Reject: Blocks the traffic and sends a response indicating the request was denied.
- Drop: Silently blocks the traffic without sending any response.

## 19. What is cloud networking?

Cloud networking refers to network infrastructure that operates through cloud data centers rather than physical local hardware.

Cloud services run on remote servers located in large data centers operated by companies such as Amazon, Google, and Microsoft.

Users access applications, files, and services through the internet instead of local systems.

## 20. Explain what happens when you visit a website using browser, DNS, router, and server.

- Step 1: A user enters a website address in a browser.
- Step 2: The browser sends a request to a DNS server to translate the domain name into an IP address.
- Step 3: The request travels through the router and internet infrastructure as data packets.
- Step 4: The packets reach the web server hosting the website.
- Step 5: The server processes the request and sends the webpage data back to the browser.
- Step 6: The browser rebuilds the data packets and displays the webpage.
