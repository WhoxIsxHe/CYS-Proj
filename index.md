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
