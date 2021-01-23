# Provisioning a Kali Linux virtual machine using Vagrant

Provision a Kali Linux virtual machine, with the goal of reducing setup time for the development environment and speeding up the process.

# Installation

## Requirements

Required:
* VirtualBox
* Vagrant

## Installation Kali Linux

```
git clone https://github.com/SantiagoSilvaZ/kali-linux-vagrant.git
cd kali-linux-vagrant
vagrant up
```

## Accessing Kali Linux

```
vagrant ssh
```

# configuration VM

Network
* mode = "NAT"
* network = "private_network", 
* ip = "192.168.33.10"

VirtualBox specific settings
* memory = "4096"