+++
title = "Projet Seral"
description = ""
type = ["posts","post"]
tags = [
    "homelab",
    "souverain",
    "securite",
]
date = "2023-04-12"
categories = [
    "adminsys",
]
series = ["Seral"]
[ author ]
  name = "Julien Mérieau"
+++

In Roman mythology, the Lares are domestic gods who protect the home and family. The name of this project, 'Seral,' is an anagram of Lares!

This project was conceived with the aim of having a connected apartment to make my life easier—turning on lights, having routines for sunrise or sunset, managing my appliances, and even my electricity consumption.

### Context
The problem of our digital age 🙃 is the overconnection of our devices to the internet. This exposes us to several problems:
- In case of internet loss, we lose control of our devices
- A third party can control our devices
- Personal data can be exfiltrated by certain devices (cameras, microphones, GPS, WiFi/Bluetooth environment, WiFi password, LIDAR on robotic vacuums...)
- Devices could be used to carry out attacks (notably DDoS)
- The vendor of the device can update it Over The Air (OTA) and add malicious code (likely in case of compromise or war with countries like China or the US)
- Devices can be entry points into the network or pivots to compromise more sensitive devices (router, computer...), many attacks are possible on the network

It’s all a matter of trust. Unfortunately, it is not uncommon to see personal data breaches following compromises or scandals about data collection.

Personally, I have no trust in companies selling non-open source connected devices. Hence, the existence of this project.

### Principles
- Privacy - No personal data should be shared with third parties.
- Security - Connected devices must be isolated.
- Ease of Use - No maintenance should be required and devices must be easily usable.

### Parts
- Network: Setting up a firewall and equipment to replace the router 🖊️
- WiFi: Deployment of multiple WiFi networks to isolate risky devices 🖊️
- Remote Access: Deployment of a VPN to access the network remotely 🖊️
- Server: Setting up a Proxmox server to manage home automation and have a homelab 🖊️
- Surveillance: Monitoring certain risky parts of the network ⌛
- Robot Vacuum: Reappropriation of a proprietary robot vacuum ⌛
- Camera: Reappropriation of a proprietary surveillance camera ⌛
- Assistant: Deployment of a voice assistant ⌛