# Enterprise Branch Routing and Networking - Cisco Packet Tracer
**Name:** Afreen Khan  
**Register Number:** 23BCAR0308         
**Course:** BCA (IoT Specialization), 4th Semester  
**Subject Code:** 23BCA4VC02 – Network Administration  
**College:** JAIN (Deemed-to-be University)  
**Submission Date:** 21st April 2025  
**Instructor:** Mr. Sahabzada Betab Badar  

---

## 🧩 Project Overview

This project simulates a **real-world enterprise-level network setup** for a three-floor office branch using **Cisco Packet Tracer**. The goal is to ensure efficient data flow, secure access, wireless coverage, and departmental segmentation across all floors. The setup is designed to reflect core principles of enterprise networking like **routing, VLANs, subnetting, inter-floor connectivity, DHCP**, and **redundant paths using OSPF**.

---

## 🏙️ Company Scenario

A fictional enterprise expanding its branch operations across a 3-floor building aims to integrate all departments under one unified and secure network. Each department is assigned its own **VLAN and subnet**, ensuring organized traffic flow and controlled access.

---

## 🖧 Network Highlights

- **Routing Protocol:** OSPF Area 0 (for dynamic routing and redundancy)  
- **Switching:** Multilayer switches for Inter-VLAN routing (SVIs used)  
- **IP Segmentation:** Proper VLANs and subnetting for department isolation  
- **Wireless Access:** Access Points for each department  
- **DHCP & DNS Services:** Located in Server Room for centralized management  
- **Security Measures:**  
  - SSH on routers and switches  
  - Port security on Layer 2 switches  
  - Banner messages and password encryption  

---

## 📶 Floor-wise Department Setup

### 🟩 First Floor
| Department          | VLAN | Network               |
|---------------------|------|------------------------|
| Sales & Marketing   | 10   | 172.16.1.0/25          |
| HR & Logistics      | 20   | 172.16.1.128/25        |

### 🟦 Second Floor
| Department          | VLAN | Network               |
|---------------------|------|------------------------|
| Finance & Accounts  | 30   | 172.16.2.0/25          |
| Admin & Public Rel. | 40   | 172.16.2.128/25        |

### 🟪 Third Floor
| Department          | VLAN | Network               |
|---------------------|------|------------------------|
| ICT Department      | 50   | 172.16.3.0/25          |
| Server Room         | 60   | 172.16.3.128/28        |

---

## 🖥️ Devices Used

### 🔁 Routers
- **CORE-R1 (Cisco 2911)**  
- **CORE-R2 (Cisco 2911)**  
- Connected to **ISP1-MAIN** and **ISP2-BACKUP** via public IP links (195.136.x.x)

### 🔀 Layer-3 Switches (Multilayer)
- 2 Multilayer Switches for VLAN routing on each floor:  
  - `3550-24PS` Multilayer1  
  - `3550-24PS` Multilayer2  

### 📶 Layer-2 Switches (2960 Series)
- 6 total L2 switches for individual departments  

### 💻 End Devices
- PCs, Laptops, Tablets, Printers (each VLAN has its own set)  
- Wireless Access Points for BYOD connectivity  

### 🧮 Servers
- **DHCP Server** – Dynamic IP allocation  
- **DNS Server** – Domain name resolution  
- **Email Server** – Internal communication  
- **SysAdmin PC** – Server management  

---

## 🌐 IP & Connectivity Design

- **OSPF** ensures inter-router communication and automatic route updates  
- **VLANs** maintain logical separation of departments  
- **Access Points** enable seamless Wi-Fi on each floor  
- **Servers** use static IPs from VLAN 60  
- **Subnetting** done efficiently for optimized IP usage  

---

## 🔐 Security Setup

- Enabled **SSH** on all routers and Layer-3 switches  
- Used **Sticky MAC** to bind MAC addresses to specific ports  
- **Password protection** on console and VTY lines  
- Disabled **IP domain lookup** to prevent unwanted delays  

---

## 🎯 Key Learnings

- Understood **enterprise-grade network architecture**  
- Gained practical skills in:  
  - **Configuring VLANs**  
  - **Routing with OSPF**  
  - **Static and Dynamic IP addressing**  
  - **Port security and wireless configuration**  
- Learned how to **simulate, troubleshoot, and optimize** a multi-floor network setup  

---

## 🧾 Notes & Tools

- **Simulation Tool:** Cisco Packet Tracer  
- **OS Used:** Windows 11  
- **PC Model:** Dell Inspiron 2-in-1 i3  

---

## 📌 Project Map (Image)

![Enterprise Branch Network Map](https://github.com/Afreen-khan2605/Enterprise_Branch_Routing_and_Networking/blob/a5117473a0079984b51445605ed0d579d8ecb0f3/NA%20Enterprise%20Activity%202%20Project.png)

---

## 🔗 References

- Personal experience and Cisco Packet Tracer Documentation   
- [Case Study Reference](https://gurutechnetworks.otombenard.com/assetsProject/project6) for inspiration  

---
© 2025 – Afreen Khan | JAIN (Deemed-to-be University)

