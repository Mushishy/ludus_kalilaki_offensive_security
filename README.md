# Ludus Ansible Role: Kalilaki Offensive Security

Ansible role for automated Kali Linux setup and configuration.

## Features

**Languages & Frameworks:** Python 3, Go, C/C++, C# (Mono), PowerShell

**Tool Packages:**
- kali-tools-information-gathering
- kali-tools-vulnerability
- kali-tools-web
- kali-tools-database
- kali-tools-passwords
- kali-tools-wireless
- kali-tools-reverse-engineering
- kali-tools-exploitation
- kali-tools-social-engineering
- kali-tools-sniffing-spoofing
- kali-tools-post-exploitation
- kali-tools-forensics
- kali-tools-reporting

## Example Ludus Range Config

```yaml
ludus:
  - vm_name: "{{ range_id }}-kali"
    hostname: "{{ range_id }}-kali"
    template: kali-x64-desktop-template
    vlan: 20
    ip_last_octet: 10
    ram_gb: 8
    cpus: 4
    linux: true
    testing:
      snapshot: false
      block_internet: false
    roles:                 
      - name: ludus_kalilaki_offensive_security 
    role_vars: 
        ludus_copy_files: true
        ludus_disable_kasmvnc: true
        ludus_additional_install:
            - kali-tools-web
        ludus_configure_git: true 
        ludus_git_user_name: "Mushishy"
        ludus_git_user_email: "mushishy@local.local"
```

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`).

```yaml
# KasmVNC Control
ludus_disable_kasmvnc: false

# Additional Packages
ludus_additional_install: []

# Git Configuration
ludus_configure_git: false
ludus_git_user_name: ""
ludus_git_user_email: ""

# Customization
# Customization
ludus_copy_files: false
```

## License

GPLv3