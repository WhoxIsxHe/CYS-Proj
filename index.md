## <span class="header">Deploying My Own Security Operations Center (SOC)</span>

## <span class="header">Overview:</span>
This project aims to build a fully operational SOC that leverages the power of Azure and Juniper to enhance cybersecurity capabilities. The project includes deploying a SIEM system, setting up a threat intelligence feed that sends Indicators of Compromise (IOCs) directly, implementing robust network security measures, and simulating a deauthentication attack with a Flipper Zero.

## <span class="header">Components of the Project</span>-

*Azure Sentinel*: The SIEM solution collects, analyzes, and responds to security data from multiple sources.

*Data Connectors*: Integrates logs from various sources such as Azure services, Office 365, and custom data sources.

*Incident Response*: Configures automated response workflows using Azure Logic Apps.

## <span class="sub-header">Threat Intelligence</span>-

*Threat Intelligence Feeds*: Sets up feeds to receive IOCs directly, providing real-time updates on malicious IPs, domains, and file hashes.

*Automation*: Implements workflows to ingest and analyze threat intelligence data.

*Alerts*: Configures alerts for immediate notification of potential threats.

## <span class="sub-header">Network Segmentation</span>-

*Juniper EX2200-C*: Sets up network segmentation to improve security and manage traffic more effectively.

*VLAN Configuration*: Assigns VLANs to different segments of the network.

## <span class="sub-header">Intrusion Detection System (IDS)</span>-

*Snort*: Uses Snort to monitor and analyze network traffic for suspicious activities.

## <span class="sub-header">VPN Configuration</span>-

*OpenVPN*: Configures and tests VPNs for secure remote access.

## <span class="sub-header">Firewall Rules</span>-

*Firewall Configuration*: Develops and tests complex firewall rules to protect the network from various threats.

## <span class="sub-header">Access Control Lists (ACLs)</span>-

*Traffic Control*: Implements ACLs to control traffic flow and enhance security.

## <span class="sub-header">Network Monitoring</span>-

*Juniper Tools*: Uses Juniper's tools to monitor network performance and detect anomalies.

## <span class="sub-header">Security Policies</span>-

*Policy Development*: Develops and enforces security policies across the network.

## <span class="sub-header">SIEM Integration</span>-

*Integration with Juniper*: Integrates Juniper routers with a SIEM system to centralize security monitoring.

## <span class="sub-header">Deauthentication Attack Simulation</span>:

*Flipper Zero*: Simulates a deauthentication attack using Flipper Zero to understand potential vulnerabilities and test network defenses.

## <span class="header">Detailed Implementation</span>
Using Azure Sentinel, I set up a comprehensive SIEM solution that aggregates logs from various sources such as Azure services and Office 365. Automated incident response workflows are configured using Azure Logic Apps.

[Screenshot 1: Azure Sentinel Dashboard]

## <span class="sub-header">Threat Intelligence</span>
I set up threat intelligence feeds to receive IOCs, providing real-time updates on malicious activities. Automated workflows ensure timely ingestion and analysis of threat data.

[Screenshot 2: Threat Intelligence Configuration]

## <span class="sub-header">Network Segmentation</span>
The network is segmented using Juniper EX2200-C to create VLANs, improving security and traffic management. Inter-VLAN routing is configured to allow controlled communication between segments.

[Video 1: VLAN Configuration on Juniper EX2200-C]

## <span class="sub-header">Intrusion Detection System</span>
Snort is deployed to monitor network traffic and detect suspicious activities. This ensures real-time analysis and prompt response to potential threats.

[Screenshot 3: Snort IDS Alerts]

## <span class="sub-header">VPN Configuration</span>
OpenVPN is used to set up secure remote access, ensuring encrypted communication channels for users accessing the network from remote locations.

[Video 2: OpenVPN Configuration and Testing]

## <span class="sub-header">Firewall Rules and ACLs</span>
Complex firewall rules and Access Control Lists (ACLs) are developed to control network traffic and enhance security. This includes filtering unauthorized access and potential threats.

[Screenshot 4: Firewall Rules Configuration]

## <span class="sub-header">Network Monitoring</span>
Juniper’s tools are utilized for continuous network monitoring, enabling the detection of performance issues and anomalies.

[Video 3: Network Performance Monitoring]

## <span class="sub-header">Security Policies</span>
Security policies are developed and enforced across the network to ensure a secure and compliant environment.

## <span class="sub-header">SIEM Integration</span>
The SIEM is integrated with Juniper routers to centralize security monitoring and provide a unified view of network activities.

## <span class="sub-header">Deauthentication Attack Simulation</span>
A deauthentication attack is simulated using Flipper Zero to test the network’s resilience and identify potential vulnerabilities.

[Video 4: Deauthentication Attack Simulation]

## <span class="header">Conclusion</span>
This project showcases my ability to deploy and manage a SOC using Microsoft Azure and Juniper EX2200-C switch. By integrating a SIEM system, setting up a threat intelligence feed, implementing network segmentation, and using advanced security tools, I can effectively monitor, detect, and respond to security threats in real-time. The addition of a deauthentication attack simulation using Flipper Zero highlights my practical skills in identifying and mitigating potential network vulnerabilities.
