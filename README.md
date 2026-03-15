This repository explores enterprise network design concepts that later informed the HybridOps platform.

Platform overview → https://hybridops.tech/why  
Documentation → https://docs.hybridops.tech

---

# Network Architecture & Optimisation Lab

Enterprise network architecture lab exploring traffic segmentation, routing resilience and high-availability switching design.

The project models a scalable network environment using Cisco Packet Tracer to demonstrate common enterprise networking patterns including VLAN segmentation, dynamic routing and redundancy mechanisms.

---

## Architecture Overview

The lab simulates a multi-layer enterprise network architecture including:

• Access layer switching for endpoint connectivity  
• Distribution layer routing and redundancy  
• Core routing and external connectivity  
• Wireless infrastructure integration  
• Voice network segmentation

---

## Core Network Components

### Access Layer

Access switches provide endpoint connectivity and segmentation.

Key configurations include:

• VLAN segmentation for data, voice and wireless traffic  
• Access and trunk port configuration  
• Spanning Tree PortFast and BPDU Guard for edge protection  
• Voice VLAN configuration for IP telephony devices

---

### Distribution Layer

Distribution switches provide routing, aggregation and redundancy.

Key capabilities:

• Inter-VLAN routing  
• OSPF dynamic routing configuration  
• HSRP gateway redundancy  
• Trunk links to access layer switches

---

### Core Routing

The core router provides external connectivity and routing aggregation.

Capabilities include:

• Layer 3 routing between internal networks  
• OSPF adjacency with distribution layer  
• WAN edge connectivity simulation

---

### Wireless Infrastructure

Wireless connectivity is integrated using:

• Wireless LAN Controller simulation  
• VLAN integration with wired infrastructure  
• Segmented wireless traffic routing

---

### Voice Infrastructure

The lab includes a basic voice architecture.

Features include:

• Dedicated Voice VLAN segmentation  
• DHCP configuration for IP phones  
• Telephony service configuration  
• IP phone auto-registration

---

## Routing Architecture

Dynamic routing is implemented using **OSPF**.

The configuration demonstrates:

• OSPF router ID configuration  
• Multi-area network advertisements  
• Route propagation between distribution and core layers  
• Simulated WAN connectivity

---

## High Availability

Redundancy is implemented using:

• HSRP for gateway redundancy  
• Multiple distribution switches  
• Spanning Tree protections  
• EtherChannel link aggregation

These mechanisms demonstrate common enterprise high-availability design patterns.

---

## Lab Environment

The network architecture is implemented using:

• Cisco Packet Tracer simulation  
• Multi-layer switching topology  
• Simulated WAN edge connectivity  
• Voice and wireless service integration

---

## Project Context

This project explores foundational concepts in enterprise network architecture including segmentation, redundancy and scalable routing design.

Many of the architectural ideas explored here later informed the networking design patterns used in the HybridOps platform.
