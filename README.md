# SIEM-WAZUH
This final-year B.Tech Cyber Security project implements a SIEM solution to help organizations monitor, collect, and analyze logs from multiple systems. It enables real-time threat detection, event analysis, and improved incident response, enhancing overall security visibility and management.

# 🔐 Features of SIEM (Security Information and Event Management)

1. Centralized Log Management
Collects and stores logs from multiple sources such as servers, endpoints, firewalls, and applications in a single location.

2. Real-Time Monitoring
Continuously monitors system activities and network events to identify suspicious behavior as it happens.

3. Threat Detection & Correlation
Analyzes logs using correlation rules to detect patterns that indicate potential security threats or attacks.

4. Alerting & Notifications
Generates alerts when abnormal or malicious activities are detected, enabling quick response.

5. Incident Response Support
Provides detailed insights and timelines to help security teams investigate and respond to incidents effectively.

6. Compliance & Reporting
Helps organizations meet regulatory requirements by generating reports for standards like ISO, PCI-DSS, etc.

7. User Activity Monitoring
Tracks user behavior to detect unauthorized access or insider threats.

8. Data Visualization & Dashboards
Displays security data through dashboards and graphs for easy analysis and decision-making.

9. Log Retention & Forensics
Stores historical data for forensic analysis and future investigations.

10. Scalability
Supports growing infrastructure by handling large volumes of data across multiple systems

# 🧩 Modules of SIEM (Security Information and Event Management)

1. Log Collection Module
Gathers logs from various sources such as endpoints, servers, network devices, and applications.

2. Log Normalization Module
Converts different log formats into a standard format for easier analysis and correlation.

3. Event Correlation Module
Analyzes logs using predefined rules to identify suspicious patterns and potential threats.

4. Alerting Module
Generates alerts and notifications when security incidents or anomalies are detected.

5. Data Storage Module
Stores collected logs and events securely for future analysis and compliance purposes.

6. Analysis & Monitoring Module
Provides real-time monitoring and analysis of events to detect unusual activities.

7. Dashboard & Visualization Module
Displays logs and alerts in graphical formats like charts and dashboards for better understanding.

8. Incident Response Module
Supports investigation and response by providing detailed event information and timelines.

9. Reporting Module
Generates reports for audits, compliance, and security assessments.

10. Agent Management Module
Manages connected agents (like Windows systems) and ensures proper communication with the SIEM server

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

a) Use Ubuntu as the SIEM Server
b) Responsible for log collection, analysis, and threat detection
c) Hosts the SIEM platform (e.g., Wazuh/ELK stack)
d) Use Windows 10 as the Agent System
e) Acts as an endpoint machine
f) Generates logs and security events
g) Sends collected data to the SIEM server for monitoring

# ✅ Advantages of SIEM

1) Centralized Log Management
Collects and manages logs from multiple systems in one place.

2) Real-Time Threat Detection
Identifies security threats and suspicious activities instantly.

3) Improved Incident Response
Helps quickly analyze and respond to security incidents.

4) Compliance Support
Assists in meeting regulatory requirements through logging and reporting.

5) Better Visibility
Provides clear insights into system and user activities across the network.

## 👤 Author

**Anandaraj Alwin Raj**  
SOC Analyst | Security Researcher |

- GitHub: https://github.com/alwin-github  
- LinkedIn: https://www.linkedin.com/in/anandarajalwinraj/  
- Medium: https://medium.com/@alwinraj  



