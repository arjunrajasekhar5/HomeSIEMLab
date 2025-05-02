# Honeypot SOC Lab
This project sets up a home SOC (Security Operations Center) lab in Microsoft Azure to simulate real-world cyber attack monitoring and investigation. It involves deploying a Windows virtual machine (VM) configured as a honeypot, collecting security logs, and analyzing them with Microsoft Sentinel using Kusto Query Language (KQL).

# 🛠️ Features
Deployed a Windows VM in Azure configured as a honeypot to attract cyber attacks

Collected and centralized security logs using PowerShell and Azure Log Analytics

Analyzed security events with Microsoft Sentinel

Built dashboards and geographic visualizations to monitor attacker activity

Investigated attack patterns in real time using KQL queries

# 📦 Requirements
Microsoft Azure account

Azure subscription with VM quota

Microsoft Sentinel enabled in Azure

Basic knowledge of PowerShell and KQL

# 🚀 Setup Instructions
1) Create a Windows VM in Azure
     Deploy a Windows Server or Windows 10 VM.
     Open ports like RDP (3389) to attract attacks (in a safe lab environment).

2) Set up logging and monitoring
     Enable Log Analytics Workspace in Azure.
     Connect the VM to the workspace and install the Log Analytics agent.

3) Enable Microsoft Sentinel
     Activate Microsoft Sentinel on the workspace.
     Add connectors for Security Events and Windows Firewall.

4) Analyze attacks
     Write KQL queries in Sentinel to investigate attacks.
     Build dashboards and visualizations to monitor attacker behavior.

# 📸 Screenshots
![Screenshot 2025-04-30 100422](https://github.com/user-attachments/assets/4cd45fa6-97df-4b36-acb0-8495818307a4)
![Screenshot 2025-04-29 235234](https://github.com/user-attachments/assets/b7f425d7-6866-453b-8f2c-915b9aaf282c)
![Screenshot 2025-04-29 235200](https://github.com/user-attachments/assets/514a0406-caff-4de4-97b1-ba47a8e70a11)

# 🧰 Skills Demonstrated
Virtual Machines,
Azure Sentinel,
Remote Desktop Protocol (RDP),
Kusto Query Language (KQL),
Security monitoring and investigation

