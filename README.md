# TRex-Inc-APT-Tactics-Detection-and-Network-Analysis-PartB

[View Project File](https://github.com/Viney-Washington/TRex-Inc-APT-Tactics-Detection-and-Network-Analysis-PartB/blob/main/Viney%20Washington_%20Part%20B%20Target%20Simulation%20Attack%20Part%202.pdf)

## Overview
This project continues the analysis of an Advanced Persistent Threat (APT) attack within the BioGenX environment, focusing on lateral movement, persistence mechanisms, and data exfiltration techniques used after initial compromise.

## Objectives
- Analyze APT attack phases including lateral movement and persistence  
- Identify command-and-control (C2) communication patterns  
- Detect indicators of compromise across the network  
- Evaluate vulnerabilities that enabled continued access  
- Recommend mitigation strategies to strengthen network security  

## Tools Used
- Wireshark  
- PCAP Traffic Analysis  
- Network Monitoring Techniques  

## Key Findings
- Evidence of lateral movement between systems within the network  
- Persistent outbound communication with external command-and-control servers  
- Data exfiltration attempts through monitored traffic channels  
- Abnormal traffic patterns consistent with long-term unauthorized access  
- Attack behavior aligned with known APT lifecycle phases  

## Vulnerability Analysis
The attack was enabled by weak network segmentation, insufficient monitoring of internal traffic, and lack of detection for persistent connections. These gaps allowed attackers to expand access and maintain long-term control within the environment.

## Recommendations
- Implement network segmentation to limit lateral movement  
- Enhance monitoring of east-west traffic within the network  
- Deploy intrusion detection and prevention systems (IDS/IPS)  
- Enforce least privilege access controls  
- Strengthen logging and continuous monitoring capabilities  

## Conclusion
This project demonstrates how Advanced Persistent Threat actors maintain persistence and expand access within a network while avoiding detection, highlighting the importance of layered security controls and continuous monitoring.
