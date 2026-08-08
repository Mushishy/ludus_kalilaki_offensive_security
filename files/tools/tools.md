## These tools are in tools.zip
Akagi64.exe         mimikatz.exe    rclone.exe                  Seatbelt.exe    SharpLDAPSearch.exe  SweetPotato.exe
AnyDesk.exe         PowerView.ps1   reverse_shell_template.ps1  SharpHound.exe  SharpUp.exe          Token-Impersonation.ps1
CredentialKatz.exe  procdump64.exe  Rubeus.exe                  SharpHound.ps1  SharpView.exe

## To use pyenv use 

```bash
pyenv install 3.12
~/.pyenv/versions/3.12.*/bin/python3 -m venv my_env
source my_env/bin/activate
```

## This is how you can use cmake to build

```bash
cmake -B build -S . && cmake --build build
```