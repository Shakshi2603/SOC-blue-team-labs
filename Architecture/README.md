# Lab Architecture

## Environment

| Machine | OS | Role | IP |
|---|---|---|---|
| Kali-Attacker | Kali Linux | Attacker | 192.168.10.5 |
| Ubuntu-Victim | Ubuntu Server 22.04 | Linux Target | 192.168.10.30 |
| DC01-Server | Windows Server 2022 | Domain Controller | 192.168.10.10 |
| WS01-Client | Windows 10 | Workstation 1 | 192.168.10.20 |
| WS02-Client | Windows 11 | Workstation 2 | 192.168.10.21 |
| Wazuh-SIEM | Ubuntu Server 22.04 | SIEM | 192.168.10.100 |

## Network
- **Host-Only Network:** All VMs communicate internally
- **NAT:** Kali and Wazuh have internet access
- **Domain:** SOC.LAB
