# Network-traffic-capture-and-analysis-with-Wireshark 
## AIM:
To capture and analyze network traffic using Wireshark in order to observe protocols, packets, and potential anomalies.
## Requirements:
- **Hardware:**
    - Computer with internet access
    - Network adapter (Ethernet/Wi-Fi)
- **Software:**
    - Wireshark (latest stable version)
    - Sample PCAP files (optional for offline analysis)
## Architecture:
```mermaid
flowchart TD
    A[Network Interface Card] --> B[Wireshark Packet Capture Engine]
    B --> C[Packet Decoder & Protocol Analyzer]
    C --> D[Packet Display & Filtering Interface]
    D --> E[Investigator Analyzes Network Data]
    E --> F[Findings: IPs, Ports, Protocols, Anomalies]
```
## DESIGN STEPS:
### Step 1:
Install Wireshark on the system.

### Step 2:
Launch Wireshark and select the network interface (Ethernet/Wi-Fi).

### Step 3:
Start the capture, apply filters (like http, tcp, ip.addr == x.x.x.x) to analyze specific traffic, and stop the capture after observing relevant data.
### Step 4:
**Analyze traffic to identify:**
  - Source & Destination IP addresses
  - Protocols (HTTP, DNS, TCP, UDP, etc.)
  - Suspicious activities (e.g., unusual ports, repeated requests).
## PROGRAM:
Wireshark Packet Capture and Filter Usage

## OUTPUT:
## OUTPUT:
- Captured Packets with Protocol Analysis and Detailed Packet Info
<img width="1920" height="1080" alt="KALI 2  Running  - Oracle VirtualBox 10-10-2025 08_23_42" src="https://github.com/user-attachments/assets/426ef9df-aebd-4ecb-843a-04efe3da99ea" />


- ## Start Capturing Packets
• Click the blue shark fin icon or double-click the interface.
• Wireshark will start capturing all real-time traffic.
<img width="1920" height="1080" alt="KALI 2  Running  - Oracle VirtualBox 10-10-2025 08_35_22" src="https://github.com/user-attachments/assets/b80d0bdd-da0a-4ffc-b9e0-76767a6f0d06" />





- ## Apply Filters to Focus on Specific Traffic
• Use filters like http, ip.addr == 192.168.1.1, or tcp.port == 80 in the top filter bar to narrow down results.

<img width="1920" height="1080" alt="KALI 2  Running  - Oracle VirtualBox 10-10-2025 08_35_29" src="https://github.com/user-attachments/assets/ad94c182-563a-4c67-a64c-86dbd6d4a20e" />


- ## Analyze Packet Details
• Click on a packet to view its detailed breakdown including frame, Ethernet,IP, TCP/UDP layers, and data payload.
<img width="1920" height="1080" alt="KALI 2  Running  - Oracle VirtualBox 10-10-2025 08_37_16" src="https://github.com/user-attachments/assets/bc9d934a-1163-49ce-bbdf-ee281889bc21" />

<img width="1920" height="1080" alt="KALI 2  Running  - Oracle VirtualBox 10-10-2025 08_35_35" src="https://github.com/user-attachments/assets/3b23e12d-77de-41fb-a0af-027d2f676910" />
<img width="1920" height="1080" alt="KALI 2  Running  - Oracle VirtualBox 10-10-2025 09_47_46" src="https://github.com/user-attachments/assets/35e2e39b-bbc9-4f64-a271-ebaf3fd8c10a" />
<img width="1920" height="1080" alt="KALI 2  Running  - Oracle VirtualBox 10-10-2025 09_48_20" src="https://github.com/user-attachments/assets/ce36a54c-6f3b-45f6-9a6a-d0b910b776c5" />
<img width="1920" height="1080" alt="KALI 2  Running  - Oracle VirtualBox 10-10-2025 09_49_55" src="https://github.com/user-attachments/assets/b51410ce-1e8a-43cf-8c56-535a7aca51e7" />


## RESULT:
Network traffic was successfully captured and analyzed using Wireshark.
