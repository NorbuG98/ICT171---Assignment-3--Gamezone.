# ICT171---Assignment-3--Gamezone.
ICT171 Assignment 3 - Cloud hosted GameZone website on Microsoft Azure with DNS, GitHub documentation and server configuration.

## Student Information

**Student Name:** Norbu Gyeltshen
**Unit:** ICT171 – Introduction to Server Environments and Architectures
**Project Name:** GameZone

---

## Project Overview

GameZone is a gaming website hosted on a Microsoft Azure Virtual Machine. This project demonstrates cloud computing concepts including server deployment, Linux administration, web hosting, DNS configuration, GitHub version control, website deployment, and HTTPS security implementation.

The website provides information about different gaming categories including Racing, Horror, and Action games. The website is publicly accessible through a custom domain name and is hosted using the Nginx web server.

---

## Cloud Infrastructure

### Cloud Provider

Microsoft Azure

### Virtual Machine Details

* Operating System: Ubuntu Linux 24.04
* Virtual Machine Name: MurdochVM
* Public IP Address: 20.213.185.249
* Web Server: Nginx
* Domain Name: [www.gamezone-usa.com](http://www.gamezone-usa.com)

---

## Web Server Configuration

Nginx was installed and configured on the Azure Virtual Machine to host the GameZone website.

### Commands Used

```bash
sudo apt update
sudo apt install nginx
sudo systemctl start nginx
sudo systemctl enable nginx
```

### Website Location

```bash
/var/www/html
```

---

## Website Deployment

The GameZone website was developed using HTML and CSS and deployed on an Azure Virtual Machine.

### Website Features

* Home page
* Racing games section
* Horror games section
* Action games section
* Navigation menu
* Cloud server information
* License information

---

## DNS Configuration

Cloudflare was used to manage DNS records and connect the custom domain to the Azure Virtual Machine.

### Domain Name

[www.gamezone-usa.com](http://www.gamezone-usa.com)

### DNS Records

A records were configured to point both:

* gamezone-usa.com
* [www.gamezone-usa.com](http://www.gamezone-usa.com)

to the Azure Virtual Machine public IP address.

---

## GitHub Repository

GitHub was used for version control and project documentation.

The repository contains:

* Website source code
* Project documentation
* Server scripts
* Assignment screenshots
* HTTPS configuration notes

---

## Server Script

A Bash script named **serverinfo.sh** was created to display basic server information.

### Functions Performed

* Display current date and time
* Display server hostname
* Display disk usage information
* Display memory usage information

### Example Execution

```bash
chmod +x serverinfo.sh
./serverinfo.sh
```

---

## HTTPS Configuration

HTTPS was implemented using Certbot and Let's Encrypt SSL certificates.

### Commands Used

```bash
sudo apt install certbot python3-certbot-nginx
sudo certbot --nginx
```

HTTPS provides encrypted communication between users and the website and improves website security.

---

## Screenshots

Project screenshots are stored in the **images** folder and include:

* Azure Virtual Machine configuration
* Nginx service status
* Website deployment
* Cloudflare DNS configuration
* GitHub repository structure
* Server script execution
* HTTPS configuration

---

## References

* Microsoft Azure Documentation
* Nginx Documentation
* Cloudflare Documentation
* GitHub Documentation
* Certbot Documentation
* Let's Encrypt Documentation
  
