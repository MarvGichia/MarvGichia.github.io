---
title: "Lab – Using Wireshark to Examine Network Traffic"
date: 2025-11-17 14:00:00 +0300
categories: [Labs]
tags: [Wireshark, Packet-Analysis, Monitoring, ThreatDetection]
description: "Capturing and analyzing packet flows to uncover unsafe traffic patterns."
---

![Wireshark capture highlighting Google HTTP traffic](/assets/img/Lab%203/google.png)
*Filtered capture showing HTTP requests to google.com alongside DNS and TCP details.*

## Problem Statement

Capture and analyze network packet flows to identify unsafe traffic patterns and potential threats.

## Approach

1. Launched Wireshark on a Linux terminal and captured traffic on the monitoring interface.  
2. Applied display filters for ICMP, TCP three-way handshakes, DNS queries, and HTTP requests to focus on key flows.  
3. Marked anomalies such as retransmissions, suspicious HTTP headers, and unexpected DNS responses.  
4. Exported capture slices for documentation and future replay.

## Tools Used

- Wireshark  
- Linux terminal utilities

## Key Lessons Learned

- Packet analysis is key in detecting anomalies.  
- Filtering is vital for isolating suspicious traffic.  
- Understanding behavior from OSI Layer 3–7 helps pinpoint threats early.  
