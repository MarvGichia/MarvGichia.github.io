---
title: "Lab – VLANs and Secure Switch Configuration"
date: 2025-11-17 10:00:00 +0300
categories: [Labs]
tags: [Networking, VLAN, Switching, Cisco]
description: "Configuring VLAN segmentation with secure switch features to block rogue devices."
---

![Topology overview for VLAN segmentation](/assets/img/Lab%201/topology.png)
*Network topology showing VLAN trunks, management, user, and guest segments.*

## Problem Statement

Configure VLAN segmentation on a network switch and implement secure port configurations to prevent rogue device access.

## Approach

1. Created multiple VLANs (Management, Users, Guests) and mapped access ports accordingly.  
2. Configured trunk links between switches to carry the tagged VLANs.  
3. Enabled port security with sticky MAC, shutdown violation action, and limited MAC counts per port.  
4. Activated BPDU Guard on all edge ports to block rogue switch introductions.  
5. Turned on DHCP Snooping to trust only authorized uplink ports and drop malicious DHCP responses.  
6. Verified segmentation and security posture with show commands and simulated rogue hosts.

## Tools Used

- Cisco Packet Tracer  
- Catalyst-style Switch CLI

## Key Lessons Learned

- VLAN segmentation improves network security and performance.  
- Port security prevents unauthorized access.  
- BPDU Guard protects against rogue switches.  
- DHCP Snooping blocks malicious DHCP servers.  

![BPDU Guard enabled on access ports](/assets/img/Lab%201/bpdu%20enabled.png)
*Spanning Tree BPDU Guard activated on all edge ports to block rogue switches.*

![Sticky MAC port security configuration](/assets/img/Lab%201/S1,S2%20Port%20security.png)
*Sticky MAC limits and shutdown violation mode applied on S1 and S2 interfaces.*

![DHCP Snooping binding verification](/assets/img/Lab%201/VERIFYING%20DHCP%20SNOOPING%20BINDING.png)
*DHCP Snooping binding table confirming trusted uplinks and dropped rogue servers.*






