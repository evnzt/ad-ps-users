<p align="center">
<img width="480" height="270" alt="psise-1" src="https://github.com/user-attachments/assets/bc5d4caa-23b3-4d0a-8637-a2af5de3cb89" />
</p>

## Windows PowerShell ISE Script

This script creates user accounts with randomly generated names so you can populate labs with realistic fake users.<br />


## Tool(s) Used

- PowerShell ISE

## Operating System(s) Used

- Windows

## Instructions

- Open **PowerShell ISE** as an **Administrator**
- Copy the raw code and paste it into a new **ISE** script file.
- (*Recommended*) Reduce the number of accounts (*e.g., from 10k to 1k*) for a faster lab run.
- Run the script (*F5*) and watch accounts being created in **_EMPLOYEES**.

## Disclaimer

This script relies on having an **Organizational Unit (OU)** called `_EMPLOYEES` created in **Active Directory Users and Computers (ADUC)**.
