# Summary Report — NZSE Technical Portfolio

This portfolio highlights my technical skills and projects in infrastructure roles, with a strong emphasis on secure, scalable, and resilient solutions. All content reflects coursework-based implementations and has been documented with transparency and accuracy.

## Overview
This report provides a concise overview of the technical modules, projects, and key learning outcomes from the NZQA Level 7 Diploma in Applied Networking and Cloud Technology (NZSE), complemented by ongoing part-time studies in multi-cloud security and systems administration (Yoobee Colleges).

## Key Achievements
- Designed and implemented hybrid cloud architectures utilizing Azure services (VPN Gateway, NSG, Bastion, Azure Firewall).
- Established secure enterprise environments through Active Directory, DNS, DHCP, and IIS configurations.
- Developed and deployed IoT systems using Raspberry Pi, MQTT protocol, and Adafruit IO dashboards for real-time monitoring.
- Conducted research on SDN, NFV, and network slicing, evaluating their impact on SLA and QoS.
- Successfully completed the [AWS Academy Cloud Foundations badge](https://www.credly.com/badges/68d16e7d-a6b6-47a8-aa6d-ed0719b164af) as part of Yoobee CCC601 module.

## Core Competencies and Industry Relevance
- Possesses a strong foundation in Microsoft Azure, actively expanding AWS proficiency through a multi-cloud program.
- Demonstrated ability to design secure, scalable, and resilient infrastructure, meeting diverse industry requirements.
- Capstone project experience includes hybrid cloud architecture design, comprehensive risk analysis, and business continuity planning.
- Committed to continuous learning and highly adaptable to diverse cloud environments, including AWS.

## Supporting Documents

See `/reports` for detailed module reports (PDF), including:

    - `DNCT702 Internet of Things Assessment 1.pdf`: Analysis of IoT system architecture and SDN integration strategy.
    - `Smart World’s IoT System Analysis and Recommendations for SDN Integration`: IoT dataflow analysis and SDN-based network design for smart sensor deployment.
    - `DNCT703 Network and Cloud Security A2.pdf`: Enterprise security risk assessment and mitigation planning.
    - `DNCT604 Cloud Infrastructure and Administration A2.pdf`: Comparative analysis of cloud service and deployment models, with Azure-focused hybrid architecture and risk mitigation strategies.
    - `DNCT704 Network and Cloud Design and A1.pdf`: Hybrid network design using SDN, NFV, and Fog computing, with BCP/DRP evaluation and Azure-based architecture for scalable and resilient infrastructure.
    - `DNCT704 Network and Cloud Design and A2.pdf`: Supplementary portfolio with implementation details, performance evaluation, and technical diagrams supporting hybrid cloud and network design strategies.
    - `DNCT701_Assessment2_Report_TakashiMurachi.pdf`: Wireless network systems project featuring VLAN segmentation, WLC configuration, EIGRP routing, DHCP optimization, and WPA2 security. Includes high-availability server design and bicultural integration aligned with industry standards.
    - `DNCT603 Network Infrastructure Administration A1`: Network infrastructure administration project including IP addressing corrections, VLAN configuration, static routing between Auckland and Wellington branches, and IPSec VPN setup. Demonstrates hands-on CLI troubleshooting and secure inter-branch connectivity aligned with industry infrastructure standards.
    - `DNCT603 Network Infrastructure Administration A2.pdf`: Full-cycle network infrastructure portfolio based on the PPDIOO model. Includes VLAN segmentation, high availability design, Windows Server (Nano, IIS, PowerShell), DNS and Active Directory configuration, and risk mitigation strategies aligned with industry requirements.
    - `Deploy a Static Website from GitHub to Azure.pdf`: Hands-on project deploying a static website from GitHub to Azure Storage. Includes repository setup, storage account provisioning, static website configuration, and HTML/CSS/JS deployment. Demonstrates practical understanding of Azure resource management, web hosting, and cost optimization aligned with industry cloud practices.
    - `Friday_activity_Takashi_Murachi_8_6_2024.pdf`: Azure VM deployment and backup configuration project. Includes Entra ID login setup and RBAC role assignment for secure access control, demonstrating identity management aligned with industry standards.
    - `Fridayactivity5.25.2024_Takashi_Murachi.pdf`: Supplementary documentation of the same static website deployment project. Reinforces Azure portal proficiency, GitHub integration, blob storage configuration, and cost-aware resource group management. Complements the main report with step-by-step screenshots and portal interactions.

    > *Note: The DNCT705 Capstone Project focused on planning and design. Due to confidentiality agreements, full reports are not publicly shared. This project encompassed feasibility analysis, stakeholder interviews, hybrid cloud architecture design, and proposals for Azure-based monitoring and access control. Relevant diagrams are available in the `/diagrams` folder.*

- See `/diagrams` for architecture visuals and network designs:
    - `dnct604-azure-monitor-alerts.png`: Alert and backup configuration diagram from DNCT604 Assessment 1, detailing:
    - CPU threshold alerts via Azure Monitor (configured using "CPU usage" metric over 60-minute range).
    - VM backup setup via Recovery Vault (including name, resource group, policy, frequency, and retention settings).
    - VM deletion notifications via email/SMS (triggered by VM deletion or CPU usage exceeding 83%).
    - Alert rules and action group setup in Azure Portal (defining conditions and notification channels).
    - `dnct703-enterprise-security-roles.png`: Enterprise security roles diagram from DNCT703 Assessment 1, summarizing layered strategies for:
    - Infrastructure security (insider threat, patch management).
    - Data protection (encryption, IDS/IPS).
    - Access management (MFA, IAM). 
    - `dnct704-hybrid-network-architecture.png`: Hybrid cloud design using VPN Gateway, Bastion, NSG, and Azure Firewall
    - - `dnct702-iot-dataflow.png`: Multi-layer IoT architecture diagram from DNCT702 Assessment 1, illustrating data flow from edge devices to cloud analytics and dashboard alerts, integrating MQTT/WebSocket protocols, Azure App Service, and disaster recovery zones.

    - `dnct705-capstone-risk-analysis.png`: Risk assessment matrix for hybrid infrastructure project
    - `aws-foundations-summary.png`: Overview of AWS services (EC2, S3, IAM, VPC) learned in CCC601


- See `/scripts` for deployment and automation examples (PowerShell, CLI, Python)
    Note: Scripts are not included in this portfolio. All configurations and implementation steps are documented within the module reports, based on coursework completed at NZSE. These reports reflect hands-on learning and demonstrate technical understanding aligned with industry infrastructure standards.

