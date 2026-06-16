# Linux Administration Lab

## Overview

This project demonstrates core Linux system administration tasks using Red Hat Enterprise Linux (RHEL). The lab focuses on user and group management, permissions, ownership, process monitoring, service management, log analysis, storage administration, Logical Volume Manager (LVM) inspection, Bash scripting, and automated system health reporting.

The objective of this lab was to gain hands-on experience performing common Linux administration tasks in a live enterprise Linux environment.

---

## Environment

### Operating System

* Red Hat Enterprise Linux 10.1 (Coughlan)

### Platform

* Oracle VirtualBox

### Architecture

* x86_64

### User

* ronnyearly

---

## Skills Demonstrated

### User Administration

* Create Linux users
* Verify user accounts
* Manage account information

Commands Used:

```bash
useradd
id
passwd
```

### Group Administration

* Create groups
* Add users to groups
* Verify group membership

Commands Used:

```bash
groupadd
usermod
groups
getent group
```

### Permissions and Ownership

* Create directories
* Modify ownership
* Configure access permissions
* Validate access controls

Commands Used:

```bash
mkdir
chown
chmod
ls -ld
```

### Process Management

* View running processes
* Inspect process information

Commands Used:

```bash
ps -ef
```

### Service Management

* List running services
* Inspect service status

Commands Used:

```bash
systemctl
```

### Log Analysis

* Review systemd service logs
* Analyze scheduled task activity

Commands Used:

```bash
journalctl
```

### Storage Administration

* Review filesystem capacity
* Inspect disk layouts
* Verify LVM configuration

Commands Used:

```bash
df -h
lsblk
```

### Bash Automation

* Create executable scripts
* Generate system health reports
* Automate operational reporting

Commands Used:

```bash
chmod
bash
```

---

## Lab Activities

### User and Group Management

Created an administrative user account and assigned group membership to demonstrate role-based access control (RBAC).

### Directory Ownership and Permissions

Created a shared monitoring directory and configured ownership and permissions using Linux access control concepts.

### Process and Service Monitoring

Reviewed active processes and inspected running system services using systemctl and ps.

### Log Investigation

Analyzed cron service logs using journalctl to validate scheduled task execution and service health.

### Storage Analysis

Reviewed filesystem utilization and inspected disk partitioning and LVM configuration.

### System Health Automation

Developed a Bash script that generates a Linux system health report containing:

* Hostname
* Disk Usage
* Memory Usage
* Swap Usage

---

## Automation Script

### system-health.sh

Generates a basic operational health report for Linux systems.

Features:

* Hostname collection
* Disk capacity reporting
* Memory utilization reporting
* Swap utilization reporting

---

## Project Deliverables

* Linux Administration Documentation
* User and Group Management Examples
* Permissions and Ownership Configuration
* Process and Service Monitoring Examples
* Log Analysis Examples
* Storage Administration Examples
* Bash Automation Script
* System Health Report
* Project Screenshots

---

## Business Use Case

Linux administrators are responsible for managing user access, maintaining system security, monitoring services, troubleshooting issues, reviewing logs, managing storage, and automating operational tasks.

This lab simulates common day-to-day administration activities performed in enterprise Linux environments and demonstrates foundational skills used by Systems Administrators, Infrastructure Engineers, Site Reliability Engineers (SREs), and Platform Engineers.

---

## Technologies Used

* Red Hat Enterprise Linux (RHEL)
* Oracle VirtualBox
* Bash
* systemd
* journalctl
* LVM

---

## Author

Ronny Early

Linux Administration Lab
