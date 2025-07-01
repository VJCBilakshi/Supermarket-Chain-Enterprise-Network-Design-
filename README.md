# 🛒 Supermarket Chain Enterprise Network Design  
**Module:** CN301.3 - Advanced Routing & Switching  
**Batch:** 22.2  
**Instructor:** Mr. Chamindra Attanayake  

---

## 📌 Overview

This project presents a comprehensive, scalable, and secure enterprise network design for a supermarket chain undergoing digital transformation. It addresses the infrastructure needs of three types of outlets — **Small**, **Standard**, and **Mega** — and a **central head office**.

The network is designed using best practices in routing, switching, VLAN segmentation, firewall deployment, wireless access, and software-defined networking concepts. It is demonstrated using **Cisco Packet Tracer** simulations.

---

## 🎯 Objectives

- Design a modern, enterprise-level network architecture
- Create detailed IP addressing and segmentation plans
- Implement VLAN-based service isolation across all branches
- Simulate the network using Cisco Packet Tracer
- Ensure support for services like VoIP, CCTV, PoE, public/staff Wi-Fi, digital signage, ATM, and delivery systems
- Plan for flexible outlet expansion and centralized control via SD-WAN simulation

---

## 🎯 VLAN Structure

| **VLAN ID** | **Name**         | **Purpose**                                        |
|-------------|------------------|----------------------------------------------------|
| 10          | Management        | Admin access, network operation center (NOC)       |
| 20          | POS               | Point of Sale systems (billing, checkout devices) |
| 30          | CCTV              | Security cameras and NVR systems                  |
| 40          | VoIP              | IP telephony and SIP devices                      |
| 50          | Staff Wi-Fi       | Secure wireless access for internal staff         |
| 60          | Customer Wi-Fi    | Open wireless for customers/guests                |
| 70          | Digital Ads       | Digital signage, LED panels, advertisement kiosks |
| 80          | ATM/Banking       | Banking systems, ATMs, third-party payment links  |
| 90          | Delivery/Orders   | Logistics, order tracking, inventory mobility     |


- **IP Addressing Plan**
  - Unique subnets assigned to each VLAN per outlet
  - Efficient IP usage across varying outlet sizes

- **Assumptions & Limitations**
  - One firewall used per site due to Cisco Packet Tracer limitations
  - SD-WAN simulated via VPN tunnel assumptions
  - PoE assumed for IP phones and cameras

---

## 🖥️ Packet Tracer Simulation

The project includes full simulation files that demonstrate:
- Inter-branch communication
- VLAN isolation and routing
- Firewall path verifications
- Scalable configurations per outlet type

---

## 👥 My Contributions

As part of the **segmentation planning**, I focused on:
- Designing and defining VLAN structures across outlets
- Mapping services to logical network segments
- Ensuring clear traffic isolation and security
- Coordinating with IP planning to align subnet allocations

---



