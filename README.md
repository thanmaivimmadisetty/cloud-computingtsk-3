# 🌩 Task 3 — Create and Configure a Virtual Private Cloud (VPC) with Subnets

## 🎯 Objective
To understand how secure networking works in cloud environments by creating a *Virtual Private Cloud (VPC)* with *public and private subnets*, enabling controlled internet access using route tables and an Internet Gateway.

---

## ✅ Deliverables
- 📌 Screenshot of *VPC + Subnets* page
- 📌 Screenshot of *Route Table configuration*
- 📌 Short description containing:
  - VPC CIDR
  - Subnet CIDRs
  - Region
  - Internet access status (enabled/disabled)

---

## 🛠 Tools Used
| Tool | Purpose |
|--------|---------|
| *AWS Free Tier* | VPC, Subnets, Routing & Internet Gateway |
| *EC2 (Optional for testing)* | To test public vs private connectivity |

---

## 🧭 Step-by-Step Guide

### *1️⃣ Create VPC*
1. Open AWS Console → Go to *VPC Dashboard*
2. Click *Create VPC*
3. Enter:
   - *Name:* intern-vpc
   - *IPv4 CIDR:* 10.0.0.0/16
