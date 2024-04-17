# Setup de programas frequentemente usados no windows

## Instalar chocolatey

obs: abrir powershell como admnistrador

```powershell
Set-ExecutionPolicy AllSigned

Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

## Programas para instalar com chocolatey
```powershell
choco install spotify
choco install vscode
choco install python3
choco install git
choco install autohotkey
```
