# Era: Digital — Packet Switching

## 1. Executive Summary
Packet switching is the foundational network architecture that enabled the internet to exist by replacing dedicated circuit-switched channels with resilient, shared data-transfer paths.

## 2. Theoretical Principles
Data is segmented into **discrete packets**, each containing addressing information. Packets are **independently routed** through the network and reassembled at the destination. Enables high **statistical multiplexing** and fault tolerance.

## 3. The ASCII Representation
```text
  [Data Source] -> [Packetizer] -> [Routing Engine] -> [Interface/Buffer]
                                        |                  |
                                  [Routing Table]    (Outgoing Link)
```

## 4. Historical Context & Societal Impact
Allowed the scale of the global internet, breaking down geographic barriers for communication and enabling the digital information economy.

## 5. Technical Limitations & Challenges
Packet loss, out-of-order delivery (requiring reassembly logic), congestion management (buffering delays), and security risks (packet sniffing/interception).

## 6. Key Innovations/Enablers
- **Dynamic Routing:** Intelligent nodes capable of path finding.
- **Header Structure:** Standardized addressing to enable efficient routing.

## 7. Related Concepts
- [Internet Protocols](../04_digital_modern/network_protocols.md)
- [LAN Evolution](../04_digital_modern/network_lan.md)
