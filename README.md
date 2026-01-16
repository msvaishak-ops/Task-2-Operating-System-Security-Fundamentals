# Task-2-Operating-System-Security-Fundamentals
🛡️ OS Security & Hardening – README
📌 Project Title

Operating System Security & Hardening Basics

📖 Overview

This project focuses on understanding OS-level security by exploring user permissions, access control, services, and system hardening techniques. The goal is to reduce the attack surface of an operating system and follow security best practices commonly used in real-world environments.

This task is essential for anyone starting a career in Cyber Security, SOC, or System Administration.

🎯 Objectives

Understand how operating systems manage users and permissions

Learn Linux file permission concepts

Differentiate administrator and standard user roles

Identify and secure running services

Apply OS hardening best practices

Gain interview-relevant theoretical and practical knowledge

🧰 Tools & Environment

Operating System: Linux (Ubuntu/Kali)

Virtualization: VirtualBox (Optional)

Alternative: Windows OS with built-in security settings

🪜 Task Breakdown
1️⃣ OS Installation

Installed a Linux Virtual Machine using VirtualBox

Alternatively explored OS security features in Windows

2️⃣ User Accounts & Access Control

Explored:

Root (administrator) user

Normal (standard) users

Understood:

User IDs (UID)

Group IDs (GID)

Access control mechanisms

3️⃣ File Permissions in Linux

Used the following commands:

ls -l
chmod
chown


Permission Types:

r – Read

w – Write

x – Execute

User Categories:

Owner

Group

Others

4️⃣ Administrator vs Standard User

Root user has full system privileges

Normal users have limited permissions

Administrative actions require sudo

5️⃣ Firewall Configuration

Enabled UFW (Uncomplicated Firewall) on Linux

sudo ufw enable
sudo ufw status


Explored Windows Defender Firewall rules (Windows OS)

6️⃣ Running Processes & Services

Identified running processes using:

ps aux
top
systemctl list-units --type=service

7️⃣ Reducing Attack Surface

Disabled unnecessary services

Ensured only required services are running

Reduced potential entry points for attackers

8️⃣ OS Hardening Best Practices

Apply least privilege principle

Disable unused services

Keep OS updated

Use strong passwords

Enable firewall

Monitor logs regularly
