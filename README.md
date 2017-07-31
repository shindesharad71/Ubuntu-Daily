<p align="center">
  <img src="https://github.com/shindesharad71/Ubuntu-Daily/blob/master/inc/ubuntu.png?raw=true" alt="Ubuntu logo"/>
</p>

# Ubuntu Daily

A Daily Use Guide For Debian Based OS Ubuntu.

## Table of Contents
  1. [Ubuntu Version Selection](#1-ubuntu-version-selection) 
  2. [Initial Setup and To-Do](#2-initial-setup-and-to-do)  
    2.1. [Update and Upgrade](#21-update-and-upgrade)  
    2.2. [Installing Packages](#22-installing-packages)  
    2.3. [Uninstalling Packages](#23-unistalling-packages)


# 1. Ubuntu Version Selection
For the best performance and stablality of system you should install ```LTS``` (**L**ong **T**erm **S**upport) version of Ubuntu. I would recommand to install Ubuntu 16.04. This tutorial is tested on Ubuntu 16.04 and I am also using same version of Ununtu.

# 2. Initial Setup and To-Do

The following things to do after installing new Ubuntu - 

### 2.1 ```Update and Upgrade```

After completing installation process first task is to update your system, so it will fix the security issues and bugs. Updating system frequently is best and it helps to improve stablality of your system and iprove the security levels.

Update your system by running this command in the terminal -
```bash
sudo apt-get update && sudo apt update
```
After this run the upgrade command

```bash
sudo apt-get upgrade && sudo apt upgrade
```

### 2.2 ```Installing Packages```

After updating system you need to install packages for your daily use. The procedure to install different packages is pretty simple.
```bash
sudo apt install <package-name>
```
this command is used to install packages.

### 2.3 ```Unistalling Packages```

To unistall certain package from your system use following command - 
```bash
sudo apt autoremove <package-name>
```
this command will remove given packages and its dependencies.