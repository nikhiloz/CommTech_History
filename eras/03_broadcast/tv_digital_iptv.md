# Era: Broadcast — Digital and IPTV

## 1. Executive Summary
The shift from analog to digital television (DTV) allowed for vastly higher quality, efficient spectrum usage, and eventually, the interactivity of on-demand content (IPTV).

## 2. Theoretical Principles
Utilizes **digital signal processing (DSP)** and **compression algorithms (MPEG, H.264)** to reduce raw video bandwidth requirements. Signals are transmitted as discrete binary packets (DVB, ATSC) or encapsulated in IP (IPTV), enabling robust error correction and multiplexing.

## 3. The ASCII Representation
```text
  [Content Provider] -> [Encoder/Transcoder (MPEG)] -> [Streaming Server] --(IP Network)--> [Home Gateway/Router] -> [Set-Top Box] -> [Display]
                                                                                                  |
                                                                                         (QoS/Buffering)
```

## 4. Historical Context & Societal Impact
De-coupled television from fixed broadcast schedules, enabling VOD (Video On Demand) and personalized, non-linear media consumption.

## 5. Technical Limitations & Challenges
Sensitivity to packet loss (data corruption), requirement for high-speed network infrastructure, and complex digital rights management (DRM).

## 6. Key Innovations/Enablers
- **Video Compression (H.264/HEVC):** Essential for HD/4K streaming.
- **QoS (Quality of Service):** Managing streaming traffic over shared network links.

## 7. Related Concepts
- [Analog TV](../03_broadcast/tv_analog.md)
- [Packet Switching](../04_digital_modern/network_packet.md)
