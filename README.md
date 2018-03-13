# Welcome to CxDevSecOps Lab
CxDevSecOps lab is ....

## Get Ready
* [Requirements](#Requirements)
  * [Software](#software)
	* [Hardware](#hardware)
* [Installation](#Installation)
  * [Windows](#windows)

## Requirements

### Software

* [Vagrant](https://www.vagrantup.com/downloads.html)
* [Virtualbox](https://www.virtualbox.org/wiki/Downloads)
* [Ansible](http://docs.ansible.com/ansible/latest/intro_installation.html#installation)

### Hardware
* Atleast 4GB of RAM for the virtual machines.
* 60GB of HDD Space.
* Intel i3 Processor or above.

## Installation

### Windows

1. Installation can be done using [chocolatey](https://chocolatey.org/install) by opening up command prompt  and using the following command.
```bash
@"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"
```

2. Install dependencies using choco

```bash
choco install vagrant virtualbox git -y 
```

