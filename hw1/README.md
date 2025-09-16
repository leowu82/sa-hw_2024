# HW1 - Install FreeBSD and Basic Configurations

This repository documents the setup and configuration of FreeBSD, showcasing core competencies in system setup, user management, security, and networking.

## Key Tasks
- **OS Installation & Virtualization:** Deployed **FreeBSD 14.1** on an **Oracle VM VirtualBox** instance, including performing initial system updates and configurations like setting the hostname and time zone.
- **User & Privilege Management:** Configured administrative access by installing and editing `sudoers` with `visudo`. Managed system users and groups using standard utilities like `adduser` and `pw`.
- **Secure Remote Access:** Enabled and configured the **SSH daemon** (`sshd`) to allow for secure, key-based remote authentication, hardening the system against unauthorized access.
- **Package & Repository Management:** Utilized the `pkg` tool to install and manage software. Modified the package repository configuration (`/etc/pkg/FreeBSD.conf`) to point to a specific mirror for optimized downloads.
- **VPN Configuration:** Set up a secure network tunnel by installing and configuring **WireGuard**. This involved generating keys, defining the interface in `/usr/local/etc/wireguard/wg0.conf`, and activating the connection with `wg-quick`.
- **System Customization:** Modified system configuration files to customize the user login experience (`/etc/motd.template`) and system behavior (`/etc/sysctl.conf`).

## Skills Demonstrated
- **Command-Line Interface (CLI):** Use shell for system navigation, file editing (`vi`), and executing commands for administration and networking tasks.
- **User & Access Control:** Practical experience in creating users/groups and managing system permissions and privilege escalation with `sudo`.
- **Network & Security:** Securing remote access with **SSH** and establishing encrypted network connections using **WireGuard VPNs**.
- **Service & Package Management:** Manage system services (`service`) and handling software installation and repository configuration with `pkg`.
- **Troubleshooting:** Demonstrated ability to diagnose and resolve system issues, such as resolving package installation errors and recovering from user management misconfigurations.

## Notes
https://sun-ski-6a4.notion.site/HW1-Install-FreeBSD-107768cf5f3580b29676d853efb5355e?source=copy_link
