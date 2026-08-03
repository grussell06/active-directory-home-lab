# Active-Directory-Home-Lab

## Overview
This project documents the creation of a Windows enterprise lab using Active Directory Domain Services. The environment simulates a small business network with centralized authentication, Group Policy management, shared resources, and Windows security monitoring.

## Technologies



## Lab Architecture 

```mermaid
graph TD
  A[Host PC]
  A --> B[Windows Server 2022<br/>Domain Controller]
  A --> C[Windows 11 Client]
  A --> D[Splunk Enterprise]
  A --> E[Kali Linux]

  B --> F[Active Directory]
  C --> G[Sysmon]
  C --> H[Splunk Universal Forwarder]
```

## Active Directory Domain Services

### Objective
Configure the Windows Server as a domain controller.

### Steps Performed
- Installed the Active Directory Domain Services role.
- Promoted the server to a domain controller.
- Created the domain.
- Verified successful installation.

### Screenshots
<img width="744" height="117" alt="AD DS Installed" src="https://github.com/user-attachments/assets/8ec9b637-2033-4b0b-ac8d-df45646f872f" />

<img width="1023" height="774" alt="AD Users and Computers" src="https://github.com/user-attachments/assets/fc4b96ab-df81-42e5-844c-c9bf971f2b5d" />
