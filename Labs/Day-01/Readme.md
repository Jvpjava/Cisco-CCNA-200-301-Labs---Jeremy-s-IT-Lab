<p align="center">
  <img src="cover.png" alt="Cisco Labs Banner" width="100%">
</p>

<div align="center">

# 🛠️ Lab: Topology Reconstruction & Device Placement
**CCNA 200-301 | Day-02 Lab**

[![Packet Tracer](https://img.shields.io/badge/Simulator-Cisco%20Packet%20Tracer-blue.svg)](#)
[![Status](https://img.shields.io/badge/Task-Completed-green.svg)](#)
[![Hardware](https://img.shields.io/badge/Hardware-ISR%202911%20%7C%20ASA%205505-orange.svg)](#)

</div>

---

## 📝 Overview
This lab focuses on the initial setup and physical cabling of a multi-branch network using **Cisco Packet Tracer**. The objective is to recreate a complex architectural diagram consisting of a **New York Branch**, a **Tokyo Branch**, and a simulated **Internet (ISP)** core, incorporating security appliances and various end-host devices.

---

## 🌐 Network Architecture

The topology is logically divided into three primary segments to simulate a real-world enterprise environment:

<h1 align="center">Cisco Labs</h1>
<p align="center">
  <img src="img/Screenshot 2026-04-03 154313.png" alt="Cisco Labs Cover" width="100%">
</p>


### 🏙️ New York Branch (Left)
*   **End Devices:** 2 PCs (`PC1`, `PC2`)
*   **Access Layer:** 1 Cisco Catalyst 2960 Switch (`SW1`)
*   **Edge:** 1 Cisco ISR 2911 Router (`R1`) and 1 Cisco ASA 5505 Firewall (`FW1`)

### ☁️ The Internet (Center)
*   **ISP Core:** Represented by a Cisco 2911 Router.
*   **Security Context:** 1 Attacker Laptop connected directly to the Internet simulation to test future security policies.

### 🗾 Tokyo Branch (Right)
*   **End Devices:** 2 Servers (`SRV1`, `SRV2`)
*   **Access Layer:** 1 Cisco Catalyst 2960 Switch (`SW2`)
*   **Edge:** 1 Cisco ISR 2911 Router (`R2`) and 1 Cisco ASA 5505 Firewall (`FW2`)

> [!IMPORTANT]
> **Firewall Placement Logic:** This lab demonstrates design flexibility. In the **NY Branch**, the firewall sits between the Router and the Internet. In the **Tokyo Branch**, the firewall is positioned between the Router and the Internal Switch.

---

## 🛠️ Hardware Specifications

| Device Type | Model | Role in Network |
| :--- | :--- | :--- |
| **Router** | Cisco ISR 2911 | Inter-branch routing and ISP simulation. |
| **Switch** | Catalyst 2960 | Layer 2 access for PCs and Servers. |
| **Firewall** | ASA 5505 | Adaptive Security Appliance for traffic filtering. |

---

## 🚀 Lab Implementation Steps

<p align="center">
  <img src="img/Screenshot 2026-04-03 154832.png" alt="Cisco Labs Cover" width="100%">
</p>


### 1. Device Placement
Selected specific hardware models from the **Network Devices** and **End Devices** menus to ensure alignment with CCNA curriculum standards.

### 2. Logical Labeling
All devices were renamed within the Packet Tracer workspace to match the lecture diagram (e.g., `R1`, `FW2`, `SRV1`). This ensures configuration accuracy in later labs.

### 3. Rapid Cabling
*   Used the **Automatically Choose Connection Type** tool.
*   **Power-User Tip:** Held `Ctrl` while selecting the tool to maintain an active cursor, allowing for rapid deployment of all physical links without returning to the menu.

---

## 💡 Key Takeaways
*   **Iconography Mastery:** Developed familiarity with Cisco-specific symbols for ISR routers and ASA firewalls.
*   **Topology Design:** Gained insight into where security appliances (ASA) are typically positioned at the network edge.
*   **Preparation:** This environment serves as the foundation for future "Life of a Packet" demonstrations involving encapsulation and de-encapsulation.

---

<div align="center">
  <sub>Completed as part of Jeremy's IT Lab CCNA 200-301 Course.</sub>
</div>
