-🛡️ Network Intrusion Detection System (IDS) Lab

- Overview
A fully functional IDS lab environment built using VirtualBox virtualization,
demonstrating real-time detection of network attacks using Snort IDS.

- Architecture
| Node | Role | IP Address |
|------|------|------------|
| Windows Host | Target machine | 192.168.56.1 |
| Kali Linux | Attacker | 192.168.56.108 |
| Ubuntu Server | IDS Sensor (Snort) | 192.168.56.110 |

## Attack Scenarios Demonstrated
- ICMP Ping flood detection
- Nmap SYN / NULL / FIN / XMAS scan detection
- SSH brute force detection (Hydra)
- HTTP port scan detection

## Tools Used
- Oracle VirtualBox
- Snort 2.9.x (IDS)
- Kali Linux XFCE
- Ubuntu Server 22.04
- Nmap, Hydra, hping3

## Key Concepts
- Signature-based intrusion detection
- Network promiscuous mode monitoring
- Custom Snort rule development
- Real-time alert generation and log analysis

## Results
Snort successfully detected all simulated attack types,
generating 24 logged alerts across the full test session.

## Academic Context
End-of-year project — NETWORK AND TELECOM
JFN-HIGHTECH INSTITUTE OF TECHNOLOGY, Cameroon
