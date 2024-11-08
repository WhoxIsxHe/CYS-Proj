# Deploying My Own Security Operations Center (SOC)
# Overview
This project aims to build a fully operational SOC that leverages the power of Azure and Juniper to enhance cybersecurity capabilities. The project includes deploying a SIEM system, setting up a threat intelligence feed that sends Indicators of Compromise (IOCs) directly, implementing robust network security measures, and simulating a deauthentication attack with a Flipper Zero.

| [# Component]                  | [# Description]                            |
|:----------------------------|:------------------------------------------|
| SIEM Deployment             | Using Azure Sentinel                      |
| Threat Intelligence         | Real-time IOC updates and analysis        |
| Network Segmentation        | Using Juniper EX2200-C switch             |
| Intrusion Detection         | Snort for traffic monitoring              |
| VPN Configuration           | Secure access with OpenVPN                |
| Firewall Rules              | Complex firewall configurations           |
| Access Control Lists        | Control traffic flow and enhance security |
| Network Monitoring          | Juniper tools for performance monitoring  |
| Security Policies           | Development and enforcement               |
| SIEM Integration            | Centralized monitoring with Juniper router|
| Deauthentication Simulation | Flipper Zero for vulnerability testing    |

 # Detailed Implementation

# [SIEM Deployment]
*Using Azure Sentinel, I set up a comprehensive SIEM solution that aggregates logs from various sources such as Azure services and Office 365. Automated incident response workflows are configured using Azure Logic Apps.*

[Screenshot 1: Azure Sentinel Dashboard]

# [Threat Intelligence]
*I set up threat intelligence feeds to receive IOCs, providing real-time updates on malicious activities. Automated workflows ensure timely ingestion and analysis of threat data.*

[Screenshot 2: Threat Intelligence Configuration]

# [Network Segmentation]
*The network is segmented using Juniper EX2200-C to create VLANs, improving security and traffic management. Inter-VLAN routing is configured to allow controlled communication between segments.*

[Video 1: VLAN Configuration on Juniper EX2200-C]

# [Intrusion Detection System] 
*Snort is deployed to monitor network traffic and detect suspicious activities. This ensures real-time analysis and prompt response to potential threats.*

[Screenshot 3: Snort IDS Alerts]

# [VPN Configuration]
*OpenVPN is used to set up secure remote access, ensuring encrypted communication channels for users accessing the network from remote locations.*

[Video 2: OpenVPN Configuration and Testing]

# [Firewall Rules and ACLs]
*Complex firewall rules and Access Control Lists (ACLs) are developed to control network traffic and enhance security. This includes filtering unauthorized access and potential threats.*

[Screenshot 4: Firewall Rules Configuration]

# [Network Monitoring]
*Juniper’s tools are utilized for continuous network monitoring, enabling the detection of performance issues and anomalies.*

[Video 3: Network Performance Monitoring]

# [Security Policies]
*Security policies are developed and enforced across the network to ensure a secure and compliant environment.*

# [SIEM Integration]
*The SIEM is integrated with Juniper routers to centralize security monitoring and provide a unified view of network activities.*

# [Deauthentication Attack Simulation]
*A deauthentication attack is simulated using Flipper Zero to test the network’s resilience and identify potential vulnerabilities.*

[Video 4: Deauthentication Attack Simulation]

# Conclusion

This project demonstrates my ability to deploy and manage a SOC using Microsoft Azure and Juniper EX2200-C switch. By integrating a SIEM system, setting up a threat intelligence feed, implementing network segmentation, and using advanced security tools, I can effectively monitor, detect, and respond to security threats in real-time. The addition of a deauthentication attack simulation using Flipper Zero highlights my practical skills in identifying and mitigating potential network vulnerabilities.
