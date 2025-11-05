# 🖥️ Virtual Network Configuration – Windows Server & Client Simulation

A system administration project completed as part of **CNT 4603: System Administration** at the **University of Central Florida**.  
This project demonstrates virtualization, network configuration, and system management using **Windows Server 2022** and **Windows 10** virtual machines.

---

## 📖 Overview
The goal of this project was to install and configure a small virtual network named `SAVN.local` consisting of:
- Two **Windows Server 2022** machines (Domain Controller & File Server)
- One **Windows 10 Education** client machine

All machines were built and configured using **Oracle VirtualBox**, employing **static IP addressing**, **internal networking**, and basic connectivity testing using `ping` and `ipconfig`.

---

## ⚙️ Network Configuration

| Machine | Role | OS | IP Address | Function |
|----------|------|----|-------------|-----------|
| `MJL-SU24-S22-1` | Domain Controller | Windows Server 2022 | 192.168.0.101 | DNS + AD DS Host |
| `MJL-SU24-S22-2` | File Server | Windows Server 2022 | 192.168.0.102 | Application & File Storage |
| `MJL-SU24-W10-1` | Client | Windows 10 Education | 192.168.0.103 | Desktop Client |

All machines were configured on an **internal network** in VirtualBox, using static IPs and a shared virtual switch.

---

## 🧩 Key Steps
1. Installed and configured **Windows Server 2022** and **Windows 10** OS images.
2. Set up **internal networking** for all VMs in Oracle VirtualBox.
3. Assigned **static IP addresses** to each system.
4. Verified configuration using:
   - `ipconfig /all`
   - `ping` connectivity tests between all systems.
5. Captured deliverable screenshots of all configurations and successful communications.

---

## 🧾 Deliverables
| Screenshot | Description |
|-------------|--------------|
| Server1_ipconfig | IP Configuration for Domain Controller |
| Server2_ipconfig | IP Configuration for File Server |
| Client_ipconfig | IP Configuration for Windows 10 Client |
| Server1_ping | Connectivity tests from Server 1 |
| Server2_ping | Connectivity tests from Server 2 |
| Client_ping | Connectivity tests from Client |
| Server1_OS | Installed OS verification – Server 1 |
| Server2_OS | Installed OS verification – Server 2 |
| Client_OS | Installed OS verification – Windows 10 Client |

---

## 🧠 Learning Outcomes
- Gained hands-on experience configuring **Windows Server roles**  
- Practiced **Active Directory**, **DNS**, and **file server management**  
- Implemented **virtual internal networking** using VirtualBox  
- Applied **IP addressing, subnetting, and DNS configuration**  
- Strengthened troubleshooting and testing with `ping` and `ipconfig`

---

## 🧰 Tools & Technologies
- **Windows Server 2022**
- **Windows 10 Education**
- **Oracle VirtualBox**
- **CMD / PowerShell**
- **Active Directory & DNS Services**

---

## 👨‍💻 Author
**Sadman Nahin**  
📧 your.email@example.com  
🔗 [GitHub](https://github.com/Sadmannahin2000) | [LinkedIn](https://linkedin.com/in/your-link)
