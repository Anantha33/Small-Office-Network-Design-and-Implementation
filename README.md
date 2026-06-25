# Small-Office-Network-Design-and-Implementation

Completed a hands-on networking lab using Cisco Packet Tracer, focused on building and troubleshooting a small office network from scratch using CCNA-level concepts.

# What I built:

1. Designed a network with 3 departments segmented using VLANs (HR, Sales, IT)
2. Subnetted a /24 network into /26 subnets for proper IP allocation and scalability
3. Implemented inter-VLAN routing using a Router-on-a-Stick design
4. Configured 802.1Q trunking between a Cisco 2960 switch and Cisco 1941 router
5. Manually configured end devices with correct IPs, subnet masks, and default gateways

# VLAN & IP Design:

1. VLAN 10 (HR): 192.168.10.0/26 → Gateway: 192.168.10.1
2. VLAN 20 (Sales): 192.168.10.64/26 → Gateway: 192.168.10.65
3. VLAN 30 (IT): 192.168.10.128/26 → Gateway: 192.168.10.129

# What I learned:

1. How VLANs logically isolate traffic and improve network structure
2. How routers handle tagged traffic using subinterfaces
3. The importance of Layer 1 checks (cabling and port connections) during troubleshooting
4. How small misconfigurations (wrong port, inactive trunk) can break inter-VLAN communication
5. Using Cisco IOS commands to systematically verify and debug network state

# Outcome:

After correcting physical connections and trunk configuration, inter-VLAN communication was fully functional, with successful end-to-end connectivity across all departments.

This project reinforced that networking isn’t about memorising commands; it’s about understanding how traffic flows and knowing where to look when things don’t work.
