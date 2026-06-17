# Cisco Routing and Switching Lab Portfolio

A structured collection of network topology blueprints, device subnet schemas, and static routing paths implemented within Cisco Packet Tracer.


## Assignment 1: Dual-Router Core Network Matrix (task1.pkt)

This configuration establishes symmetrical transit paths between two distinct local area networks using dedicated FastEthernet links and a point-to-point WAN Serial interface.

### Network Architecture Parameters

* **Local LAN 1 Network:** 192.168.1.0/24 (Gateway: 192.168.1.1)
* **Core WAN Serial Link:** 10.0.0.0/30 (Inter-router connectivity link)
* **Remote LAN 2 Network:** 192.168.2.0/24 (Gateway: 192.168.2.1)

### Next-Hop Static Routing Configuration Matrix

* **Router 1 Path Map:** ip route 192.168.2.0 255.255.255.0 10.0.0.2
* **Router 2 Path Map:** ip route 192.168.1.0 255.255.255.0 10.0.0.1


## Assignment 2: Intermediate Network Infrastructure (task 3 (1).pkt)

This lab assignment expands upon basic point-to-point routing by introducing intermediate switch configurations, expanded subnet boundaries, and multiple active client nodes across the topology to simulate a growing mid-sized office deployment.


## Assignment 3: Enterprise Simulation Architecture (project 4.pkt)

A comprehensive enterprise-level network layout simulating a complete corporate environment. This file demonstrates advanced configurations including VLAN segmentation, custom IP addressing schemas across multiple departments, and optimized path routing to ensure reliable network redundancy and security.
