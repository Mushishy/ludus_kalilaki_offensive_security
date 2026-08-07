
# Pentesting Tools

## Network Discovery and Scanning

- **nmap** #recon #exploitation - Network scanner for host discovery and port scanning
- **zenmap** #recon - Official graphical interface for nmap
- **masscan** #recon - Fast TCP port scanner
- **netdiscover** #recon - ARP-based network scanner
- **passive_discovery6** #recon - IPv6 passive discovery tool
- **netstat** #recon - Display network connections and routing tables
- **ipconfig** #recon - Windows IP configuration tool
- **arp** #recon - Address Resolution Protocol utility
- **arping** #recon - ARP ping utility
- **arpwatch** #recon - Monitor ARP activity
- **ping** #recon - ICMP echo request utility
- **ping6** #recon - IPv6 ping utility
- **traceroute** #recon - Network diagnostic tool for tracing packet routes
- **tcptraceroute** #recon - TCP-based traceroute

## Network Traffic Analysis

- **wireshark** #recon #exploitation - Network protocol analyzer
- **tcpdump** #recon #exploitation - Command-line packet analyzer
- **p0f** #recon - Passive OS fingerprinting tool
- **ettercap** #exploitation - Comprehensive network security tool for MitM attacks
- **dsniff** #exploitation - Network auditing and penetration testing toolkit
- **arpspoof** #exploitation - ARP spoofing tool
- **responder** #exploitation - LLMNR, NBT-NS and MDNS poisoner

## Vulnerability Scanning

- **Nessus** #recon #exploitation - Commercial vulnerability scanner
- **OpenVAS** #recon #exploitation - Open-source vulnerability scanner
- **Nuclei** #recon #exploitation - Fast vulnerability scanner
- **Qualys** #recon #exploitation - Cloud-based vulnerability scanner

## DNS Testing

- **nslookup** #recon - DNS lookup utility
- **dig** #recon - DNS lookup tool (more advanced than nslookup)
- **amass** #recon - OWASP project for DNS enumeration and subdomain discovery
- **fierce** #recon - Domain scanner for locating non-contiguous IP ranges
- **dmitry** #recon - Domain information gatherer
- **whois** #recon - Domain registration information lookup
- **sublist3r** #recon - Subdomain enumeration tool
- **SubBrute** #recon - Subdomain brute-forcer
- **dnsrecon** #recon - DNS reconnaissance tool
- **dnsenum** #recon - DNS enumeration tool

## Web Application Testing

- **gobuster** #recon #exploitation - Directory and file brute-forcer
- **ffuf** #recon #exploitation - Fast web fuzzer
- **wfuzz** #recon #exploitation - Web application fuzzer
- **dirb** #recon #exploitation - Web content scanner
- **dirbuster** #recon #exploitation - Directory and filename brute-forcer
- **Burp Suite** #recon #exploitation - Web application security testing platform
- **OWASP ZAP** #recon #exploitation - Web application security scanner
- **nikto** #recon #exploitation - Web vulnerability scanner
- **w3af** #exploitation - Web application attack and audit framework
- **skipfish** #recon - Web application reconnaissance tool
- **wappalyzer** #recon - Technology profiler (browser extension)
- **sqlmap** #exploitation - SQL injection testing tool
- **XSStrike** #exploitation - XSS detection suite
- **Commix** #exploitation - Command injection exploiter
- **wpscan** #recon #exploitation - WordPress vulnerability scanner
- **droopescan** #recon #exploitation - Drupal vulnerability scanner (orphaned)
- **joomscan** #recon #exploitation - Joomla vulnerability scanner
- **testssl.sh** #recon #exploitation - SSL/TLS configuration checker

## Database Testing

- **sqlmap** #exploitation - SQL injection testing tool
- **SQLNinja** #exploitation - SQL injection exploitation tool
- **NoSQLMap** #exploitation - NoSQL injection tool
- **MongoDB tools** #recon #exploitation - Database testing utilities
- **Oracle tools** #recon #exploitation - Database security testing

## SMB/NetBIOS Testing

- **smbclient** #recon #exploitation - SMB client
- **enum4linux** #recon - Linux SMB enumeration
- **nmblookup** #recon - NetBIOS name lookup
- **net** #recon #exploitation - Windows networking command
- **smbmap** #recon - SMB share enumerator
- **rpcclient** #recon #exploitation - RPC client
- **nbtscan** #recon - NetBIOS name scanner

## SNMP Testing

- **snmpwalk** #recon - SNMP enumeration tool
- **snmp-check** #recon - SNMP enumerator
- **onesixtyone** #recon - SNMP scanner

## FTP Testing

- **ftp** #delivery - FTP client
- **tftp** #delivery - TFTP client
- **ncftp** #delivery - Enhanced FTP client


## Email/SMTP Testing

- **swaks** #exploitation - SMTP testing tool
- **smtp-user-enum** #exploitation - SMTP user enumeration

## WiFi Testing

- **aircrack-ng** #exploitation - WiFi security auditing suite (WEP/WPA cracking)
- **airmon-ng** #recon - WiFi monitor mode enabler
- **airodump-ng** #recon - WiFi packet capture
- **aireplay-ng** #exploitation - WiFi packet injection
- **wifiphisher** #delivery #exploitation - WiFi phishing framework
- **airgeddon** #recon #delivery - WiFi auditing script
- **kismet** #recon - Wireless network detector and IDS
- **WiFi Pineapple** #delivery - Wireless penetration testing platform

## Bluetooth Testing

- **btscanner** #recon - Bluetooth device scanner
- **bluetoothctl** #recon - Bluetooth control utility
- **hcitool** #recon - Bluetooth device configuration
- **spooftooph** #exploitation - Bluetooth device spoofing

## Active Directory Testing

- **BloodHound** #recon #exploitation - AD attack path analysis
- **SharpHound** #recon - BloodHound data collector
- **PowerView** #recon - AD reconnaissance PowerShell script
- **SharpView** #recon - C# port of PowerView
- **ldapsearch** #recon - LDAP search tool
- **ADFind** #recon - AD command-line query tool
- **Rubeus** #exploitation - Kerberos abuse toolkit
- **GetUserSPNs.py** #exploitation - Kerberoasting script
- **kerbrute** #exploitation - Kerberos username enumeration

## Password Attacks

- **hashcat** #exploitation - Advanced password recovery
- **john the ripper** #exploitation - Password cracking tool
- **hydra** #exploitation - Network login cracker
- **medusa** #exploitation - Password cracking tool
- **patator** #exploitation - Multi-purpose brute-forcer
- **hash-identifier** #exploitation - Hash type identifier
- **findmyhash** #exploitation - Online hash cracker
- **crunch** #weaponization - Wordlist generator
- **CeWL** #weaponization - Custom wordlist generator


## Physical Security

- **USB Rubber Ducky** #delivery - USB keystroke injection tool
- **Flipper Zero** #delivery - Multi-tool for pentesters

## Social Engineering

- **Social Engineer Toolkit (SET)** #delivery - Social engineering framework
- **Gophish** #delivery - Phishing campaign toolkit
- **King Phisher** #delivery - Phishing campaign toolkit

## OSINT/Information Gathering

- **theharvester** #recon - Email and subdomain harvester
- **recon-ng** #recon - Web reconnaissance framework
- **Maltego** #recon - Link analysis and data visualization
- **spiderfoot** #recon - OSINT automation tool
- **Shodan** #recon - Internet-connected device search engine
- **SimplyEmail** #recon - Email reconnaissance tool
- **Metagoofil** #recon - Metadata extraction tool
- **sherlock** #recon - Social media username checker
- **social-analyzer** #recon - Social media analysis tool
- **exiftool** #recon - Metadata extraction tool
- **FOCA** #recon - Document metadata analysis

## Exploitation Frameworks

- **Metasploit Framework** #exploitation - Penetration testing framework
- **Metasploit Pro** #exploitation - Commercial version of Metasploit
- **msfconsole** #exploitation - Metasploit console interface
- **Armitage** #exploitation - GUI for Metasploit
- **Cobalt Strike** #exploitation #command_and_control - Commercial penetration testing platform
- **Empire** #command_and_control - Post-exploitation framework
- **Covenant** #command_and_control - .NET command and control framework

## Payload Generation and Weaponization

- **msfvenom** #weaponization - Metasploit payload generator
- **Veil** #weaponization - Payload generator framework
- **Phantom-Evasion** #weaponization - AV evasion tool
- **Shellter** #weaponization - Dynamic shellcode injection
- **TheFatRat** #weaponization - Massive exploiting tool
- **searchsploit** #weaponization - Exploit-DB command line search tool
- **msf-virustotal** #weaponization - VirusTotal integration

## Post-Exploitation and Privilege Escalation

- **LinPEAS** #installation - Linux privilege escalation script
- **linenum** #installation - Linux privilege escalation script
- **winPEAS** #installation - Windows privilege escalation script
- **adpeas** #installation - AD privilege escalation script
- **linux-exploit-suggester** #installation - Linux exploit suggester
- **windows-exploit-suggester** #installation - Windows exploit suggester
- **pspy** #installation - Linux process monitor
- **GTFOBins** #installation - Unix binaries privilege escalation
- **LOLBAS** #installation - Living Off The Land Binaries and Scripts
- **mimikatz** #installation #actions_on_objectives - Windows credential extractor
- **LaZagne** #installation #actions_on_objectives - Credential harvesting tool
- **secretsdump.py** #installation #actions_on_objectives - Credential dumper
- **lsassy** #installation #actions_on_objectives - LSASS memory extractor
- **impacket** #exploitation #command_and_control - Python network protocols library

## Lateral Movement

- **psexec** #exploitation #command_and_control - Remote execution tool
- **winrm** #exploitation #command_and_control - Windows Remote Management
- **evil-winrm** #exploitation #command_and_control - WinRM pentesting tool
- **crackmapexec** #exploitation - Network service exploitation
- **Invoke-TheHash** #command_and_control - PowerShell hash passing toolkit

## Command and Control / Tunneling

- **nc (netcat)** #command_and_control #delivery - Network utility
- **ncat** #command_and_control - Netcat reimplementation
- **socat** #command_and_control #delivery - Socket relay tool
- **proxychains** #command_and_control - Proxy chaining tool
- **ProxyTunnel** #command_and_control - HTTP tunnel through proxy
- **chisel** #command_and_control - TCP/UDP tunnel over HTTP
- **ligolo-ng** #command_and_control - Tunneling tool
- **OpenVPN** #command_and_control - VPN client/server
- **WireGuard** #command_and_control - VPN protocol
- **sshuttle** #command_and_control - VPN over SSH
- **screen** #command_and_control - Terminal multiplexer
- **tmux** #command_and_control - Terminal multiplexer

## File Transfer and Delivery

- **curl** #delivery #recon - Command-line HTTP client
- **wget** #delivery #recon - File downloader
- **python3 -m http.server** #delivery - Simple HTTP server
- **scp** #delivery - Secure copy
- **rsync** #delivery - File synchronization

## Cloud Security

- **ScoutSuite** #recon #exploitation - Cloud security auditing tool
- **Prowler** #recon #exploitation - AWS security assessment
- **CloudMapper** #recon #exploitation - AWS network visualization
- **Pacu** #exploitation - AWS exploitation framework
- **PowerZure** #exploitation - Azure exploitation toolkit
- **AzureHound** #recon #exploitation - Azure data collector for BloodHound
- **ROADtools** #recon #exploitation - Azure AD exploration framework
- **CloudSploit** #recon #exploitation - Cloud security scanner
- **Steampipe** #recon #actions_on_objectives - Cloud asset inventory

## Mobile Application Testing

- **apktool** #recon #weaponization - Android APK reverse engineering
- **jadx** #recon #weaponization - Android dex decompiler
- **MobSF** #recon #exploitation - Mobile security framework
- **drozer** #exploitation - Android security testing framework
- **class-dump** #recon #exploitation - Objective-C class dumper
- **Hopper** #recon #exploitation - iOS binary analysis
- **iProxy** #exploitation - iOS app analysis proxy

## Container Security

- **docker-bench-security** #recon #exploitation - Docker security benchmark
- **clair** #recon #exploitation - Container vulnerability scanner
- **trivy** #recon #exploitation - Container vulnerability scanner
- **kube-bench** #recon #exploitation - Kubernetes security benchmark
- **kubescape** #recon #exploitation - Kubernetes security scanner
- **kubectl** #exploitation - Kubernetes command-line tool

## Hardware and Firmware Analysis

- **binwalk** #recon #weaponization - Firmware analysis tool
- **firmware-mod-kit** #weaponization - Firmware modification toolkit
- **FACT** #recon #actions_on_objectives - Firmware analysis and comparison tool
- **Bus Pirate** #recon #exploitation - Hardware analysis tool
- **Logic Analyzer** #recon - Digital signal analysis
- **JTAG** #exploitation - Hardware debugging interface

## Reporting and Documentation

- **Dradis** #actions_on_objectives - Information sharing platform
- **Faraday** #actions_on_objectives - Collaborative penetration testing
- **Serpico** #actions_on_objectives - Penetration testing report generator
- **PlexTrac** #actions_on_objectives - Security reporting platform
- **CherryTree** #actions_on_objectives - Hierarchical note-taking
- **Obsidian** #actions_on_objectives - Knowledge management
- **Joplin** #actions_on_objectives - Note-taking application

## Anti-Forensics and Cleanup

- **wipe** #actions_on_objectives - Secure file deletion
- **shred** #actions_on_objectives - Secure file deletion
- **zerofree** #actions_on_objectives - Zero free disk space

## Encoding/Decoding Utilities

- **base64** #actions_on_objectives - Base64 encoding/decoding
- **xxd** #actions_on_objectives - Hex dump utility
- **hexdump** #actions_on_objectives - Hex dump utility

## Development and Scripting

- **PowerShell** #weaponization #exploitation - Windows scripting language
- **Python** #weaponization #exploitation - Programming language (many tools written in Python)
- **Ruby** #weaponization #exploitation - Programming language (Metasploit is Ruby-based)
- **Bash** #weaponization #exploitation - Unix shell scripting

## Security Testing Platforms and Distributions

- **Kali Linux** - Debian-based penetration testing distribution
- **Parrot Security OS** - Debian-based security distribution
- **BlackArch Linux** - Arch-based penetration testing distribution
- **BackBox** - Ubuntu-based penetration testing distribution
- **Pentoo** - Gentoo-based penetration testing distribution
- **Pentesters Framework (PTF)** - Penetration testing framework by TrustedSec