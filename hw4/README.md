# HW4 - Web Services & NFS Firewall

## Key Tasks

* **Full Stack Web Service Deployment:** Built and configured a complete web service from the ground up on FreeBSD. The stack includes **Nginx** as the web server and reverse proxy, a **Python FastAPI** backend, a **PostgreSQL** database, and **PHP-FPM** for a database admin tool.
* **HTTPS & Public Key Infrastructure (PKI) Implementation:** Established a custom **Certificate Authority (CA)** using `openssl` to issue a wildcard SSL certificate. This was used to secure all web services with **HTTPS (TLS)** and enforce it globally using the **HSTS** header.
* **Backend API with Reverse Proxy:** Developed a RESTful API using **Python's FastAPI framework** and deployed it with a `uvicorn` ASGI server. Configured Nginx as a **reverse proxy** to securely route traffic from a public-facing domain to the internal backend application.
* **Database & Admin Tool Integration:** Deployed and administered a **PostgreSQL** database, managing users, databases, tables, and access privileges. Deployed **Adminer** (a PHP-based tool) by configuring Nginx to process PHP requests via **PHP-FPM**.
* **Network Service Configuration:** Set up a **Dnsmasq** server to provide local DNS resolution for wildcard subdomains. Implemented a stateful firewall using **`ipfw`** to control network traffic and enhance security.
* **System Automation and Logging:** Implemented custom access logging in Nginx with conditions to exclude specific user agents. Created a custom shell script for automated log rotation to manage disk space.


## Skills Demonstrated

* **Web Server Administration (Nginx):** Configure Nginx for diverse roles: a static file server, a **reverse proxy**, an SSL/TLS termination point, and a PHP application server via FastCGI.
* **Backend Development (Python/FastAPI):** Built and developed modern, high-performance web APIs with **FastAPI** and serving them with ASGI servers like **Uvicorn**.
* **Database Administration (PostgreSQL):** Set up, configured, and managed a **PostgreSQL** database, including user roles, permissions, and network access control (`pg_hba.conf`).
* **Security & Cryptography:** Practical application of **Public Key Infrastructure (PKI)** using `openssl` to create a custom CA and sign certificates. Implementation of security best practices like **HTTPS**, **HSTS**, **HTTP Basic Authentication**, and firewalling with `ipfw`.
* **Network Services (DNS & Firewall):** Deployed and configured core network services like **DNS (Dnsmasq)** and stateful firewalls (`ipfw`).
* **PHP Integration (PHP-FPM):** Knowledge of integrating PHP applications with Nginx via the **FastCGI** protocol, a standard for modern PHP deployments.
* **Full Stack Integration:** Integrate multiple disparate technologies (Nginx, Python, PostgreSQL, PHP) into a cohesive and functional web application stack.

## Notes
https://sun-ski-6a4.notion.site/HW4-Web-Services-NFS-Firewall-157768cf5f3580038518ea9eea10c481?source=copy_link
