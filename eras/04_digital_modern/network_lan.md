# Era: Digital — LAN Evolution

## 1. Executive Summary
Local Area Networks (LANs) facilitated the first step in interconnecting desktop computing power, shifting from isolated mainframes to networked, collaborative workstation clusters.

## 2. Theoretical Principles
Utilizes **shared medium access** or **switched topologies**. Based on **CSMA/CD** (early Ethernet) or **MAC-based switching** (modern Ethernet), providing high-speed, low-latency connectivity within a limited geographic radius.

## 3. The ASCII Representation
```text
  [Host A] --(Physical Link)--> [Network Switch (L2)] <-> [Router (L3)] --> [Internet]
                                        |
                                 [Host B/C/D...]
```

## 4. Historical Context & Societal Impact
Enabled local collaboration in business and academia, birthed the concept of "network resources" (files, printers), and provided the blueprint for building larger interconnected structures.

## 5. Technical Limitations & Challenges
Broadcast storm management (loop detection), limited physical distance (without repeaters/fiber), and bandwidth bottlenecking in shared-medium topologies.

## 6. Key Innovations/Enablers
- **Ethernet (IEEE 802.3):** The standardized robust physical/link layer.
- **Layer 2 Switches:** Intelligent traffic segmentation (VLANs, MAC learning).

## 7. Related Concepts
- [Internet Protocols](../04_digital_modern/network_protocols.md)
- [Packet Switching](../04_digital_modern/network_packet.md)
