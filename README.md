# 🔒 Zero Trust SOC Network Architecture - Lab Project

[![Network Simulation](https://img.shields.io/badge/Simulation-Cisco%20Packet%20Tracer-blue.svg)](https://www.netacad.com/courses/packet-tracer)
[![Security Framework](https://img.shields.io/badge/Security-Zero%20Trust%20Architecture-red.svg)](https://csrc.nist.gov/publications/detail/sp/800-207/final)
[![Documentation](https://img.shields.io/badge/Documentation-Structured%20Report-green.svg)](Zero_Trust_SOC_Structured.docx)

A comprehensive Computer Networking & Cyber Security Lab Project implementing a **Zero Trust Security Operations Center (SOC)** network topology. This project includes a complete **Cisco Packet Tracer simulation environment** and an in-depth **technical architecture document**.

---

## 📌 Project Overview

Traditional perimeter-based network security assumes everything inside an organization's network is trusted. The **Zero Trust Architecture (ZTA)** operates on the strict principle: **"Never Trust, Always Verify."**

This project designs and simulates an enterprise-grade Zero Trust Security Operations Center (SOC) framework to mitigate lateral movement, prevent unauthorized access, and continuously inspect network traffic.

---

## 📁 Repository Structure

```
Lab Project/
├── Lab Project.pkt                # Cisco Packet Tracer network simulation file
├── Zero_Trust_SOC_Structured.docx # Full technical documentation & architecture report
├── .gitignore                     # Repository ignore rules
└── README.md                      # Project documentation overview
```

---

## 🎯 Key Features & Architectural Highlights

1. **Micro-Segmentation & VLAN Isolation**:
   - Division of enterprise network into strict security zones (DMZ, Internal SOC, Server Farm, Management VLAN).
   - Access Control Lists (ACLs) enforcing minimal communication paths between segments.

2. **Zero Trust Access Control**:
   - Strict identity-based verification prior to resource access.
   - Elimination of implicit trust based on physical or IP network location.

3. **SOC Monitoring & Incident Response**:
   - Implementation of centralized log management and SIEM integration topology.
   - Continuous traffic analysis and active intrusion detection/prevention.

4. **Redundant & Secure Infrastructure**:
   - High availability router and switch configurations.
   - Encrypted administration channels (SSH, HTTPS) across management interfaces.

---

## 🚀 How to Run the Simulation

1. **Prerequisites**:
   - Download and install **Cisco Packet Tracer** (v8.0+ recommended).
   - Microsoft Word or compatible viewer for reading `Zero_Trust_SOC_Structured.docx`.

2. **Opening the Lab Topology**:
   - Open Cisco Packet Tracer.
   - Navigate to `File -> Open` and select `Lab Project.pkt`.
   - Explore switch/router configurations, VLAN assignments, ACL policies, and test connectivity across security boundaries.

---

## 👥 Authors & Credits

This project was designed and co-authored by:

- **Eman Fatima**  
  📧 Email: [emanmubashir2005@gmail.com](mailto:emanmubashir2005@gmail.com)  
  🌐 GitHub: [@eman2005fatima](https://github.com/eman2005fatima)

- **Anusha Zaman**  
  🤝 Project Co-Author & Collaborator

---

## 📄 License

This project is created for educational and academic computer networking demonstration purposes.
