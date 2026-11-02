# Secure Emergency Response Network

## Project Overview

A Cisco Packet Tracer-based networking project designed to connect four emergency service departments:

- Emergency Operations Center (EOC)
- Hospital
- Police Department
- Fire Department

The project demonstrates network segmentation, dynamic routing, IP address allocation and access control.

## Technologies Used

- Cisco Packet Tracer
- VLANs
- Inter-VLAN Routing (Router-on-a-Stick)
- OSPF Dynamic Routing
- DHCP
- Extended Access Control Lists (ACLs)

## Network Configuration

### EOC VLANs

| VLAN ID | VLAN Name | Network |
|---|---|---|
| 10 | CONTROL | 192.168.10.0/24 |
| 20 | ADMIN | 192.168.11.0/24 |
| 30 | SERVER | 192.168.12.0/24 |

### Department Networks

| Department | Network |
|---|---|
| Hospital | 192.168.20.0/24 |
| Police | 192.168.30.0/24 |
| Fire | 192.168.40.0/24 |

## Routing

OSPF is used for dynamic routing and exchanging routing information between routers.

## Security

Extended ACLs control communication between selected departmental networks.

## DHCP

DHCP is configured for the EOC networks. Configuration and testing for other departments should be documented according to the verified implementation.

## Repository Structure

- `Packet-Tracer/` – Network simulation files.
- `Documentation/` – Project report.
- `Configurations/` – Router configurations.
- `Screenshots/` – Network configuration and testing evidence.
- `Diagrams/` – Network architecture diagrams.

## Project Objective

To design and simulate a segmented and access-controlled emergency response network that enables communication between emergency departments while restricting unauthorized traffic.
