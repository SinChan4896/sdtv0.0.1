How to download Chocolatey in Windows
=====================================

#. open PowerShell as admin |

#. paste the whole text and press enter::
    Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
|
#. then type ``choco install make`` to install make console.