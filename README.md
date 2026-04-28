# SIEM-WAZUH
This final-year B.Tech Cyber Security project implements a SIEM solution to help organizations monitor, collect, and analyze logs from multiple systems. It enables real-time threat detection, event analysis, and improved incident response, enhancing overall security visibility and management.

# ⚙️ Step 1: Environment Setup

1. Install Virtualization Software
Download and install Oracle VM VirtualBox to create and manage virtual machines.

2. Download Operating System ISOs

Download the Ubuntu ISO file (for SIEM server setup)
Download the Windows 10 ISO file (for endpoint/log generation)

3. Create Virtual Machines

Create one VM for Ubuntu (SIEM server)
Create one VM for Windows 10 (client machine)
Allocate sufficient RAM (minimum 4GB recommended) and storage

4. Install Operating Systems

Mount the respective ISO files
Complete the installation process for both Ubuntu and Windows 10

# 🖥️ Step 2: System Role Configuration

After setting up the virtual machines:

Use Ubuntu as the SIEM Server
Responsible for log collection, analysis, and threat detection
Hosts the SIEM platform (e.g., Wazuh/ELK stack)
Use Windows 10 as the Agent System
Acts as an endpoint machine
Generates logs and security events
Sends collected data to the SIEM server for monitoring

This setup simulates a real-world environment where endpoints communicate with a centralized SIEM system for security analysis
