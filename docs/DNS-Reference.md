## 🌐DNS Resource Record Master Reference
As a Platform Engineer, maintaining DNS integrity is the foundation of service availability. Below are the standards I follow.

| Record | Name | Enterprise Purpose |
| :--- | :--- | :--- |
| **A** | Address | Maps hostname to **IPv4**. The base of all web services. |
| **AAAA** | IPv6 Address | Maps hostname to **IPv6**. Essential for dual-stack networks. |
| **CNAME** | Canonical Name | Creates aliases for load-balanced services. |
| **PTR** | Pointer | **Reverse DNS:** Crucial for security logs and mail verification. |
| **MX** | Mail Exchange | Directs email to the authoritative mail server. |
| **TXT** | Text | Generic storage for **SPF**, **DKIM**, and **DMARC** security. |
| **SRV** | Service Record | Locates specific services (LDAP, SIP, Active Directory). |
| **SOA** | Start of Authority| Contains primary zone info (Serial, Refresh, Admin Email). |
| **NS** | Name Server | Delegates a zone to authoritative servers (Infoblox Grid). |
| **CAA** | Cert Authority | Restricts which CAs can issue SSL certificates for the domain. |
| **DS / DNSKEY**| DNS Security | Used in **DNSSEC** to secure the chain of trust. |
