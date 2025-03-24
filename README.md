# Week 7 Workshop - Enterprise Linux Infrastructure Simulation

This repository contains tutorial materials for setting up an Enterprise Linux Infrastructure using CentOS Stream 9. The workshop guides you through implementing a multi-VM environment with various enterprise services and security configurations.

## About This Workshop

This is the Week 7 Workshop content for the Coastline Community College Cyber Xploit Club Competition Workshop Training series. The content is designed and developed by Mike Crawford to prepare students for cybersecurity competitions like the Western Regional Collegiate Cyber Defense Competition (WRCCDC) and the National Collegiate Penetration Testing Competition (CPTC).

## Contents

- **Main Tutorial Page**: Comprehensive overview of the workshop and lab architecture
- **Gateway Configuration Guide**: Detailed steps for setting up the Gateway/Router VM
- **Web Server Setup Guide**: Step-by-step instructions for configuring a secure web server

## Lab Architecture

The lab consists of 6 virtual machines:

- Gateway/Router VM (Firewall, VPN, NAT)
- Web Server VM (Apache, Nginx, PHP)
- Database VM (MariaDB, PostgreSQL)
- Application Server VM (Docker, Kubernetes)
- Monitoring VM (Prometheus, ELK Stack)
- Client VM (Testing)

## Features

- Complex network architecture with DMZ and internal networks
- Secure web server configuration with HTTPS
- Reverse proxy setup combining Apache and Nginx
- Web Application Firewall implementation
- Enterprise-grade security hardening

## Getting Started

1. Open `enterprise_linux_tutorial.html` in your web browser
2. Follow the lab setup instructions
3. Use the detailed guides for each component

## Requirements

- VirtualBox/VMware
- CentOS Stream 9 installation media
- Vagrant (optional but recommended)
- Basic Linux knowledge
