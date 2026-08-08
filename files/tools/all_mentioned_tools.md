# All Tools Mentioned in Penetration Testing Documents
*Organized by testing domains with kill chain phase tags*

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
- **hping3** #recon #exploitation - Packet crafting and active network probing utility

## Network Traffic Analysis

- **wireshark** #recon #exploitation - Network protocol analyzer
- **tcpdump** #recon #exploitation - Command-line packet analyzer
- **tshark** #recon #exploitation - Command-line Wireshark packet analysis utility
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
- **Rapid7 InsightVM** #recon #exploitation - Vulnerability management and assessment platform

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
- **dnsspoof** #exploitation - DNS spoofing and response forgery utility

## Web Application Testing

- **gobuster** #recon #exploitation - Directory and file brute-forcer
- **ffuf** #recon #exploitation - Fast web fuzzer
- **wfuzz** #recon #exploitation - Web application fuzzer
- **dirb** #recon #exploitation - Web content scanner
- **dirbuster** #recon #exploitation - Directory and filename brute-forcer
- **dirsearch** #recon #exploitation - Web path and file brute-force scanner
- **Burp Suite** #recon #exploitation - Web application security testing platform
- **OWASP ZAP** #recon #exploitation - Web application security scanner
- **nikto** #recon #exploitation - Web vulnerability scanner
- **w3af** #exploitation - Web application attack and audit framework
- **skipfish** #recon - Web application reconnaissance tool
- **whatweb** #recon - Web technology fingerprinting tool
- **wappalyzer** #recon - Technology profiler (browser extension)
- **sqlmap** #exploitation - SQL injection testing tool
- **XSStrike** #exploitation - XSS detection suite
- **Commix** #exploitation - Command injection exploiter
- **wpscan** #recon #exploitation - WordPress vulnerability scanner
- **droopescan** #recon #exploitation - Drupal vulnerability scanner (orphaned)
- **joomscan** #recon #exploitation - Joomla vulnerability scanner
- **testssl.sh** #recon #exploitation - SSL/TLS configuration checker
- **BoidCMS** #recon #exploitation - Web CMS platform often fingerprinted and targeted during web assessments

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
- **SharpLDAPSearch** #recon #exploitation - LDAP enumeration utility for Active Directory
- **NetExec** #recon #exploitation - Successor to CrackMapExec for AD/network enumeration and command execution
- **Inveigh** #exploitation #credential_access - LLMNR/NBNS spoofing and NTLM credential capture/relay tool
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
- **Proxmark3 RDV4** #delivery #physical_security - RFID/NFC research and emulation platform
- **O.MG Cable** #delivery #physical_security - Covert USB cable payload delivery platform
- **LAN Turtle** #delivery #physical_security - USB Ethernet attack and persistence implant
- **iCopy-XS** #delivery #physical_security - Portable RFID/NFC cloning and testing device
- **Bash Bunny** #delivery #physical_security - USB attack platform for scripted payload delivery

## Social Engineering

- **Social Engineer Toolkit (SET)** #delivery - Social engineering framework
- **setoolkit** #delivery - Command alias/binary name commonly used for the Social Engineer Toolkit
- **Gophish** #delivery - Phishing campaign toolkit
- **King Phisher** #delivery - Phishing campaign toolkit

## OSINT/Information Gathering

- **theharvester** #recon - Email and subdomain harvester
- **recon-ng** #recon - Web reconnaissance framework
- **Maltego** #recon - Link analysis and data visualization
- **spiderfoot** #recon - OSINT automation tool
- **Shodan** #recon - Internet-connected device search engine
- **Censys** #recon - Internet asset discovery and exposure search platform
- **Netcraft** #recon - Internet infrastructure, hosting, and phishing intelligence lookup platform
- **BuiltWith** #recon - Web technology profiling and stack intelligence platform
- **Hunter.io** #recon - Email pattern discovery and contact intelligence platform
- **Have I Been Pwned** #recon #threat_intelligence - Breach exposure and compromised account lookup service
- **crt.sh** #recon - Certificate Transparency log search interface
- **UrlScan.io** #recon #threat_intelligence - URL and domain scanning intelligence platform
- **MalwareBazaar (bazaar.abuse.ch)** #threat_intelligence #malware_analysis - Malware sample and indicator sharing repository
- **SimplyEmail** #recon - Email reconnaissance tool
- **Metagoofil** #recon - Metadata extraction tool
- **sherlock** #recon - Social media username checker
- **social-analyzer** #recon - Social media analysis tool
- **exiftool** #recon - Metadata extraction tool
- **FOCA** #recon - Document metadata analysis
- **LeakCheck** #recon - Credential leak lookup and breach intelligence platform
- **DeHashed** #recon - Breach and leaked credential search platform
- **AbuseIPDB** #recon #threat_intelligence - IP reputation and abuse reporting platform

## Exploitation Frameworks

- **Metasploit Framework** #exploitation - Penetration testing framework
- **Metasploit Pro** #exploitation - Commercial version of Metasploit
- **msfconsole** #exploitation - Metasploit console interface
- **Armitage** #exploitation - GUI for Metasploit
- **Cobalt Strike** #exploitation #command_and_control - Commercial penetration testing platform
- **Empire** #command_and_control - Post-exploitation framework
- **Covenant** #command_and_control - .NET command and control framework
- **Mythic** #command_and_control - Open-source command-and-control framework
- **Adaptix Framework** #command_and_control - Red team command-and-control framework

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
- **winPEAS** #installation - Windows privilege escalation script
- **adPEAS** #installation - Active Directory privilege escalation enumeration script
- **LinEnum** #installation - Linux privilege escalation and host enumeration script
- **linux-exploit-suggester** #installation - Linux exploit suggester
- **windows-exploit-suggester** #installation - Windows exploit suggester
- **pspy** #installation - Linux process monitor
- **pspy64** #installation - 64-bit Linux process monitoring binary
- **GTFOBins** #installation - Unix binaries privilege escalation
- **LOLBAS** #installation - Living Off The Land Binaries and Scripts
- **mimikatz** #installation #actions_on_objectives - Windows credential extractor
- **pypykatz** #installation #actions_on_objectives - Python-based parser for credential extraction and LSASS artifacts
- **LaZagne** #installation #actions_on_objectives - Credential harvesting tool
- **secretsdump.py** #installation #actions_on_objectives - Credential dumper
- **lsassy** #installation #actions_on_objectives - LSASS memory extractor
- **impacket** #exploitation #command_and_control - Python network protocols library
- **PowerSploit** #installation #exploitation - PowerShell offensive framework for privilege escalation and post-exploitation
- **Seatbelt** #recon #post_exploitation - Windows host situational awareness and triage tool
- **SharpUp** #recon #post_exploitation - Windows privilege escalation auditing tool
- **PowerUp** #recon #post_exploitation - PowerShell privilege escalation module from PowerSploit
- **PrintSpoofer** #privilege_escalation #exploitation - Local privilege escalation tool abusing SeImpersonate privileges
- **SharpCollection** #actions_on_objectives #post_exploitation - Curated collection of offensive .NET utilities used in operations
- **pdb** #post_exploitation #development - Python interactive debugger that can be abused when reachable through privileged script error paths
- **tar** #post_exploitation #privilege_escalation - Native archiving utility frequently abused for privilege escalation via GTFOBins techniques

## Native OS Enumeration Utilities

- **whoami.exe** #recon #post_exploitation - Native Windows identity and privilege enumeration command
- **cmd.exe** #recon #post_exploitation - Native Windows command interpreter used for execution and triage
- **systeminfo.exe** #recon #post_exploitation - Native Windows host and patch/system information command
- **icacls.exe** #recon #post_exploitation - Native Windows file and ACL permission inspection utility
- **sc.exe** #recon #post_exploitation - Native Windows service control/query utility
- **tasklist.exe** #recon #post_exploitation - Native Windows process listing utility
- **wmic.exe** #recon #post_exploitation - Native WMI command-line interface for software, patch, and system queries
- **netsh.exe** #recon #post_exploitation - Native Windows network and firewall configuration/query utility
- **schtasks.exe** #recon #post_exploitation - Native Windows scheduled task query and management utility
- **driverquery.exe** #recon #post_exploitation - Native Windows driver inventory and metadata query utility
- **sfc /scannow** #endpoint_recovery #integrity - Native Windows system file integrity verification and repair command
- **WmiPrvSE.exe** #forensics #endpoint_monitoring - Windows Management Instrumentation host process frequently reviewed during investigations
- **Get-ComputerInfo** #recon #post_exploitation - PowerShell cmdlet for host inventory and OS metadata
- **Get-LocalUser** #recon #post_exploitation - PowerShell cmdlet for local user account enumeration
- **Get-LocalGroup** #recon #post_exploitation - PowerShell cmdlet for local group enumeration
- **Get-Process** #recon #post_exploitation - PowerShell cmdlet for process enumeration
- **Start-Process** #exploitation #post_exploitation - PowerShell cmdlet for process and payload execution
- **IEX (Invoke-Expression)** #exploitation #post_exploitation - PowerShell command execution primitive often used for in-memory execution
- **Get-WMIObject** #recon #post_exploitation - PowerShell cmdlet for WMI-based host/service/query enumeration
- **ss** #recon #post_exploitation - Native Linux socket and listening-service enumeration utility
- **systemctl** #recon #post_exploitation - systemd service status and management utility used during host/service triage

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
- **httprobe** #recon - HTTP/HTTPS probing utility for discovered hosts and subdomains
- **screen** #command_and_control - Terminal multiplexer
- **tmux** #command_and_control - Terminal multiplexer

## File Transfer and Delivery

- **curl** #delivery #recon - Command-line HTTP client
- **wget** #delivery #recon - File downloader
- **python3 -m http.server** #delivery - Simple HTTP server
- **scp** #delivery - Secure copy
- **rsync** #delivery - File synchronization
- **rclone** #delivery #exfiltration - Data synchronization and exfiltration tool
- **mutt** #delivery - Command-line email client used for sending payloads or test messages

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
- **adb (Android Debug Bridge)** #recon #exploitation - Android device interaction and shell access tool
- **class-dump** #recon #exploitation - Objective-C class dumper
- **Hopper** #recon #exploitation - iOS binary analysis
- **iProxy** #exploitation - iOS app analysis proxy

## Reverse Engineering and Binary Analysis

- **IDA** #recon #exploitation - Interactive disassembler and reverse engineering platform
- **dnSpy (dnSpy-net-win32, dnSpy-net-win64)** #recon #exploitation - .NET assembly debugger and decompiler
- **ILSpy (ILSpy_binaries_7.1.0.6543)** #recon #exploitation - .NET assembly decompiler
- **de4dot** #recon #exploitation - .NET deobfuscation utility
- **CFF Explorer (CFF_Explorer)** #recon #exploitation - PE file structure analysis and editing tool
- **DIE (Detect It Easy, die)** #recon #analysis - Binary packer/compiler/signature detection tool
- **UPX (upx-4.1.0-win32)** #weaponization #evasion - Executable packer and compressor
- **FAR Manager (Far)** #actions_on_objectives - File and archive manager used in reverse engineering workflows

## Container Security

- **docker-bench-security** #recon #exploitation - Docker security benchmark
- **clair** #recon #exploitation - Container vulnerability scanner
- **trivy** #recon #exploitation - Container vulnerability scanner
- **kube-bench** #recon #exploitation - Kubernetes security benchmark
- **kubescape** #recon #exploitation - Kubernetes security scanner
- **kubectl** #exploitation - Kubernetes command-line tool
- **Docker Scout** #recon #vulnerability_management - Container image vulnerability and supply-chain analysis tool
- **seccomp** #container_security #hardening - Linux syscall filtering framework used to constrain container behavior
- **AppArmor** #container_security #hardening - Mandatory access control framework for process and container confinement
- **no-new-privileges** #container_security #hardening - Kernel process flag that blocks privilege escalation through exec transitions

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
- **Ansible** #operations #hardening - Automation framework used for repeatable system hardening and remediation playbooks
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
- **gcc** #weaponization #development - GNU compiler collection used to build native payloads and shared objects
- **LD_PRELOAD** #evasion #development - Dynamic linker preload mechanism commonly abused for process hijacking and function hooking

## Security Testing Platforms and Distributions

- **Kali Linux** - Debian-based penetration testing distribution
- **Parrot Security OS** - Debian-based security distribution
- **BlackArch Linux** - Arch-based penetration testing distribution
- **BackBox** - Ubuntu-based penetration testing distribution
- **Pentoo** - Gentoo-based penetration testing distribution
- **DragonOS** - Security-focused distribution for RF, SDR, and wireless assessments
- **Pentesters Framework (PTF)** - Penetration testing framework by TrustedSec

## Blue Team / Defensive Security Tools

- **osquery** #detection #endpoint_monitoring - Endpoint visibility and live query tool
- **Velociraptor** #detection #forensics #threat_hunting - Endpoint collection and hunting platform
- **OSSEC** #hids #detection - Host-based intrusion detection system
- **Wazuh** #siem #detection #log_analysis - Open-source XDR/SIEM and host-based security monitoring
- **Security Onion** #siem #ids #network_detection - Network security monitoring distribution with integrated tools
- **Arkime** #nsm #packet_analysis - Full packet capture indexing and hunting platform
- **Splunk** #siem #detection #log_analysis - Enterprise SIEM and log analytics platform
- **Elastic Stack** #siem #detection #log_analysis - Elasticsearch, Kibana, Beats, and Logstash for security analytics
- **Elastic Security X-Pack** #siem #detection #rule_engine - Elastic security module with built-in detection content and ruleing engine
- **Elastic Agent** #siem #telemetry - Unified endpoint and log collection agent for Elastic
- **Filebeat** #siem #log_collection - Lightweight log shipper for Elasticsearch and Logstash
- **Winlogbeat** #detection #telemetry - Windows event log shipping agent for Elasticsearch/Logstash
- **Suricata** #ids #network_detection - Network intrusion detection and security monitoring engine
- **suricata-update** #ids #rule_management - Rule source and update management utility for Suricata
- **ET Pro** #ids #rule_management - Emerging Threats Pro commercial Suricata/Snort ruleset
- **Zeek** #network_detection #nsm - Network security monitoring and protocol analysis platform
- **Sguil** #incident_response #nsm - Analyst console for network security monitoring events
- **Squert** #incident_response #nsm - Web interface for querying and reviewing NSM alerts
- **YARA** #malware_analysis #detection - Pattern-based malware and file classification engine
- **Sigma** #detection #rule_engine - Generic rule format for SIEM and log-based detections
- **Sysmon** #detection #endpoint_monitoring - Windows system monitor for detailed process and network telemetry
- **Sysinternals** #forensics #endpoint_monitoring - Windows troubleshooting and monitoring utilities
- **Process Monitor (Procmon)** #forensics #endpoint_monitoring - Sysinternals real-time process, registry, and file activity monitor
- **Process Explorer (ProcExp)** #forensics #endpoint_monitoring - Sysinternals advanced process and handle inspection tool
- **Process Hacker** #forensics #endpoint_monitoring - Advanced process, handle, and memory inspection utility
- **ProcDump** #forensics #acquisition - Sysinternals process dump capture utility for troubleshooting and malware analysis
- **Sigcheck** #forensics #integrity - Sysinternals signature and file metadata verification utility
- **Streams** #forensics #file_analysis - Sysinternals alternate data stream inspection utility
- **SDelete** #forensics #secure_deletion - Sysinternals secure deletion utility
- **TCPView** #network_detection #endpoint_monitoring - Sysinternals network connection monitoring utility
- **Autoruns** #forensics #persistence_detection - Sysinternals autostart location inspection utility
- **WinObj** #forensics #endpoint_monitoring - Sysinternals Windows Object Manager namespace viewer
- **BGInfo** #operations #endpoint_visibility - Sysinternals desktop information display utility
- **RegJump** #forensics #registry_analysis - Sysinternals fast registry navigation utility
- **Strings** #forensics #analysis - Sysinternals printable string extraction utility for binaries and files
- **Volatility 3** #forensics #memory_forensics - Memory forensics and incident response analysis framework
- **FTK Imager** #forensics #acquisition - Evidence imaging and preview tool
- **Redline** #forensics #endpoint_analysis - Endpoint memory and host investigation tool
- **DumpIt** #forensics #memory_acquisition - Lightweight memory acquisition utility
- **win32dd / win64dd** #forensics #memory_acquisition - Windows physical memory dumping tools
- **Memoryze** #forensics #memory_forensics - Memory analysis and malware triage tool
- **FastDump** #forensics #memory_acquisition - Fast memory acquisition utility
- **WinPmem** #forensics #memory_acquisition - Physical memory acquisition utility for Windows systems
- **The Sleuth Kit** #forensics #disk_forensics - Command-line digital forensics and filesystem analysis toolkit
- **libewf (ewfmount / ewfverify)** #forensics #disk_forensics - EWF evidence image mounting and verification tools
- **CyberChef** #forensics #analysis - Data decoding, encoding, and transformation workbench
- **7-Zip** #forensics #analysis - Archive extraction and file inspection utility used in forensic workflows
- **VirusTotal** #threat_intelligence #malware_analysis - Malware and indicator reputation analysis platform
- **ANY.RUN** #malware_analysis #sandboxing - Interactive malware detonation and behavior analysis sandbox
- **MetaDefender** #malware_analysis #file_scanning - Multi-engine file and URL malware scanning platform
- **zsteg** #forensics #steganography - PNG/BMP steganography detection and extraction tool
- **IRIS CM** #incident_response #case_management - Incident response case management platform
- **Zabbix** #monitoring #detection - Infrastructure and service monitoring platform used for security visibility
- **CRISPY** #monitoring #agent_monitoring - Agent-based monitoring and management platform
- **RMMS** #monitoring #agent_monitoring - Remote monitoring and management software class
- **Bstrike / BlackStrike** #threat_hunting #suspicious_tooling - Potentially dangerous tooling monitored during defensive operations
- **Atomic Red Team** #threat_emulation #detection_validation - Adversary emulation tests mapped to ATT&CK techniques
- **MITRE Caldera** #threat_emulation #purple_teaming - Automated adversary emulation and operation orchestration platform
- **FlareVM** #malware_analysis #reverse_engineering - Windows-based malware analysis virtual machine environment
- **auditd** #linux_security #logging - Linux audit daemon for system call and security event logging
- **Neo23x0 Auditd Rules** #linux_security #logging - Community baseline auditd ruleset for host audit coverage
- **debsums** #linux_security #integrity - Package file integrity verification tool for Debian/Ubuntu systems
- **journalctl** #linux_security #logging - systemd journal log query and investigation utility
- **syslog-ng** #linux_security #logging - Centralized log collection and forwarding daemon
- **Fail2Ban** #host_security #blocking - Brute-force prevention and login protection tool
- **ClamAV** #malware_detection #endpoint_security - Antivirus engine for malware scanning
- **ESET** #malware_detection #endpoint_security - Commercial antivirus and endpoint protection platform
- **Lynis** #linux_security #auditing - Security auditing and hardening assessment tool for Unix-like systems
- **debsecan** #vulnerability_management #linux_security - Debian/Ubuntu package vulnerability scanner
- **rkhunter** #rootkit_detection #host_security - Rootkit detection tool for Unix systems
- **chkrootkit** #rootkit_detection #host_security - Rootkit check utility for Unix systems
- **Microsoft Defender for Endpoint** #edr #endpoint_security - Enterprise endpoint detection and response platform
- **CrowdStrike Falcon** #edr #endpoint_security - Cloud-native endpoint protection and detection platform
- **SentinelOne** #edr #endpoint_security - Autonomous endpoint detection and response platform
- **GRR Rapid Response** #incident_response #forensics - Remote live forensics and incident response framework
- **MISP** #threat_intelligence #intel - Threat intelligence sharing and indicator management platform
- **Group Policy Management Editor** #endpoint_hardening #policy_management - Windows policy management console for enforcing security baselines
- **gpupdate** #endpoint_hardening #policy_management - Command-line utility to force Group Policy refresh on Windows hosts
- **uBlock Origin** #endpoint_hardening #web_security - Browser extension used to reduce malicious/advertising/tracker exposure
- **FortiClient VPN** #operations #remote_access - Fortinet remote access VPN client used for secure connectivity
- **Cisco AnyConnect** #operations #remote_access - Cisco remote access VPN client for enterprise connectivity
- **Winbox64** #operations #network_admin - MikroTik RouterOS administration client
- **Cisco Packet Tracer** #operations #network_training - Network simulation and lab tool for routing and switching practice