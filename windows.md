# Setup do windows para programar

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
choco install autohotkey.portable --version=2.0.2
choco install sublimetext3
```

## Script de atalhos do autohotkey
```autohotkey
#Requires AutoHotkey v2.0

; Opens winbox
^!i::
{
    Run "C:\Users\pedro.ramos\Documents\winbox64.exe"
    return
}

; Opens chrome
^!h::
{
    Run "C:\Users\pedro.ramos\AppData\Local\Google\Chrome\Application\chrome.exe"
    return
}

; Opens vscode
^!k::
{
	Run "code"
	return
}

; Opens terminal
^!t::
{
    Run("cmd.exe /k cd C:\\Users\\pedro.ramos")
    return
}
```
