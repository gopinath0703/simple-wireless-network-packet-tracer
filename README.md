# Simple Wireless Network - Cisco Packet Tracer

## 📋 Project Overview
A basic wireless network setup demonstrating both wired and 
wireless device connectivity through a single wireless router.

## 🖥️ Topology
- 1 Wireless Router (300N series)
- 1 PC (wired connection via Fa0)
- 2 Laptops (wireless connection via Wireless port)

## 🌐 IP Addressing

| Device | Connection Type | IP Address |
|--------|-----------------|------------|
| PC0 | Wired (Fa0) | 192.168.0.104 |
| admin (Laptop) | Wireless | 192.168.0.100 |
| student (Laptop) | Wireless | 192.168.0.102 |

## ⚙️ Configuration Highlights
- Configured wireless router with SSID for laptop connectivity
- Assigned static IP addresses to all end devices
- Verified same-subnet communication between wired and 
  wireless devices

## ✅ Verification
- 100% successful ICMP ping between all devices:
  - admin ↔ PC0
  - student ↔ PC0
  - student ↔ admin

## 🛠️ Tools Used
Cisco Packet Tracer 8.2.2

## 📁 Files
- `simple wireless network.pkt` - Packet Tracer project file
- `screenshots/` - Topology and ping verification screenshots
