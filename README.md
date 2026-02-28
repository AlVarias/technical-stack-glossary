# 🛠️ Enterprise Technical Stack Glossary
### **Systems Engineering | Infrastructure-as-Code | Cloud Orchestration**

This repository is a comprehensive technical glossary of the enterprise tools, platforms, and methodologies I have mastered across my career at **Systemethix**, **SMS Global Technologies**, and **Antlabs**. 

Each category below represents a core pillar of my "Platform Engineering" philosophy: **Automation, Scalability, and Observability.**

---

## 🏗️  Cloud & Virtualization
Managing the modern data center from the hypervisor to the hybrid cloud.
* **[VMware vSphere](./VMWARE.md):** vCenter, ESXi, and CCL Rivera Cloud administration.
* **[Red Hat OpenStack](./REDHAT.md):** Private cloud compute (Nova), storage (Cinder), and networking (Neutron).
* **[Red Hat OpenShift](./REDHAT.md):** Enterprise Kubernetes (KVM/LXC) for containerized workloads.
* **[Proxmox VE](./PROXMOX.md):** Open-source virtualization and ZFS storage management for lab environments.



---

## ⚙️ Automation & Infrastructure-as-Code (IaC)
Treating hardware and software configurations as version-controlled code.
* **[Ansible & Red Hat Tower](./REDHAT.md):** Enterprise automation, playbook development, and RBAC-controlled job execution.
* **[Terraform](./TERRAFORM.md):** Declarative infrastructure provisioning for virtualized environments.
* **[Linux Shell Scripting](./LINUX_ADMIN.md):** Bash/Sh scripting for system health checks and task automation.
* **[Zapier](./ZAPIER.md):** Low-code workflow orchestration for cross-platform tool integration.



---

## 🌐 Networking & DDI (Telecommunications Grade)
Ensuring 100% uptime for core network services and traffic flow.
* **[Infoblox DDI](./INFOBLOX.md):** Expert DNS/DHCP/IPAM management. Specialized in **IMS**, **APN**, and caching.
* **[F5 Networks](./F5_NETWORKS.md):** Load Balancing (LTM) and Application Delivery Controllers (ADC).
* **[Harmony](./HARMONY.md):** Data compression and network bandwidth optimization.
* [Cisco Systems](./CISCO.md) - Enterprise Backbone
* [Mikrotik](./MIKROTIK.md) - RouterOS & ISP Routing
* [Ruckus Wireless](./RUCKUS.md) - High-Density WLAN
* [Ubiquiti](./UBIQUITI.md) - UniFi & EdgeMAX Ecosystem
* [Ransnet](./RANSNET.md) - SD-Gateway & Hotspot
* [Altai Technologies](./ALTAI_TECHNOLOGIES.md) - Super WiFi Outdoor
* [SMB Solutions (D-Link/Linksys/TP-Link)](./D-LINK_LINKSYS_TPLINK.md)


---

## 🛡️  Operating Systems & Security
Hardening and maintaining stable, secure environments.
* **[Red Hat Enterprise Linux (RHEL)](./REDHAT_ENTERPRISE_LINUX.md):** Security-first OS administration (SELinux, Firewalld).
* **[Ubuntu & CentOS](./LINUX_ADMIN.md):** Managing community-driven and cloud-native Linux distributions.
* **[Windows Server](./WINDOWS_SYSTEMS.md):** Administration of Server 2008, 2012, and 2016 environments.
* **[Fortinet](./FORTINET.md):** Network security association and firewall management.

---

## 🗄️  Data & Storage Management
High-performance scaling and long-term data archival.
* **[IBM Storage Scale](./IBM.md):** Managing GPFS parallel file systems for global data sets.
* **[IBM Tape Storage](./IBM.md):** Secure, long-term data retention and archival systems.
* **[Databases](./DATABASES.md):** Administration of **MS SQL Server**, **MariaDB**, and **MySQL**.

---

## 🎫  ITSM & Professional Services
Governance and service delivery in high-SLA environments.
* **[ServiceNow](./SERVICENOW.md):** Enterprise Incident, Change, and Problem management.
* **[Autotask & Cherwell](./AUTOTASK.md):** PSA and Service Desk management for Managed Service Providers (MSP).
* **[Wireshark](./WIRESHARK.md):** Deep-packet inspection for Root Cause Analysis (RCA).

---

## 🗄️ Database Management Systems (DBMS)
* [Microsoft SQL Server](./MS_SQL_SERVER.md) - Enterprise Windows Environments
* [MariaDB](./MARIADB.md) - High-Performance Open Source
* [MySQL](./MYSQL.md) - Web & Cloud Application Data

## 📐 Infrastructure Design & Physical Security
* [Microsoft Visio](./MICROSOFT_VISIO.md) - Topology & Rack Design
* [CCTV & IP Camera Systems](./CCTV_IP_CAMERA.md) - Surveillance Infrastructure
* [Physical Access Controls](./ACCESS_CONTROLS.md) - Perimeter & Data Center Security

* # 🏢 Data Center & Physical Infrastructure Portfolio
### **Systems Engineering | Layer 1 Operations | Critical Facilities**

This repository documents my hands-on experience in the "Physical Stack" of enterprise IT. A resilient cloud environment is only as stable as the power, cooling, and cabling that support it. This guide outlines my professional standards for **Datacenter Operations**, **Thermal Management**, and **Business Continuity**.

---

## 🏗️ Rack & Stack Operations
Professional deployment of enterprise hardware with a focus on weight distribution and airflow optimization.
* **Hardware Commissioning:** Physical installation of 1U-4U servers (Dell PowerEdge, HP ProLiant, IBM System x).
* **Asset Mapping:** Utilizing **Microsoft Visio** to create 1:1 rack elevations and RU (Rack Unit) placement guides.
* **Labeling Standards:** Implementing unique Asset IDs on both front and rear chassis for rapid identification.



---

## 🧶 Structured Cabling (TIA/EIA-606)
High-performance network and power distribution using industry-standard cable hygiene and color-coding.
* **Data Cabling:** Professional routing of **Cat6a Copper** and **OM4 Fiber Optic** links.
* **Color-Coding Standard:** Using standardized colors (e.g., Blue for Data, Red/Black for A+B Power) for instant troubleshooting.
* **Source-to-Destination Labeling:** Wrap-around labels at both ends of every cable (e.g., `SW01-P15 / SRV02-NIC1`).
* **Cable Management:** Utilizing Velcro ties and vertical managers to maintain "Clean Aisle" standards and prevent airflow obstruction.



---

## ⚡ Critical Power & Business Continuity
Ensuring 100% uptime through redundant power paths and backup generation.
* **UPS Systems:** Monitoring battery health, load balancing, and bypass modes for Uninterruptible Power Supplies.
* **Genset (Generator) Operations:** Overseeing Diesel Generator readiness, including ATS (Automatic Transfer Switch) testing and "Full-Load" transfers.
* **Redundancy (2N / N+1):** Configuring dual-feed PDUs (Power Distribution Units) to eliminate single points of failure.



---

## ❄️ Environmental & Thermal Management (HVAC)
Precision cooling and airflow engineering to prevent hardware failure and thermal throttling.
* **CRAC/HVAC Management:** Monitoring Computer Room Air Conditioning units to maintain optimal temperature (18°C–22°C).
* **Aisle Containment:** Implementing **Hot/Cold Aisle** strategies and using blanking panels to prevent air recirculation.
* **Environmental Alerting:** Deploying IP-based sensors for real-time temperature and humidity monitoring integrated into **ServiceNow**.



---

## 🛡️ Physical Security & Integration
* **CCTV & IP Surveillance:** Deployment of POE-based security cameras and NVR recording systems.
* **Access Control:** Installation of biometric and RFID-based entry systems for data hall security.
* **System Integration:** Bridging physical security hardware with the core IT network.

---


## 👨‍💻 About the Author
I am a **Systems Engineer** based in **Auckland, NZ**, with a focus on bridging the gap between traditional hardware and modern cloud automation. My career is built on the belief that if a task is done twice, it should be automated.

**Connect with me:**
* [LinkedIn](https://www.linkedin.com/in/allen-albert-varias/)
* [Personal Portfolio](https://your-google-site-link.com) ## under construction

---

To finalize your Data Center & Physical Infrastructure repository, here is the complete, high-impact README.md file.

This is designed to showcase your "hands-on" expertise to New Zealand employers like Systemethix, emphasizing that you understand the critical relationship between hardware, power, and cooling.

