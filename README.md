# ICT171---Assignment-3--Gamezone.
ICT171 Assignment 3 - Cloud hosted GameZone website on Microsoft Azure with DNS, GitHub documentation and server configuration.

## Student Information

**Student Name:** Norbu Gyaltsen
**Assignment 3** ICT171 – Introduction to Server Environments and Architectures
**Project Name:** GameZone

---

## Project Overview

GameZone is a gaming website hosted on a Microsoft Azure Virtual Machine. The project demonstrates cloud computing concepts including server deployment, Linux administration, web hosting, DNS configuration, GitHub version control, and website management.

The website provides information about different game categories including Racing, Horror, and Action games. The website is publicly accessible through a custom domain name.

---

## Cloud Infrastructure

### Cloud Provider

Microsoft Azure

### Virtual Machine Details

* Operating System: Ubuntu Linux 24.04
* VM Name: MurdochVM
* Public IP Address: 20.213.185.249
* Web Server: Nginx

---

## Web Server Configuration

Nginx was installed and configured on the Azure Virtual Machine to host the GameZone website.

Commands used:

```bash
sudo apt update
sudo apt install nginx
sudo systemctl start nginx
sudo systemctl enable nginx
```

The website files were stored in:

```bash
/var/www/html
```

---

## Website Deployment

The GameZone website was developed using HTML and CSS.

Features include:

* Home page
* Racing games section
* Horror games section
* Action games section
* Navigation menu
* Cloud server information
* License information

---

## DNS Configuration

Cloudflare was used to manage the domain name.

Domain Name:

[www.gamezone-usa.com](http://www.gamezone-usa.com)

DNS records were configured to point the domain name to the Azure Virtual Machine public IP address.

---

## GitHub Repository

GitHub was used to store and manage project files.

Repository contents include:

* Website source code
* Project documentation
* Server script
* Assignment screenshots

---

## Server Script

A Bash script named serverinfo.sh was created to display system information.

Functions performed:

* Display current date
* Display hostname
* Display disk usage
* Display memory usage

Example execution:

```bash
chmod +x serverinfo.sh
./serverinfo.sh
```

---

## Screenshots

Project screenshots are stored in the images folder and include:

* Azure VM configuration
* Nginx service status
* Website deployment
* DNS configuration
* GitHub repository
* Script execution

---

## References

Microsoft Azure Documentation  
Nginx Documentation  
Cloudflare Documentation  
GitHub Documentation  
