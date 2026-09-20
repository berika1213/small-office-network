# Small Office Network

A small office network designed and configured in Cisco Packet Tracer.

## Network Topology

The network consists of:

* 1 Cisco Router
* 1 Cisco Switch
* 3 PCs

## IP Addressing

| Device | IP Address   | Subnet Mask   | Default Gateway |
| ------ | ------------ | ------------- | --------------- |
| Router | 192.168.1.1  | 255.255.255.0 | —               |
| PC1    | 192.168.1.10 | 255.255.255.0 | 192.168.1.1     |
| PC2    | 192.168.1.11 | 255.255.255.0 | 192.168.1.1     |
| PC3    | 192.168.1.12 | 255.255.255.0 | 192.168.1.1     |

## Configuration

The router interface was configured with the IP address `192.168.1.1`.

Network connectivity was tested using the `ping` command.

## Files

* `small-office-network.pkt` — Cisco Packet Tracer project
* `topology.png` — Network topology screenshot
