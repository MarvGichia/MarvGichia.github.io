---
title: "Lab – WLAN Configuration in Packet Tracer"
date: 2025-11-17 12:00:00 +0300
categories: [Labs]
tags: [Wireless, WLAN, PacketTracer, Security]
description: "Deploying a secure wireless LAN with WPA2 encryption and routed connectivity."
---

![WLAN topology linking AP to routed LAN](/assets/img/Lab%202/wlantopology.png)
*Packet Tracer layout showing the secure WLAN bridged into the routed LAN core.*

## Problem Statement

Deploy and secure a wireless LAN with proper authentication and encryption.

## Approach

1. Configured the wireless access point SSID and set WPA2-PSK with a strong passphrase.  
2. Assigned IP addressing to WLAN clients and integrated the AP into the core LAN through a router-on-a-stick design.  
3. Enabled DHCP on the router so wireless devices receive scoped addresses.  
4. Built static routes / default routes to ensure bidirectional connectivity between the WLAN and rest of the network.  
5. Performed connectivity and security validation using Packet Tracer simulation mode.

## Tools Used

- Cisco Packet Tracer

## Key Lessons Learned

- Strong encryption is essential to prevent Wi-Fi attacks.  
- WLAN-to-LAN integration requires correct routing and DHCP.  
- Wireless misconfigurations are a major vulnerability.  

![WPA2-PSK authentication settings](/assets/img/Lab%202/WPA2%20authentication.png)
*Access point configured with WPA2-PSK and a strong passphrase for clients.*

![DHCP lease allocated to wireless client](/assets/img/Lab%202/IP%20allocated%20via%20DHCP.png)
*Wireless workstation receiving its scoped IP via router-based DHCP service.*






