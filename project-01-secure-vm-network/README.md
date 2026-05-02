# 🚀 Project 01: Secure Azure VM Network

## 📌 Overview
This project demonstrates how to deploy and secure a Microsoft Azure Virtual Machine using core networking and security services.

The goal was to simulate a real-world cloud environment by implementing:
- Network isolation
- Controlled access
- Secure connectivity

---

## 🛠️ Services Used
- Azure Virtual Machine (Windows Server 2022)
- Virtual Network (VNet)
- Subnet
- Network Security Group (NSG)
- Azure Storage Account

---

## 🏗️ Architecture Diagram
![Architecture](diagrams/architecture-diagram.png)

---

## ⚙️ Deployment Steps

### 1. Environment Initialization
![Sandbox](screenshots/01-sandbox-start.png)

---

### 2. Resource Group Setup
![RG List](screenshots/02-resource-groups-list.png)
![RG Overview](screenshots/03-resource-group-overview.png)

---

### 3. Virtual Network & Subnet Configuration
![VNet](screenshots/04-vnet-create-settings.png)
![Subnet](screenshots/05-vnet-subnet.png)

---

### 4. Network Security Group (NSG)
Configured inbound rules to allow secure RDP access only.

![NSG Overview](screenshots/06-nsg-overview.png)
![NSG Rules](screenshots/07-nsg-inbound-rules.png)

---

### 5. Virtual Machine Deployment
![VM Settings](screenshots/08-vm-create-settings.png)
![VM Networking](screenshots/09-vm-networking.png)

---

### 6. VM Validation & Connectivity
![VM Overview](screenshots/10-vm-overview-1.png)
![VM Overview 2](screenshots/11-vm-overview-2.png)

---

### 7. Storage Account Configuration
![Storage](screenshots/12-storage-account.png)

---

## 🔐 Security Implementation
- Restricted RDP (Port 3389) to specific IP
- Applied Network Security Group rules
- Isolated VM within subnet
- Controlled inbound traffic

---

## 📚 What I Learned
- How Azure networking components work together (VNet, Subnets, NSGs)
- How to securely expose a VM to the internet
- How to troubleshoot VM deployment and connectivity
- How to structure real-world cloud environments

---

## 🎯 Outcome
Successfully deployed a secure Azure VM environment with controlled access and documented the full process for reproducibility.

---

## 📌 Next Improvements
- Implement Azure Bastion (remove public RDP exposure)
- Add Azure Monitor for logging
- Automate deployment using ARM/Bicep templates
