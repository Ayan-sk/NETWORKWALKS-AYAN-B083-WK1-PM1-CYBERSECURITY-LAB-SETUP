# Cybersecurity Lab Environment Setup
Building an isolated virtual lab for penetration testing and ethical hacking practice.

## Project Overview
This project focuses on setting up a virtual cybersecurity and penetration-testing laboratory using VirtualBox and Kali Linux. 
The purpose of the lab is to create a controlled environment where cybersecurity tools, network scanning, reconnaissance, vulnerability assessment, and other security-testing activities can be performed safely and repeatedly.

## Configuration Steps
1. Created a NATNetwork in VirtualBox configured to `10.0.0.0/24` with DHCP enabled.
2. Imported the Kali Linux virtual machine.
3. Attached Kali Linux Network Adapter 1 to the `NatNetwork` and set Promiscuous Mode to "Allow All".
4. Configured a manual IP address inside Kali Linux:
   - **IP Address:** 10.0.0.2
   - **Netmask:** 24
   - **Gateway:** 10.0.0.1
   - **DNS:** 8.8.8.8
5. Shared the host machine's Downloads folder with the Kali VM.

## Proof of Setup
<img width="967" height="537" alt="image" src="https://github.com/user-attachments/assets/847ac866-32b3-4058-8047-8fc70d92a477" />

