# Tools from all_mentioned_tools that are not already covered by tools_setup

This file contains only tools from the inventory that are not already represented by the apt packages in the Ansible setup. Each tool appears in one place only.

## Base Kali installation / common default system tools
These are commonly available as part of a standard Kali base image or basic system toolchain.
- netstat
- ipconfig
- arp
- arping
- arpwatch
- ping
- ping6
- traceroute
- tcptraceroute
- nslookup
- dig
- nmblookup
- net
- rpcclient
- tftp
- ncftp
- bluetoothctl
- hcitool
- nc (netcat)
- ncat
- scp
- wipe
- shred
- zerofree
- base64
- xxd
- hexdump

## 0. Basic Tools
- Kali Linux
- Parrot Security OS
- BlackArch Linux
- BackBox
- Pentoo
- Pentesters Framework (PTF)
- Dradis
- Faraday
- Serpico
- PlexTrac
- CherryTree
- Obsidian
- Joplin

## 1. Information Gathering & OSINT
- zenmap
- masscan
- netdiscover
- passive_discovery6
- dmitry
- SubBrute
- enum4linux
- swaks
- smtp-user-enum
- theharvester
- recon-ng
- Maltego
- spiderfoot
- Shodan
- SimplyEmail
- Metagoofil
- sherlock
- social-analyzer
- exiftool
- FOCA

## 2. Vulnerability
- Nessus
- OpenVAS
- Nuclei
- Qualys
- ScoutSuite
- Prowler
- CloudMapper
- Pacu
- PowerZure
- AzureHound
- ROADtools
- CloudSploit
- Steampipe
- docker-bench-security
- clair
- trivy
- kube-bench
- kubescape
- binwalk
- firmware-mod-kit
- FACT
- Bus Pirate
- Logic Analyzer
- JTAG

## 3. Web Application Testing
- OWASP ZAP
- w3af
- wappalyzer
- XSStrike
- Commix
- droopescan
- testssl.sh

## 4. Database Testing
- SQLNinja
- NoSQLMap
- MongoDB tools
- Oracle tools

## 5. Passwords
- medusa
- patator
- hash-identifier
- findmyhash
- crunch
- CeWL

## 6. Reverse Engineering
- apktool
- jadx
- MobSF
- drozer
- class-dump
- Hopper
- iProxy

## 7. Exploitation
- Metasploit Pro
- msfconsole
- Armitage
- Cobalt Strike
- Empire
- Covenant
- msfvenom
- Veil
- Phantom-Evasion
- Shellter
- TheFatRat
- searchsploit
- msf-virustotal
- LinPEAS
- linenum
- winPEAS
- adpeas
- linux-exploit-suggester
- windows-exploit-suggester
- pspy
- GTFOBins
- LOLBAS
- mimikatz
- LaZagne
- secretsdump.py
- lsassy
- impacket
- psexec
- winrm
- crackmapexec
- Invoke-TheHash
- ProxyTunnel
- ligolo-ng
- python3 -m http.server

## 7b. Active Directory
- BloodHound
- SharpHound
- PowerView
- SharpView
- ldapsearch
- ADFind
- Rubeus
- GetUserSPNs.py
- kerbrute

## 8. Sniffing & Spoofing
- p0f
- ettercap
- dsniff
- arpspoof
- dnsspoof
- snmpwalk
- snmp-check
- onesixtyone

## 10. Social Engineering
- USB Rubber Ducky
- Flipper Zero
- Social Engineer Toolkit (SET)
- Gophish
- King Phisher

## 11. Wireless
- aircrack-ng
- airmon-ng
- airodump-ng
- aireplay-ng
- wifiphisher
- airgeddon
- kismet
- WiFi Pineapple
- btscanner
- spooftooph

## 12. Development & Scripting
- PowerShell
- Python
- Ruby
- Bash

## 13. Out of scope / non-role tooling
These are intentionally left out of this role because they are commercial, Windows-only, defensive/blue-team focused, platform-specific, or otherwise outside the current Kali offensive-security scope.
- hping3
- tshark
- Rapid7 InsightVM
- Burp Suite
- dirsearch
- whatweb
- BoidCMS
- SharpLDAPSearch
- Inveigh
- john the ripper
- Proxmark3 RDV4
- O.MG Cable
- LAN Turtle
- iCopy-XS
- Bash Bunny
- setoolkit
- Censys
- Netcraft
- BuiltWith
- Hunter.io
- Have I Been Pwned
- crt.sh
- UrlScan.io
- MalwareBazaar (bazaar.abuse.ch)
- LeakCheck
- DeHashed
- AbuseIPDB
- Mythic
- Adaptix Framework
- pspy64
- pypykatz
- PowerSploit
- Seatbelt
- SharpUp
- PowerUp
- PrintSpoofer
- SharpCollection
- pdb
- tar
- whoami.exe
- cmd.exe
- systeminfo.exe
- icacls.exe
- sc.exe
- tasklist.exe
- wmic.exe
- netsh.exe
- schtasks.exe
- driverquery.exe
- sfc /scannow
- WmiPrvSE.exe
- Get-ComputerInfo
- Get-LocalUser
- Get-LocalGroup
- Get-Process
- Start-Process
- IEX (Invoke-Expression)
- Get-WMIObject
- ss
- systemctl
- httprobe
- screen
- rclone
- mutt
- adb (Android Debug Bridge)
- IDA
- dnSpy (dnSpy-net-win32, dnSpy-net-win64)
- ILSpy (ILSpy_binaries_7.1.0.6543)
- de4dot
- CFF Explorer (CFF_Explorer)
- DIE (Detect It Easy, die)
- UPX (upx-4.1.0-win32)
- FAR Manager (Far)
- Docker Scout
- seccomp
- AppArmor
- no-new-privileges
- Ansible
- gcc
- LD_PRELOAD
- DragonOS
- osquery
- Velociraptor
- OSSEC
- Wazuh
- Security Onion
- Arkime
- Splunk
- Elastic Stack
- Elastic Security X-Pack
- Elastic Agent
- Filebeat
- Winlogbeat
- Suricata
- suricata-update
- ET Pro
- Zeek
- Sguil
- Squert
- YARA
- Sigma
- Sysmon
- Sysinternals
- Process Monitor (Procmon)
- Process Explorer (ProcExp)
- Process Hacker
- ProcDump
- Sigcheck
- Streams
- SDelete
- TCPView
- Autoruns
- WinObj
- BGInfo
- RegJump
- Strings
- Volatility 3
- FTK Imager
- Redline
- DumpIt
- win32dd / win64dd
- Memoryze
- FastDump
- WinPmem
- CyberChef
- VirusTotal
- ANY.RUN
- MetaDefender
- IRIS CM
- Zabbix
- CRISPY
- RMMS
- Bstrike / BlackStrike
- Atomic Red Team
- MITRE Caldera
- FlareVM
- auditd
- Neo23x0 Auditd Rules
- journalctl
- syslog-ng
- Fail2Ban
- ClamAV
- ESET
- Microsoft Defender for Endpoint
- CrowdStrike Falcon
- SentinelOne
- GRR Rapid Response
- MISP
- Group Policy Management Editor
- gpupdate
- uBlock Origin
- FortiClient VPN
- Cisco AnyConnect
- Winbox64
- Cisco Packet Tracer


- The Sleuth Kit
- libewf (ewfmount / ewfverify)


- debsums
- Lynis
- debsecan
- rkhunter
- chkrootkit

- zsteg
