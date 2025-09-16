# HW3 - File Server and Backup

## Key Tasks

* **Advanced Storage Configuration:** Built a resilient and performant **RAID10** storage pool using **ZFS**. This involved partitioning four virtual disks with a **GPT** scheme (`gpart`), creating two mirrored pairs for data redundancy, and striping them together into a single `zpool` for improved performance.
* **Secure SFTP Server Implementation:** Deployed and hardened a multi-user SFTP server. This included creating dedicated users, configuring the SSH daemon to enforce a **chroot jail**, and restricting specific user accounts to SFTP-only access, preventing shell login.
* **Granular Access Control:** Implemented a complex, multi-layered permission scheme. This combined standard Unix permissions (`chmod`, including the sticky bit for shared directories) with **Access Control Lists (ACLs)** (`setfacl`) to grant specific, fine-grained access rights to different users and groups.
* **Custom Service & System Auditing:** Developed a custom FreeBSD `rc.d` service to automatically launch a monitoring script at boot. Additionally, configured `sshd` and `syslog.conf` to redirect and capture all SFTP transaction logs to a dedicated file for auditing.


## Skills Demonstrated

* **Storage Management (ZFS):** Experienced with advanced ZFS administration, including `zpool` creation, vdev configuration (mirroring, striping), dataset management, and tuning properties like `mountpoint` and `compression`.
* **System Security & Hardening:** Secure services by implementing **chroot jails**, managing SSH/SFTP access rules in `sshd_config`, and applying the principle of least privilege to user accounts.
* **File Permissions & ACLs:** Managed access controls using both traditional Unix permissions (`chmod`, `chown`) and modern **Access Control Lists** (`setfacl`) for complex scenarios.
* **Service Management (rc.d):** Capable of writing and deploying custom FreeBSD `rc.d` startup scripts for managing daemons and ensuring services are enabled correctly on system boot.
* **System Auditing & Logging:** Experience with configuring `syslogd` and application-level settings to monitor and centralize system activity logs.
* **User & Group Administration:** Managing user accounts, groups, home directories, and shell access using utilities like `adduser` and `pw`.

## Notes
https://sun-ski-6a4.notion.site/HW3-File-Server-and-Backup-132768cf5f3580f781e8dd95faed73a0?source=copy_link
