# Network-traffic-security-analysis
This project examines the traffic-handling and security differences between hubs and switches using Cisco Packet Tracer. It highlights how hubs broadcast packets to every connected device, while switches forward frames intelligently using MAC address learning. The project demonstrates why switches improve confidentiality, performance, and protection against packet sniffing.

## 🎯 Objectives
- Demonstrate how hubs broadcast all packets to every connected device.
- Show how switches learn MAC addresses and forward frames intelligently.
- Analyze packet movement using Cisco Packet Tracer simulation mode.
- Explain cybersecurity implications such as packet sniffing risks.
- Introduce basic configurations including IP addressing and interface control.

## 🛡️ Strategies Applied
**Device-Level Security**  
- Strong authentication mechanisms  
- Data encryption and secure firmware updates  
- Physical device hardening  

**Network-Level Security**  
- Network segmentation  
- Firewalls and Intrusion Detection Systems (IDS)  
- Secure communication protocols (TLS/SSL, MQTT with authentication)  

**Data Security**  
- Data minimization and tokenization  
- Regular backups  
- IoT security by design principles  
- Legal and regulatory compliance approaches

- Key Features

Hub Behavior Analysis

Broadcasts all traffic across the network

No segmentation or filtering

High vulnerability to sniffing attacks

Switch Behavior Analysis

Learns MAC addresses dynamically

Forwards frames only to their intended recipients

Improves confidentiality and network performance

Traffic Simulation

Visual packet flow analysis

Event inspection using simulation mode

MAC table verification for switching logic 

## 🔧 Technologies & Tools
- Wireshark (traffic analysis)  
- Snort IDS  
- IoT device emulators/testbeds  
- Secure protocols and configurations  

## 📸 Project Presentation  

### Network Topology Overview
![Network Topology](network-topology-overview.png)

### Device Configuration Interface
![Device Configuration](device-configuration-interface.png)

### Packet Simulation View
![Packet Simulation](packet-simulation-view.png)

### Switch MAC Table Output
![MAC Table](switch-mac-table-output.png)

### Hub vs Switch Traffic Flow Comparison
![Traffic Flow](hub-vs-switch-traffic-flow.png)

## 📚 Use Case
This project is designed for networking and cybersecurity learners who want to understand how traffic is handled by hubs versus switches. It reinforces fundamental concepts such as broadcast domains, MAC learning, packet visibility, and the security impact of device selection within a network.

## 📄 License
For educational demonstration and cybersecurity awareness.
