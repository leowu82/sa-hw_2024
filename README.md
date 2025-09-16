# Computer System Administration Coursework

This repository showcases four diverse computer system administration assignments (HW1-HW4) on FreeBSD, highlighting a broad range of technical skills and modern tech stacks. Each homework demonstrates practical, production-ready technologies and best practices in automation, networking, scripting, security, and full stack development.


## HW1: Install FreeBSD & Basic Configuration
**Tech Stack & Tools:** FreeBSD 14.1, Oracle VM VirtualBox, SSH, WireGuard, `pkg`, `sudo`, CLI (Shell)
- **OS Installation & Virtualization:** Deployed FreeBSD in VirtualBox, handled system updates, hostname, and timezone.
- **User & Privilege Management:** Managed users/groups, edited `sudoers` (with `visudo`), and configured permissions.
- **Secure Remote Access:** Hardened SSH daemon (`sshd`) for key-based login and remote administration.
- **Package & Repository Management:** Leveraged `pkg` for software installation, edited repo configuration for mirror selection.
- **VPN Configuration:** Set up encrypted tunnels using WireGuard for secure networking.
- **System Customization:** Edited `/etc/motd.template` and `/etc/sysctl.conf` for tailored system behavior.
- **Troubleshooting:** Diagnosed and resolved installation, user management, and network issues.


## HW2: Shell Scripting & REST API Automation
**Tech Stack & Tools:** POSIX Shell (`/bin/sh`), REST API, `curl`, `jq`, `awk`, `grep`, `tr`
- **API Automation:** Built a shell script to automate RESTful API interactions.
- **Dynamic Problem Solving:** Script fetches tasks, parses type, and executes routines (static response, arithmetic solver, password cracker).
- **Robust Input/Data Handling:** Used `getopts` for argument parsing, regular expressions for validation, and error handling (`>&2`).
- **Text & Data Processing:** Automated JSON parsing with `jq`, string manipulation with `awk`, `grep`, and cryptography with `tr`.
- **Workflow Automation:** Designed resilient, modular scripts for variable input and automated error diagnosis.


## HW3: File Server & Backup with Advanced Security
**Tech Stack & Tools:** FreeBSD, ZFS, SSH/SFTP, `gpart`, ACLs, `chmod`, `chown`, `setfacl`, `pw`, `adduser`, `rc.d`, `syslogd`
- **Storage Configuration:** Built a RAID10 pool with ZFS, using GPT partitions and mirrored vdevs for redundancy and performance.
- **Secure SFTP Server:** Hardened multi-user SFTP with chroot jails and SFTP-only restrictions in `sshd_config`.
- **Granular Access Control:** Combined Unix permissions (`chmod`, sticky bit) with Access Control Lists (`setfacl`).
- **Custom Service & Auditing:** Created custom `rc.d` daemons for monitoring and centralized SFTP log auditing via `syslogd`.
- **User & Group Administration:** Managed users/groups, shell access, and home directories with `adduser`, `pw`.
- **System Security & Hardening:** Applied least privilege, implemented chroot jails, and audited file access.


## HW4: Full Stack Web Services & Network Security
**Tech Stack & Tools:** Nginx, Python (FastAPI, Uvicorn), PostgreSQL, PHP-FPM, Adminer, Dnsmasq, OpenSSL, ipfw, shell scripting (log rotation)
- **Full Stack Web Service Deployment:** Built an integrated stack—Nginx (reverse proxy), FastAPI (backend), PostgreSQL (database), PHP-FPM (Adminer tool).
- **Web Server Administration:** Configured Nginx as static file server, reverse proxy, SSL/TLS terminator, and PHP handler.
- **Backend API Development:** Built RESTful APIs with FastAPI and served with Uvicorn.
- **Database Admin:** Deployed PostgreSQL, managed roles/permissions, and secured network access (`pg_hba.conf`).
- **Security & Cryptography:** Created a custom CA with OpenSSL, issued wildcard SSL certs, enforced HTTPS/HSTS, implemented firewalls with ipfw.
- **Network Services:** Set up DNS (Dnsmasq), managed stateful firewalls, automated log rotation via shell scripting.
- **PHP Integration:** Integrated Adminer using PHP-FPM and Nginx FastCGI.
- **Full Stack Integration:** Demonstrated ability to combine Nginx, Python, PostgreSQL, PHP into a cohesive production-grade solution.


## Tech Stack
- **Operating Systems:** FreeBSD, Linux (via shell tools)
- **Virtualization:** Oracle VM VirtualBox
- **Networking & Security:** SSH, WireGuard VPN, ipfw, chroot jails, SSL/TLS, OpenSSL, HSTS, HTTPS, PKI, firewalling, network ACLs
- **Scripting & Automation:** POSIX Shell, Bash, REST API, `curl`, `jq`, `awk`, `grep`, `tr`, rc.d scripts
- **Storage & Backup:** ZFS RAID, SFTP, syslog, ACL, sticky bit, file auditing
- **Web Development:** Nginx, FastAPI, Python, Uvicorn, PHP-FPM, Adminer, PostgreSQL, Dnsmasq
- **DevOps:** System automation, service management, log rotation, monitoring
- **Database:** PostgreSQL, SQL, user/role management
- **Cloud & Infrastructure:** DNS, SSL/TLS, certificate management, reverse proxy
- **System Administration:** User/group management, permissions, startup scripts, auditing, troubleshooting


> For detailed notes and step-by-step documentation, see each HW's README and the attached Notion documentation links.
