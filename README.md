# Automated Windows Infrastructure & Identity Management

## 📌 Project Overview
This project demonstrates the deployment and management of a centralized IT infrastructure using **Windows Server 2022** and **Windows 10 Pro**. The goal was to build a secure, scalable, and automated environment for managing users and system policies.

## 🛠 Tech Stack
* **Virtualization:** VMware Workstation
* **Server OS:** Windows Server 2022 (Domain Controller)
* **Client OS:** Windows 10 Pro
* **Networking:** Private Virtual Network (Host-only)
* **Automation:** PowerShell Scripting

## 🚀 Key Features

### 1. Infrastructure Setup
- Configured a private virtual network to simulate a corporate environment.
- Promoted Windows Server to a **Domain Controller (DC)** for the `Masr.com` domain.
- Successfully joined Windows 10 client to the domain.
  

### 2. Centralized Security (Group Policy)
- Implemented **Group Policy Objects (GPOs)** to enforce security restrictions.
- **Example:** Disabled Control Panel access for standard employees to prevent unauthorized system changes.


### 3. Automation with PowerShell
- Developed a PowerShell script to automate **Bulk User Creation**.
- Instead of manual entry, the script reads user data and provisions accounts in a specific **Organizational Unit (OU)** within seconds.


## 📂 Project Structure
- `scripts/`: Contains the PowerShell automation script.
- `documentation/`: Step-by-step screenshots of the setup.

## 🏁 Final Result
All automated users were successfully created and were able to log in to the domain-joined client machine with restricted access as per the company policy.


---
👨‍💻 **Developed by:** [Abdallah Samir]
🔗 **Connect with me on LinkedIn:** [www.linkedin.com/in/abdallah-samiir]
