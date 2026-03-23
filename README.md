![DNS](https://github.com/user-attachments/assets/2a4853a2-65cb-4a3f-8355-cf83b066d8ee)






# DNS Configuration & Name Resolution Analysis in a Windows Server Environment

---

##  🔹Project Summary
#### This project demonstrates hands on configuration and analysis of Domain Name System (DNS) services within a Windows Server environment. 
#### Key tasks included creating and managing DNS records, analyzing name resolution behavior between client and server systems, and understanding how local DNS servers interact with external DNS infrastructure. 
- ### Technology and Tools:
  - Windows Server 2022 DNS Server
  - Windows 10 Client
  - Microsoft Azure (Virtual Machine Hosting)
  - DNS manager
  - PowerShell (nslookup, ipconfig) 
  - Active Directory integrated DNS
#### This project reflects real world networking responisibilities related to name resolution, service accessibility, and basic network troubleshooting.
---

## 🔹Objectives
- Configure and manage DNS records (A Records, CNAME Records)
- Analyze client side DNS behavior
- Observe DNS functionality and propagation effects
- Understand how local DNS servers resolve external domain queries
- Strengthen foundational networking and troubleshooting skills
---

## 🔹Environment Setup
- DNS Server: Windows Server 2022 (dc-1)
- Client Machine: Windows 10
- Domain: isabelsdomain.com
- DNS Type: Active Directory Integrated DNS
  #### Tools Used within environment:
  - PowerShell:
  - ping
  - nslookup
  - ipconfig
  - ipconfig /displaydns
  - ipconfig /flushdns
- DNS Manager
#### This environment simulates an internal network where the domain controller also functions as the DNS server.
---

## 🔹Demonstration

---

## 🔹Key Takeaways
- DNS translates human readable domain names into IP addresses required for network communication
- A Records and CNAME Records serve different roles in name resolution and rescource mapping
- DNS caching improves performance but can temporarily mask changes
- Local DNS servers rely on root hints and external servers for internet resolution
- Understanding DNS behavior is critical for diagnosing connectivity and access issues
---

## Screenshots

---

