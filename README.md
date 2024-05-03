<p align="center">
<img src="assets/zammad-logo.svg" alt="Zammad Logo" />
</p>

# Zammad Community on Azure
Implemented a Help Desk Ticketing System on Azure to optimize IT support processes. Leveraging Azure's infrastructure, it centralized support requests for efficient handling and enhanced user satisfaction.

## Environments and Technologies Used

- Microsoft Azure (Virtual Machines/Compute)
- Zammad Community for Ubuntu
- Elasticsearch

## Operating Systems Used

- Ubuntu Server 22.04 LTS

## High-Level Deployment and Configuration Steps

- Create  virtual machine in Azure using Ubuntu Server image
- Update Ubuntu Server
- Add Zammad repository to apt sources list
- Update the package list and install Zammad
- Add Elasticsearch repository
- Update package list and install Elasticsearch
- Update Elasticsearch configuration file
- Connect Zammad to Elasticsearch
- Open port 80 and 443 on Ubuntu Firewall
- Update Zammad configuration file
- Start Zammad and launch Getting Started Wizard


<h2>Architecture Diagram</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
