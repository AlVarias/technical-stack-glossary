# 🐧 Linux Administration & Operations Cheat Sheet 

A comprehensive command reference for **Systems Engineering**, **Network Troubleshooting**, and **Infrastructure Management**. This guide covers the essential toolset for managing RHEL and Debian-based environments.

---

## 📂 1. File & Directory Management
| Command | Description |
| :--- | :--- |
| `pwd` | Print Working Directory (Where am I?). |
| `ls -l` | List files with long-format details (permissions, owner, size). |
| `cd` | Change directory. |
| `mkdir` / `rmdir` | Create a directory / Remove an empty directory. |
| `touch` | Create an empty file or update timestamps. |
| `cp` / `mv` | Copy / Move or Rename files and directories. |
| `rm -r` | Remove a directory and its contents recursively. |
| `ln -s` | Create a symbolic link (shortcut) to a file. |
| `shred` | Securely overwrite a file to prevent data recovery. |
| `clear` | Clear the terminal screen. |

## ⚙️ 2. System Information & Performance
| Command | Description |
| :--- | :--- |
| `uname -a` | Print all system information (Kernel, Architecture, Hostname). |
| `neofetch` | Display a visual summary of system specs. |
| `free -m` | Check free and used memory (RAM) in MB. |
| `df -H` | Display disk space usage in human-readable format. |
| `ps -aux` | View a snapshot of all currently running processes. |
| `top` / `htop` | Interactive real-time process monitoring. |
| `kill` / `pkill` | Terminate a process by ID or by name. |
| `cal` | Display a simple calendar in the terminal. |

## 🌐 3. Networking & Troubleshooting
| Command | Description |
| :--- | :--- |
| `ssh` | Secure Shell remote access (e.g., `ssh allen@192.168.2.1`). |
| `ip address` | Display and configure network interfaces and IP addresses. |
| `ifconfig` | Legacy network interface configuration tool. |
| `ping` | Test ICMP connectivity to a remote host. |
| `traceroute` | Trace the hop-by-path packets take to a destination. |
| `netstat` | Legacy tool for network statistics and routing tables. |
| `ss -tulpn` | Modern tool to view listening ports and active socket connections. |
| `resolvectl status` | Check systemd-resolved DNS status. |
| `cat /etc/resolv.conf` | View configured DNS nameservers. |
| `wget` / `curl` | Retrieve data from web servers via CLI. |

[Image of Linux network troubleshooting commands ip address and ss output]

## 🛡️ 4. Security & Firewall
| Command | Description |
| :--- | :--- |
| `sudo` | Execute a command with root/administrative privileges. |
| `su -` | Switch to the root user account. |
| `whoami` | Display the current
