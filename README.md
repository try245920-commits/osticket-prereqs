<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p># osTicket on Azure — Prerequisites & Installation Lab

## Summary
This project documents how I deployed the osTicket help desk ticketing system in a Microsoft Azure lab environment. It includes prerequisites, and installation steps.

## Skills Demonstrated
- Azure VM provisioning (Windows Server / Windows 10)
- IIS setup and web app hosting
- MySQL database setup
- osTicket installation and configuration
- Basic troubleshooting and documentation

## Lab Environment
- Cloud: Microsoft Azure
- VM OS: (example: Windows Server 2019 / Windows 10)
- Web Server: IIS
- Database: MySQL
- App: osTicket

## List of Prerequisites

# Overview

## What is osTicket?
osTicket is an open-source help desk ticketing system that allows users to submit support tickets and allows agents to manage, prioritize, and resolve issues.

## Why this lab matters
This lab demonstrates my ability to:
- Build a working help desk system
- Set up a web server and database
- Document a technical process clearly
- Troubleshoot common deployment issues



# Prerequisites

## Azure Resources
- Resource Group: (name)
- Virtual Network: (name)
- Virtual Machine: (name)
- Public IP:

## VM Requirements
- OS: (Windows Server 2019/2022 or Windows 10)


## Required Software/Components
- IIS (Web Server)
- PHP (supported version for osTicket)
- MySQL (or MariaDB)
- PHP Manager for IIS (optional but helpful)

## Network / Access
- RDP access to VM

# Installation " the meat"

## 1) Connect to the VM
- Action: RDP into the VM
- Expected result: Desktop loads successfully

Screenshot: (add image name here)

## 2) Install IIS
- Action: Turn Windows features on/off → enable IIS + required features
- Expected result: IIS Manager opens

Screenshot: (add image name here)

## 3) Install PHP + required extensions
- Action: Install PHP and enable extensions needed by osTicket
- Expected result: PHP works with IIS

Screenshot: (add image name here)

## 4) Install MySQL
- Action: Install MySQL and create database user
- Expected result: MySQL service running

Screenshot: (add image name here)

## 5) Download & deploy osTicket
- Action: Place osTicket files in IIS web root (or site directory)
- Expected result: osTicket setup page loads in browser

Screenshot: (add image name here)

## 6) Run osTicket web installer
- Action: Complete web installer fields + connect to database
- Expected result: Successful install confirmation

Screenshot: (add image name here)

## 7) Post-install hardening
- Action: Rename or remove setup directory, secure config file
- Expected result: osTicket admin panel works and setup is locked


## Screenshots
Screenshots are stored in the `/screenshots` folder and referenced throughout the documentation.



