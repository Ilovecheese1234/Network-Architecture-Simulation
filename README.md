# Enterprise Network Architecture Simulation for Cinema Infrastructure 

A robust client-server networking project built for my final HKDSE Information & Communication Technology (ICT) School-Based Assessment. The project scored a 98/100 for project execution and work innovation. (2 marks deducted since I scored low on written exam on the actual DSE)

This is an academic submission for reference. Plagarism is strictly prohibited and the author is not liable to any offense committed by outsiders.
---

## 📖 Project Overview

The projects serves as a simulation of how to implement network infrastructure for a virtual cinema using Cisco Packet Tracer. 

## 🔑 Key Features

### Security, Encryption and Access Control
* **IPSec Tunnelling** Established secured and encrypted communication tunnel. Combining AES256 encryption and SHA256 hash function, ESP can be safely communicated between the cinema and the headquaters.
* **AAA protocol and Router ACL** Secure router access and packet delivery. AAA primarily handles router access by requesting username and password. Dedicated access control list are embedded into routers to drop packets from malicious source.
* **Proposal for enhancing security** Other than implementing protocols, I have included some software applications  way to handle network security.

### External and Internal Services
* **DHCP and DNS Servers** Auto assignment of network information for outsiders to connect to the internet within the cinema.
* **Web Server** For demonstrating the cinema's most up-to-date information to the public.
* **FTP Servers** Internal file management storage for storing important documents.
* **Mail Server** Allows employees and staff members to send sensitive information within the securred intranet.

### Administration, Logistics and Maintenance
* **Syslog Server** Collect and save network status within the cinema and to report any abnormalities to the network administrator
* **Netflow Collector** Receive and record packet flow inside each routers to demonstrate workload for each router.


---

## ⚙️ Network Architecture

- Topologies adopted: Mesh, Linear, Ring
- Routing protocol: OSPF
- IP Address used: 130.0.0.0 (Class B Address)
- IP subnet mask: 255.255.240.0

---

## 🚀 Running the Project

1. Install Cisco Packet Tracer, presumably with version higher than 6.1.1
2. Run the following command in terminal to get the project <br>
git clone https://github.com/Ilovecheese1234/Network-Architecture-Simulation
3. Enjoy

---

## 📈 Learnings & Takeaways

Building this project taught me several essential hard and soft skills:
1. **Network Communication Strategy** IP configuration, subnetting, masking, using appropraite routing protocols and verifying netork communication are simulated and experimented
2. **Network Security** Basic ideas on the core ideas of network security protocols and how to implement them.
3. **Writing proposals** Enhanced communication and conveying project details. Association to real life benefits me from understanding the challenge on actual implementation
---

## 📜 License & Disclaimers
This project is licensed under the MIT License. 

*Note: This was an academic submission. To current students, please view the architectural decisions but do not copy code directly to avoid plagiarism penalties.*