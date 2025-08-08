# 🔐 Cisco Packet Tracer – Secure Network Design & Configuration

## 📌 Project Overview
This project demonstrates the design and configuration of a secure, multi-network topology in **Cisco Packet Tracer**.  
It implements **secure routing, time synchronization, remote management, port security, and ACL-based access control**.

<img width="1215" height="686" alt="image" src="https://github.com/user-attachments/assets/91887197-6dd6-4bfb-ac8c-9524bd7aacb1" />


---

## 🎯 Objectives & Tasks

### 1️⃣ Topology Design 
- Replicated the provided network diagram in Cisco Packet Tracer.
- Labeled all devices and network segments appropriately.

### 2️⃣ IP Addressing
- Assigned **first usable IP addresses** to all router interfaces.

### 3️⃣ Secure OSPFv2 Routing 
- Enabled **OSPFv2** on all routers.
- Verified end-to-end communication by sending PING requests from **Network A’s PC** to all other devices.
- **Evidence:** Screenshots of successful pings.

### 4️⃣ NTP Server Configuration 
- Configured a **secure NTP server**.
- Synchronized all network devices to the same time source.
- **Evidence:** Screenshots of the synchronized time on all devices.

### 5️⃣ Secure Remote Management 
- Enabled **TACACS+ server authentication** for remote device management.

### 6️⃣ Port Security 
**Switch 2 & Switch 3**
- Allowed **two dynamically learned MAC addresses** per port.
- Violation action: **Restrict** port access.

**Switch 1**
- Statically assigned **server and admin PC MAC addresses** to ports.
- Violation action: **Shutdown** the port.

### 7️⃣ ACL Restrictions – Web Server Access
- Networks **A, B, D, and E** can only access the **web server**.
- Denied all other traffic to/from these networks.

### 8️⃣ ACL Restrictions – Isolated Communication 
- Networks **C and F** can communicate **only with each other**.
- Blocked all communication with any other networks.

---

## 🛠 Technologies & Protocols Used
- **Cisco Packet Tracer**
- **OSPFv2**
- **NTP (Network Time Protocol)**
- **TACACS+ Authentication**
- **Port Security**
- **Access Control Lists (ACLs)**

---

## 📷 Evidence
The project includes:
- Network topology diagram
- Screenshots of:
  - Successful pings between devices
    
    <img width="534" height="407" alt="image" src="https://github.com/user-attachments/assets/cc386ae9-514d-4ce6-a5e8-271342775a6e" />

  - NTP time synchronization
    
    <img width="352" height="98" alt="image" src="https://github.com/user-attachments/assets/74b55837-8aea-41cf-bbf4-07868378fffa" />

  - TACACS+ authentication
    
    <img width="597" height="295" alt="image" src="https://github.com/user-attachments/assets/d3a96995-1fc1-497f-b8b3-9330fe6bb78f" />

  - Port security violation tests
  - ACL functionality verification

---

## 🚀 How to Use
1. Open the `.pkt` file in **Cisco Packet Tracer**.
2. Verify device configurations.
3. Test connectivity using **ping** and **web browser**.
4. Review ACL and port security behavior.

---

## 📄 Author
**Chiraji Dilipun**  
Final Year Student – Network & Security Technologies  
South Eastern University of Sri Lanka

---
