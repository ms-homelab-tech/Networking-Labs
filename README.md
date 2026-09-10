# Small Office Networking Deployment & Troubleshooting

## Project Overview

This project demonstrates the deployment and troubleshooting of a small office network using a star topology. The network consists of one router, one switch, one server, one printer, and three PCs, with the switch serving as the central connection point for all devices.

Static IP addressing was configured for the network devices, and an FTP server was configured and tested successfully. Network connectivity between the devices was verified, and additional troubleshooting and verification were performed by checking the MAC address table and interface status on the switch.

As part of the troubleshooting process, three simulated network support tickets were created to identify and resolve configuration issues. The troubleshooting scenarios included an incorrect network/subnet mask, an incorrect default gateway, and an administratively shut-down interface. Each issue was investigated, corrected, and tested to verify that network connectivity was restored.

## Network Topology

![Network Topology](./Screenshots/network-topology.png)

## Project Structure

- [`Caption1.pkt`](./Caption1.pkt) — Cisco Packet Tracer project file containing the network topology and configurations.
- [`Lab_Documentations--Networking--Basic.pdf`](./Lab_Documentations--Networking--Basic.pdf) — Detailed project documentation covering the network deployment, configuration, testing, and troubleshooting.
- [`Screenshots/`](./Screenshots/) — Screenshots showing the network topology, connectivity testing, FTP testing, MAC address table, and interface status.
