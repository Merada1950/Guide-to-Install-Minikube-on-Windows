# Before installing Minikube on Windows, ensure the following prerequisites are met:

## Operating System: Windows 10/11 (64-bit) with the latest updates.

## Hardware Requirements:

* 2 CPUs or more.
* 2GB of free memory or more.
* 20GB of free disk space.
* VT-x/AMD-v virtualization enabled in the BIOS.
* Software Requirements:

* Container/Virtualization Software: Choose either Docker, Hyper-V, or VirtualBox as your driver.

* Docker Desktop: If you have Docker Desktop installed, it will work as the container runtime for Minikube.

* Hyper-V: Ensure Hyper-V is enabled if you want to use it.

* VirtualBox: Alternatively, you can use VirtualBox.

* Windows Subsystem for Linux (WSL 2): (Optional but recommended)

* Install and set up WSL 2 to enable better performance and a more Linux-like experience on Windows.

* Ensure the Virtual Machine Platform is enabled in Windows features.

# Install Dependencies:

### Install Chocolatey Package Manager (Optional): If you don't have Chocolatey installed, you can install it to simplify package management:

## Open PowerShell as an administrator and run:
* Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))

## Verify Chocolatey is installed:
* choco --version

## Install Docker Desktop:
* Download Docker Desktop from Docker's official website [[https://docs.docker.com/desktop/install/windows-install/]].
* Install it and ensure Docker Desktop is running.
