# 🔑 Secure Access: SSH Key Management

### **Standard Operating Procedure**
1. **Generation:** Utilizing `ed25519` encryption for the best balance of security and performance.
   * `ssh-keygen -t ed25519 -C "allen.varias@lab"`
2. **Distribution:** Using `ssh-copy-id` to push keys to new Proxmox VMs.
3. **Hardening:** Disabling `PasswordAuthentication` in `/etc/ssh/sshd_config` across the entire Home Lab.
