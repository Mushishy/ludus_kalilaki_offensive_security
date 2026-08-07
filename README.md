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

## Configuration

```yaml
disable_kasmvnc: false
additional_install: []
configure_git: false
git_user_name: ""
git_user_email: ""
copy_files: false
```

## Example

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
      - name: badsectorlabs.ludus_elastic_agent
    role_vars: 
        copy_files: false
        additional_install:
            - kali-tools-web
```

## License

MIT