# Phase 2: CentOS Linux & Security Configuration

## Overview
In this phase, I worked with a CentOS virtual machine to strengthen my understanding of Linux security and network protection. I focused on firewall configuration and controlled access between systems.

## Setup
- Installed CentOS on a virtual machine
- Configured network settings for communication with Kali Linux
- Verified connectivity using ping tests

## Key Activities

### 1. Firewall Configuration
I worked with `firewalld` to manage system security.

Commands used:
- `sudo systemctl start firewalld`
- `sudo systemctl enable firewalld`
- `sudo firewall-cmd --state`

### 2. Managing Firewall Rules
I learned how to:
- Allow specific services:
  - `sudo firewall-cmd --add-service=ssh --permanent`
- Reload firewall rules:
  - `sudo firewall-cmd --reload`
- View active rules:
  - `sudo firewall-cmd --list-all`

### 3. Security Testing with Nmap
From Kali Linux, I performed network scans:
- `nmap <CentOS IP address>`

This helped me understand:
- Open ports
- Running services
- Exposure of a system to network attacks

### 4. Access Control Understanding
I learned how firewalls control:
- Incoming traffic
- Outgoing traffic
- Service accessibility

## Outcome
I gained hands-on experience in securing a Linux system using firewall rules and analyzing network exposure using Nmap scans.
