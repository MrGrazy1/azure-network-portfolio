# 🧪 Lab 1 – Azure VNet + Subnet + NSG
This lab demonstrates foundational Azure networking by deploying a Virtual Network, subnet, and Network Security Group, then testing traffic rules.

## ✅ What I Built
- Created a **Virtual Network** (`10.0.0.0/16`)
- Added a **Subnet** (`10.0.1.0/24`)
- Created and attached a **Network Security Group (NSG)**
- Added a **Deny Inbound** rule (practice with priorities)

---

## 🧠 Concepts Learned
- Azure **Resource Group** structure
- **VNet & subnet design** (CIDR, /16 → /24)
- **NSG rule priority** (lower number = higher priority)
- Default **inbound/outbound** behavior in NSGs

---

## 🗺️ Topology (text)
Resource Group: RG-Lab1
└── VNET-Lab1 (10.0.0.0/16)
    └── Subnet-FrontEnd (10.0.1.0/24)
        └── NSG-FrontEnd (custom deny inbound rule)


---

## ✅ Verification Screenshots
**Subnet with NSG Attached**  
![Subnet Screenshot](./Lab1-Subnet.png)

**NSG Inbound Rules**  
![NSG Rules Screenshot](./Lab1-NSGRules.png)

---
