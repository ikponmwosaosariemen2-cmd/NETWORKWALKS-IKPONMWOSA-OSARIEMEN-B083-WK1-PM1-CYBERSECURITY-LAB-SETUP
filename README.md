# NETWORKWALKS-IKPONMWOSA OSARIEMEN-B083-WK1-PM1-CYBERSECURITY-LAB-SETUP

## Week 1 Project: Cybersecurity Lab Setup

### Project Objective

The objective of this project was to set up a cybersecurity testing lab environment using VirtualBox and Kali Linux.

## Tools Used

- VirtualBox
- Kali Linux
- 7-Zip

## Lab Configuration

- Virtualization platform: VirtualBox
- Attacking machine: Kali Linux
- Network type: NAT Network
- Network subnet: 10.0.0.0/24
- Kali Linux IP address: 10.0.0.2/24
- Internet connectivity: Enabled
- Clipboard: Enabled
- Drag and Drop: Enabled
- Shared folder: /downloads

## Project Steps

### Step 1 — Installed 7-Zip

7-Zip was installed to extract the downloaded Kali Linux virtual machine files.

### Step 2 — Installed VirtualBox

VirtualBox was installed as the virtualization platform for the cybersecurity lab.

### Step 3 — Configured the NAT Network

A custom NAT Network was created using the required 10.0.0.0/24 subnet.

### Step 4 — Downloaded and Imported Kali Linux

The Kali Linux Virtual Machine was downloaded and imported into VirtualBox.

### Step 5 — Configured Kali Linux

Kali Linux was configured with the required IP address and Internet connectivity.

### Step 6 — Created a Virtual Machine Snapshot

A snapshot was taken after completing the lab setup so the configured environment could be restored if needed.

## Troubleshooting

### Problem

During the VirtualBox installation, an error indicated that the Microsoft Visual C++ x64 Redistributable Package was required.

### Solution

I downloaded and installed the required Microsoft Visual C++ x64 Redistributable Package and then restarted the VirtualBox installation. VirtualBox subsequently installed successfully.

## What I Learned

This project gave me practical experience setting up a cybersecurity testing environment. I learned how to use VirtualBox, configure a NAT Network, configure Kali Linux networking, enable VM integration features, and troubleshoot installation and connectivity issues.

## Lab Network Architecture

The cybersecurity lab was set up using VirtualBox with Kali Linux as the virtual machine. The lab uses a NAT Network to provide network connectivity and Internet access.

```text
Internet
   |
   v
VirtualBox NAT Network
10.0.0.0/24
   |
   v
Kali Linux
IP: 10.0.0.3/24



## Conclusion

The Week 1 cybersecurity lab environment was successfully configured and tested using VirtualBox and Kali Linux.




Architecture Components
Host Machine: Windows PC
Virtualization Platform: VirtualBox
Attacking Machine: Kali Linux
Network Type: NAT Network
Network Subnet: 10.0.0.0/24
Kali Linux IP Address: 10.0.0.3/24
Internet Access: Enabled
