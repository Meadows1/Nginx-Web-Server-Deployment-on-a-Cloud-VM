# Project 1 – Public Linux Web Server

## Overview

This project demonstrates deploying a public Linux web server in the cloud using Ubuntu and nginx.

The server hosts the default nginx webpage and is accessible through a public IP address.

---

## Infrastructure Used

Cloud Provider: DigitalOcean  
Server Type: Droplet  
Operating System: Ubuntu 24.04 LTS  
Web Server: nginx

---

## Deployment Steps

1. Created a cloud server (Droplet) in DigitalOcean
2. Connected to the server using SSH
3. Updated the server packages
4. Installed nginx
5. Started the nginx service
6. Verified nginx status
7. Accessed the web server through the public IP address

---

## Commands Used

Update packages

```
sudo apt update
```

Install nginx

```
sudo apt install nginx
```

Start nginx

```
systemctl start nginx
```

Check nginx status

```
systemctl status nginx
```

---

## Result

The nginx default page loads successfully when visiting the server’s public IP address.

Example:

```
http://159.203.71.189
```

---

## Concepts Demonstrated

Linux server management  
SSH remote access  
System services  
Web server deployment  
Cloud infrastructure basics

---

## Author

Everett Meadows Jr.
