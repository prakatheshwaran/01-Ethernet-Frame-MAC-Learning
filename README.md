# Experiment 1: Ethernet Frame Analysis & MAC Address Learning

## Objective

To understand how a Layer 2 switch processes Ethernet frames and performs MAC address learning, flooding, and forwarding using Cisco Packet Tracer.

## Topology

PC0 ─── Switch0 ─── PC1

- PC0: 192.168.1.10/24
- PC1: 192.168.1.20/24
- Switch: Cisco 2960

## Concepts Covered

- Ethernet II Frame
- Source MAC Address
- Destination MAC Address
- Incoming Port
- Outgoing Port
- MAC Address Learning
- MAC Address Table
- Flooding
- Forwarding
- ARP
- ICMP

## Experiment

1. Configure IP addresses on PC0 and PC1.
2. Connect both PCs to a Cisco 2960 switch.
3. Test connectivity using ping.
4. Observe the switch MAC address table.
5. Clear the dynamic MAC address table.
6. Use Simulation Mode to observe packet flow.
7. Analyze the Ethernet II frame.
8. Observe source and destination MAC addresses.
9. Identify incoming and outgoing switch ports.

## Verification

Command used on the switch:

```bash
enable
show mac address-table
