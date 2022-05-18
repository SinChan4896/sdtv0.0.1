How to download Chocolatey in Windows
=====================================

Open ``PowerShell`` as admin.
Paste the whole text and press enter::
    Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))

Type ``choco install make`` to install make console.