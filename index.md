<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Deploying My Own Security Operations Center (SOC)</title>
</head>
<body>
    <h1>Deploying My Own Security Operations Center (SOC)</h1>
    
    <h2>Overview</h2>
    <p>This project aims to build a fully operational SOC that leverages the power of Azure and Juniper to enhance cybersecurity capabilities. The project includes deploying a SIEM system, setting up a threat intelligence feed that sends Indicators of Compromise (IOCs) directly, implementing robust network security measures, and simulating a deauthentication attack with a Flipper Zero.</p>
    
    <h2>Components of the Project</h2>
    <ul>
        <li><strong>SIEM Deployment</strong>
            <ul>
                <li><strong>Azure Sentinel:</strong> The SIEM solution collects, analyzes, and responds to security data from multiple sources.</li>
                <li><strong>Data Connectors:</strong> Integrates logs from various sources such as Azure services, Office 365, and custom data sources.</li>
                <li><strong>Incident Response:</strong> Configures automated response workflows using Azure Logic Apps.</li>
            </ul>
        </li>
        <li><strong>Threat Intelligence</strong>
            <ul>
                <li><strong>Threat Intelligence Feeds:</strong> Sets up feeds to receive IOCs directly, providing real-time updates on malicious IPs, domains, and file hashes.</li>
                <li><strong>Automation:</strong> Implements workflows to ingest and analyze threat intelligence data.</li>
                <li><strong>Alerts:</strong> Configures alerts for immediate notification of potential threats.</li>
            </ul>
        </li>
        <li><strong>Network Segmentation</strong>
            <ul>
                <li><strong>Juniper EX2200-C:</strong> Sets up network segmentation to improve security and manage traffic more effectively.</li>
                <li><strong>VLAN Configuration:</strong> Assigns VLANs to different segments of the network.</li>
            </ul>
        </li>
        <li><strong>Intrusion Detection System (IDS)</strong>
            <ul>
                <li><strong>Snort:</strong> Uses Snort to monitor and analyze network traffic for suspicious activities.</li>
            </ul>
        </li>
        <li><strong>VPN Configuration</strong>
            <ul>
                <li><strong>OpenVPN:</strong> Configures and tests VPNs for secure remote access.</li>
            </ul>
        </li>
        <li><strong>Firewall Rules</strong>
            <ul>
                <li><strong>Firewall Configuration:</strong> Develops and tests complex firewall rules to protect the network from various threats.</li>
            </ul>
        </li>
        <li><strong>Access Control Lists (ACLs)</strong>
            <ul>
                <li><strong>Traffic Control:</strong> Implements ACLs to control traffic flow and enhance security.</li>
            </ul>
        </li>
        <li><strong>Network Monitoring</strong>
            <ul>
                <li><strong>Juniper Tools:</strong> Uses Juniper's tools to monitor network performance and detect anomalies.</li>
            </ul>
        </li>
        <li><strong>Security Policies</strong>
            <ul>
                <li><strong>Policy Development:</strong> Develops and enforces security policies across the network.</li>
            </ul>
        </li>
        <li><strong>SIEM Integration</strong>
            <ul>
                <li><strong>Integration with Juniper:</strong> Integrates Juniper routers with a SIEM system to centralize security monitoring.</li>
            </ul>
        </li>
        <li><strong>Deauthentication Attack Simulation</strong>
            <ul>
                <li><strong>Flipper Zero:</strong> Simulates a deauthentication attack using Flipper Zero to understand potential vulnerabilities and test network defenses.</li>
            </ul>
        </li>
    </ul>
    
    <h2>Detailed Implementation</h2>
    
    <h3>SIEM Deployment</h3>
    <p>Using Azure Sentinel, I set up a comprehensive SIEM solution that aggregates logs from various sources such as Azure services and Office 365. Automated incident response workflows are configured using Azure Logic Apps.</p>
    <p><strong>[Screenshot 1: Azure Sentinel Dashboard]</strong></p>
    
    <h3>Threat Intelligence</h3>
    <p>I set up threat intelligence feeds to receive IOCs, providing real-time updates on malicious activities. Automated workflows ensure timely ingestion and analysis of threat data.</p>
    <p><strong>[Screenshot 2: Threat Intelligence Configuration]</strong></p>
    
    <h3>Network Segmentation</h3>
    <p>The network is segmented using Juniper EX2200-C to create VLANs, improving security and traffic management. Inter-VLAN routing is configured to allow controlled communication between segments.</p>
    <p><strong>[Video 1: VLAN Configuration on Juniper EX2200-C]</strong></p>
    
    <h3>Intrusion Detection System (IDS)</h3>
    <p>Snort is deployed to monitor network traffic and detect suspicious activities. This ensures real-time analysis and prompt response to potential threats.</p>
    <p><strong>[Screenshot 3: Snort IDS Alerts]</strong></p>
    
    <h3>VPN Configuration</h3>
    <p>OpenVPN is used to set up secure remote access, ensuring encrypted communication channels for users accessing the network from remote locations.</p>
    <p><strong>[Video 2: OpenVPN Configuration and Testing]</strong></p>
    
    <h3>Firewall Rules and ACLs</h3>
    <p>Complex firewall rules and Access Control Lists (ACLs) are developed to control network traffic and enhance security. This includes filtering unauthorized access and potential threats.</p>
    <p><strong>[Screenshot 4: Firewall Rules Configuration]</strong></p>
    
    <h3>Network Monitoring</h3>
    <p>Juniper’s tools are utilized for continuous network monitoring, enabling the detection of performance issues and anomalies.</p>
    <p><strong>[Video 3: Network Performance Monitoring]</strong></p>
    
    <h3>Security Policies</h3>
    <p>Security policies are developed and enforced across the network to ensure a secure and compliant environment.</p>
    
    <h3>SIEM Integration</h3>
    <p>The SIEM is integrated with Juniper routers to centralize security monitoring and provide a unified view of network activities.</p>
    
    <h3>Deauthentication Attack Simulation</h3>
    <p>A deauthentication attack is simulated using Flipper Zero to test the network’s resilience and identify potential vulnerabilities.</p>
    <p><strong>[Video 4: Deauthentication Attack Simulation]</strong></p>
    
    <h2>Conclusion</h2>
    <p>This project showcases my ability to deploy and manage a SOC using Microsoft Azure and Juniper EX2200-C switch. By integrating a SIEM system, setting up a threat intelligence feed, implementing network segmentation, and using advanced security tools, I can effectively monitor, detect, and respond to security threats in real-time. The addition of a deauthentication attack simulation using Flipper Zero highlights my practical skills in identifying and mitigating potential network vulnerabilities.</p>
    
    <table>
        <tr>
            <th>Component</th>
            <th>Description</th>
        </tr>
        <tr>
            <td>SIEM Deployment</td>
            <td>Using Azure Sentinel</td>
        </tr>
        <tr>
            <td>Threat Intelligence</td>
            <td>Real-time IOC updates and analysis</td>
        </tr>
        <tr>
            <td>Network Segmentation</td>
            <td>Using Juniper EX2200-C switch</td>
        </tr>
        <tr>
            <td>Intrusion Detection</td>
            <td>Snort for traffic monitoring</td>
        </tr>
        <tr>
            <td>VPN Configuration</td>
            <td>Secure access with OpenVPN</td>
        </tr>
        <tr>
            <td>Firewall Rules</td>
            <td>Complex firewall configurations</td>
        </tr>
        <tr>
            <td>Access Control Lists</td>
            <td>Control traffic flow and enhance security</td>
        </tr>
        <tr>
            <td>Network Monitoring</td>
            <td>Juniper tools for performance monitoring</td>
        </tr>
        <tr>
            <td>Security Policies</td>
            <td>Development and enforcement</td>
        </tr>
        <tr>
            <td>SIEM Integration</td>
            <td>Centralized monitoring with Juniper routers</td>
        </tr>
        <tr>
            <td>Deauthentication Simulation</td>
            <td>Flipper Zero for vulnerability testing</td>
        </tr>
    </table>
    
    <pre>
    Building a SOC involves integrating various components to create a cohesive security system. This project showcases the practical implementation of these components to enhance network security.
    </pre>
    
    <pre>
    Deploying a SIEM and setting up threat intelligence feeds are crucial
