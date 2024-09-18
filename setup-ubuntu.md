# Ubuntu WSL Set-Up Tutorial for Windows

## What you will need beforehand: 
- Windows 10/11 on virutal or physical machine
- Windows updated to most recent version

**1. Installing WSL2**
- The first step to installing Ubuntu on your machine is installing WSL2 on your computer. WSL2 stands for Windows Subsystem for Linux, and it allows you to run a Linux environment on your computer without having to have a separate virtual machine.
- To install WSL2, you have to open Windows Terminal on your device as an adminstrator. Then enter <code> wsl --install </code>. 
- Once it has installed, you must restart your device.
  
**2. Installing Ubuntu**
The second step for installing Ubuntu is installing a version of Ubuntu onto WSL. We will be using a method that allows you to install Ubuntu from the command line. 
- First, you must open Windows Terminal and enter <code> wsl --list --online </code> to see on the available versions of Ubuntu that you are able to install.
- Once you have found the version that you like, you must type the name of the version that you want and then enter the following: <code> wsl --install -d (name of installation)
- If successful, you will see a progress bar appear showing that the installation is in progress.

**3. Running Ubuntu**
The final step for installing Ubuntu is running it on your machine and making sure it is functional. 
- To do that, you must open Powershell terminal and type in the version of Ubuntu you installed, for example: <code> ubuntu2404.exe </code>
- The Ubuntu terminal should start running, and if it has, then you have successfully installed Ubuntu!
- Once it is installed, the system will prompt you to create a username and password. Make sure to write the username and password somewhere secure so then if you forget your information, you are able to retrieve it.
- Optionally, you should also run updates for your Ubuntu terminal to make sure that it is up to date. You can run updates by entering the following:
<code> sudo apt update </code>
<code> sudo apt full-upgrade -y </code>
- It will prompt you to enter your password for the updates.

## After following these steps, you should have a fully functional Ubuntu system on your machine!

