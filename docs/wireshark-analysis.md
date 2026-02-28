# 🦈 Network Analysis with Wireshark

### **Use Case**
I utilize Wireshark for deep packet inspection (DPI) to troubleshoot complex networking issues that simple 'ping' or 'traceroute' commands cannot resolve, specifically in **Infoblox DNS** and **VPN** environments.

### **Common Workflows**
1. **DNS Troubleshooting:** Filtering for `dns` or `udp.port == 53` to identify malformed packets or latency in recursive lookups.
2. **Handshake Analysis:** Analyzing TCP 3-way handshakes (`tcp.flags.syn == 1`) to find firewall drops.
3. **Security Auditing:** Detecting unencrypted traffic (Telnet/HTTP) in production environments.

### **Pro-Tip Filters used:**
* `ip.addr == 10.5.0.10`: Filters traffic for a specific Proxmox VM.
* `http.response.code == 404`: Identifies broken web service links.
* `tcp.analysis.retransmission`: Detects packet loss and network congestion.
