# windows-server-2022-infrastructure-lab
Enterprise-style Windows Server 2022 lab demonstrating ADDS, DHCP, DNS, and IIS role configuration, network services setup, and basic infrastructure administration in VMware Workstation.
# Windows Server 2022 Infrastructure Lab

## Overview
This project demonstrates a basic Windows Server 2022 setup including ADDS, DHCP, DNS, FTP and IIS services in a virtual environment.

## Features
- Active Directory setup
-   Added few account
-   Joined domain
-   created OU
-   Created security group
-   create policy
- DHCP server configuration
-   Created DHCP Roles
-   DHCP IP Ranges
-   DHCP wins server
- DNS server configuration
-   create new zone
-   forward / reverse zone
-   added few host/seq ip's
- FTP Server
-   FTP Config through Local file
- IIS web hosting
- VMware-based lab environment

## Server Architecture
windows-server-2022-infrastructure-lab/
│
├── README.md
├── Architecture/
│   └── network-diagram.png
│
├── ActiveDirectory/
│   └── ad-setup.md
│
├── DHCP/
│   ├── dhcp-config.ps1
│   └── dhcp-export.txt
│
├── DNS/
│   ├── dns-config.ps1
│   └── zone-export.dns
│
├── IIS/
│   ├── iis-setup.ps1
│   └── website-config.md
│
├── FTP/
│   ├── ftp-setup.ps1
│   └── ftp-notes.md
│
├── Backup/
│   ├── backup-script.ps1
│   └── system-backup.txt
│
├── Scripts/
│   ├── install-roles.ps1
│   ├── dhcp.ps1
│   ├── dns.ps1
│   ├── iis.ps1
│   ├── ftp.ps1
│
├── Network/
│   └── ipconfig-all.txt
│
├── Screenshots/
│   ├── dhcp-scope.png
│   ├── dns-zone.png
│   ├── iis-website.png
│   ├── ftp-test.png
│
└── Notes/
    ├── troubleshooting.md
    └── learning-summary.md

## Tools Used
- Windows Server 2022
- VMware Workstation
- PowerShell

## Author
Server support Engineer Lab Project
