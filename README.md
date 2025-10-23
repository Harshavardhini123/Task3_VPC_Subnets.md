# Task3_VPC_Subnets.md
# Task 3: Create and Configure a Virtual Private Cloud (VPC) with Subnets

## Objective
To learn how cloud networking works by creating a Virtual Private Cloud (VPC) with public and private subnets, and enabling controlled internet access.

---

## Deliverables

- Screenshot of VPC dashboard showing subnets
- Screenshot of route table configuration
- Short description: CIDR range, number of subnets, region, and whether internet access is enabled

---

## VPC and Subnet Details (as per task)

- **VPC CIDR block:** 10.0.0.0/16  
- **Public Subnet CIDR:** 10.0.1.0/24 (auto-assign public IP enabled)  
- **Private Subnet CIDR:** 10.0.2.0/24 (auto-assign public IP disabled)  
- **Internet Gateway attached:** Yes, for public subnet  
- **Public Route Table:** 0.0.0.0/0 → IGW  
- **Private Route Table:** No internet access  

---

### Screenshots
1. VPC dashboard showing Public and Private subnets  
2. Public route table showing route 0.0.0.0/0 → IGW  
3. Private route table showing no internet route  

---

### Short Description (exact wording from task)
VPC name  
CIDR range: 10.0.0.0/16  
Number of subnets: 2 (Public: 10.0.1.0/24, Private: 10.0.2.0/24)  
Region: (your chosen region)  
Internet access enabled: Yes for public subnet, No for private subnet
