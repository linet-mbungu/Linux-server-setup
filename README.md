# Linux Web Server Setup on Ubuntu

A documented project showing how to set up and secure a Linux web server from scratch using Ubuntu, Nginx, and UFW firewall.

## What This Project Covers
- Installing and configuring Nginx web server
- Setting up and enabling UFW firewall
- Creating a dedicated system user with sudo privileges
- Serving a custom webpage

## Environment
- OS: Ubuntu 24 (WSL2 on Windows)
- Web Server: Nginx
- Firewall: UFW

## Steps Taken

### 1. System Update
Updated all packages to latest versions before installation.

### 2. Nginx Installation & Configuration
Installed Nginx, started the service, and verified it was actively serving pages.

### 3. Firewall Setup (UFW)
Configured UFW firewall to allow only necessary traffic:
- Port 22 (SSH)
- Port 80 (HTTP / Nginx)

### 4. User Management
Created a dedicated user `webadmin` with sudo privileges following the principle of least privilege.

### 5. Custom Webpage
Replaced the default Nginx page with a custom HTML page served on localhost.

## Screenshots
### Nginx Running
![Nginx Status](screenshots/Screenshot%202026-06-12%20143112.png)

### Nginx Serving Pages
![Curl Output](screenshots/Screenshot%202026-06-12%20143205.png)

### Firewall Configuration
![UFW Status](screenshots/Screenshot%202026-06-12%20144721.png)

### User Management
![Webadmin User](screenshots/Screenshot%202026-06-12%20145233.png)

### Live Webpage
![Live Server](screenshots/Screenshot%202026-06-12%20145556.png)

## Skills Demonstrated
- Linux system administration
- Web server configuration
- Firewall management
- User and permission management

## Author
Linet Mbungu — [Upwork Profile](https://www.upwork.com/freelancers/~01714ed621e9bb1135)
