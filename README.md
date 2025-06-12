# **Multi-Protocol Network Simulation with VLSM, NAT & ACLs**  

## **📌 Project Description**  
This project simulates a complex enterprise-grade network using **Cisco Packet Tracer**, integrating multiple routing protocols (**EIGRP, OSPF, RIP**) with route redistribution, **VLSM subnetting**, **DHCP**, **NAT**, and **ACLs** for secure traffic filtering. Designed for network engineering students and professionals, it demonstrates scalable network design, dynamic IP allocation, and controlled service access.  

---

## **✨ Key Features**  
✅ **Multi-Protocol Routing**:  
   - EIGRP (Blocks B & F), OSPF (Areas 1 & 2 in Blocks A & C), and RIP (Block E) with seamless redistribution.  
✅ **Optimized Subnetting**:  
   - **VLSM** for efficient IP allocation across 14+ subnets (Networks A–N).  
✅ **Centralized DHCP**:  
   - Dynamic IP assignment for hosts in EIGRP, OSPF, and RIP blocks via a server in Block D.  
✅ **Security & Access Control**:  
   - **NAT** on Router21 (Network K) & Router10 (Network F) for public IP translation.  
   - **ACLs** to restrict web server access (blocked: PC in Network A, laptop in E, smartphone in B, all hosts in D).  
✅ **FTP Server**:  
   - Configured in Network G with upload permissions restricted to authorized hosts.   

---

## **🛠️ Tech Stack**  
- **Simulation Tool**: Cisco Packet Tracer (Instructor Version)  
- **Protocols**: EIGRP, OSPF, RIP v2  
- **IP Management**: VLSM, DHCP  
- **Security**: NAT, ACLs  

---

## **🚀 Installation & Setup**  
1. **Clone the Repository** (if applicable):  
   ```bash  
   git clone [https://github.com/habib-here/Advanced-Network-Simulation-Integrating-EIGRP-OSPF-RIP-with-VLSM-NAT-ACLs.git]  
   ```  
2. **Open in Cisco Packet Tracer**:  
   - Download the `.pkt` file (i.e., `Advanced-Network-Simulation-Habib.pkt`).  
   - Launch Packet Tracer and open the file.  

---

## **📸 Usage & Demo**  
### **1. Network Topology**  
![topology](https://github.com/user-attachments/assets/8cf989a0-d984-429a-b9dc-75f00565675f) 
*Full network layout with color-coded blocks (A–N).*  

### **2. Routing Tables & Redistribution**  
![Routing Tables](https://github.com/user-attachments/assets/13dcb065-e9de-4394-aeec-bead89a0b772)
*Verified routes propagated across EIGRP, OSPF, and RIP.*  

### **3. DHCP & NAT Verification**  
![DHCP Pool](https://github.com/user-attachments/assets/2bc2ccdf-c58f-417d-8810-4e9b33ce6d12)
*Central DHCP server leases in Block D.*  

![NAT](https://github.com/user-attachments/assets/33c178fc-4f85-4cdb-a56d-f34437b3b3f5)

### **4. ACL Enforcement**
![ACL](https://github.com/user-attachments/assets/605311b9-7115-49f4-9930-d50bbb5eb977)
*Web server access denied for specified hosts.*  

### **5. FTP**
![FTP](https://github.com/user-attachments/assets/a15a6b65-3e43-41a0-a2d7-153847145cf3)
*FTP in action.*  

---

## **📜 License**  
This project is open-source under the [MIT License](LICENSE).  

---

## **🎯 Conclusion**  
A hands-on demonstration of **enterprise network design**, emphasizing protocol interoperability, efficient resource allocation, and security. Ideal for portfolios, interviews, or academic reference.  

**🔗 Connect**: [https://www.linkedin.com/in/habib-here/] | **📧 Contact**: [habibahmedmalik1@gmail.com]  

--- 
