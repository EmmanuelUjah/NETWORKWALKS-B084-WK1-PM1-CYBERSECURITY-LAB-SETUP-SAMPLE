**Cybersecurity Lab Environment Setup**
Building an isolated virtual lab for penetration testing and ethical hacking practice:

**Project Overview**
This project focuses on setting up a virtual cybersecurity and penetration-testing laboratory using VirtualBox and Kali Linux.
The purpose of the lab is to create a controlled environment where cybersecurity tools, network scanning, reconnaissance, vulnerability assessment, and other security-testing activities can be performed safely and repeatedly.
The lab is configured on a private virtual network so that additional machines can be added later and used as targets for authorized security testing.

**The main objectives of this project are to:**
Install and configure VirtualBox.
Install/import Kali Linux as a virtual machine.
Create a private NAT Network for the cybersecurity lab.
Configure network connectivity for Kali Linux.
Assign a consistent IP address to the Kali VM.
Verify network connectivity and DNS resolution.
Take a clean VM snapshot for recovery.
Document the complete setup process.
Prepare the environment for future cybersecurity projects.

**Purpose of the Lab :***
The lab provides an isolated and controlled environment for cybersecurity learning and authorized security testing.
It can be used for activities such as:
Network reconnaissance
Port scanning
Vulnerability assessment
Packet analysis
Web security testing
Exploitation practice
Security-tool experimentation

**Lab Configuration**
🧩 Component	⚙️ Configuration
🖥️ Host OS	Windows 11
🧠 Host RAM	8 GB
⚡ Processor	Intel Core i7
🧰 Hypervisor	VirtualBox 7.2.14
🐉 Security OS	Kali Linux 2026.2
🧠 Kali RAM	2048 MB
🌐 Virtual Network	NAT Network
📡 Network Address	10.0.0.0/24
🐧 Kali IP Address	10.0.0.2/24
🚪 Default Gateway	10.0.0.1
🌍 DNS Server	10.0.0.1


**Lab Setup Procedure:**
Step 1. Install VirtualBox : VirtualBox was installed as the hypervisor.
