# Wireless Penetration Testing & Network Reconnaissance

**Author:** Pedro Gonçalves  
**Area:** Ethical Hacking · Wireless Security · Network Reconnaissance  
**Environment:** Authorized, isolated cybersecurity laboratory  
**Report language:** Portuguese

## Project Overview

This project documents practical wireless security assessments and internal network reconnaissance in a controlled lab. The report combines configuration notes, terminal screenshots, tool output, methodology, and a footprinting-style assessment of the observed network exposure.

The work is organized around two complementary areas: **wireless penetration testing** and **network discovery, scanning, and service enumeration**. Activities are presented as educational exercises performed within an authorized environment.

## Laboratory Scope

- **Wireless environment:** simulated/local WPA/WPA2 access point and wireless clients.
- **Internal lab network:** `192.168.56.0/24`.
- **Testing workstation:** Kali Linux.
- **Targets:** Windows Server and Windows desktop virtual machines.

Addresses and wireless identifiers are laboratory examples, not public targets.

## Technologies & Tools

| Category | Tools and protocols |
| --- | --- |
| Wireless lab setup | `mac80211_hwsim`, `hostapd`, `wpa_supplicant` |
| Wireless security assessment | Airgeddon, Aircrack-ng, Hashcat, Crunch, WPA/WPA2, PMKID |
| Host discovery | Netdiscover, arp-scan, Nmap |
| Port and protocol assessment | Nmap, Masscan, Unicornscan, Hping3 |
| Windows service enumeration | SMB, RPC, NetBIOS, smbmap, smbclient, enum4linux |
| Auxiliary assessment | Metasploit Framework, CrackMapExec |
| Network traffic analysis | Wireshark, tcpdump (methodology and study context) |

## Practical Work Covered

### 1. Wireless Network Assessment

- Creation and inspection of virtual wireless interfaces.
- Configuration of an access point and client association in the lab.
- Introduction to wireless monitor mode and packet capture.
- WPA/WPA2 handshake and PMKID assessment.
- Offline password-strength testing with dictionary, brute-force, and rule-based approaches.
- Study of deauthentication and Evil Twin/captive-portal risks.

### 2. Network Reconnaissance & Enumeration

- Discovery of reachable systems on an isolated subnet.
- TCP/UDP port scanning and service/version identification.
- Windows SMB/RPC service assessment and enumeration.
- Auxiliary checks with Metasploit and other command-line tools.
- Interpretation of exposed services, authentication controls, and hardening opportunities.

### 3. Security Findings & Recommendations

The report includes a footprinting-style summary of laboratory observations and recommendations relating to wireless password strength, rogue access point detection, network segmentation, restricted remote access, and SMB security settings.

**Evidence caveat:** Some sections in the source report contain example values, planned steps, or unfilled screenshot placeholders. Such material should not be interpreted as independently verified successful exploitation.

## Technical Report

📄 **[View the complete illustrated PDF report](Wireless_Penetration_Testing_Pedro_Goncalves_Sem_Entidade_Colaboradores.pdf)**

The PDF contains screenshots, explanations, configuration commands, and a technical assessment. It is provided for portfolio and educational purposes.

## Skills Demonstrated

`Wireless Security` · `Ethical Hacking` · `WPA/WPA2` · `Network Reconnaissance` · `Nmap` · `Service Enumeration` · `SMB` · `Linux` · `Windows Security` · `Technical Reporting`

## Responsible Use

All activities described here must be limited to networks and systems owned by the tester or explicitly authorized for testing. Do not use these procedures against third-party networks. Review screenshots and supporting files for personal data, real credentials, and sensitive identifiers before publication.

## Author

**Pedro Gonçalves**  
[GitHub Portfolio](https://github.com/PedroGoncalves28286)
