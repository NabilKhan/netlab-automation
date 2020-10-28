# cumulus-vxlan-evpn

In this lab, we will create a Spine-Leaf topology based on Nvidia/Cumulus VX. We will use a VXLAN Overlay with EVPN as the control plane to distribute MAC Addresses in our Fabric.

The idea of the lab is to learn about VXLAN/EVPN while automating the deployment of the fabric as much as possible.

## Topology

The basic topology is shown below.
![print table](../resources/net_lab1_logical.png)

## Requirements

- [Virtualbox](https://www.virtualbox.org/wiki/Downloads)
  - For macOS:
    - Download and install [Virtualbox](https://www.virtualbox.org/wiki/Downloads)
  - For Windows:
    - You must ensure that Hyper-V is not enabled on Windows. [Disabling Hyper-V on Windows 10](https://docs.microsoft.com/en-us/troubleshoot/windows-client/application-management/virtualization-apps-not-work-with-hyper-v#resolution)
    - Download and install [Virtualbox](https://www.virtualbox.org/wiki/Downloads)
- [Vagrant](https://www.vagrantup.com/docs/installation)
  - For macOS:
    - Open your terminal
    - Install Hombrew `/bin/bash -c "$(curl -fsSL`
    - Install Virtualbox with homembrew-cask `brew cask install virtualbox`
    - Install Vagrant with homembrew-cask `brew cask install vagrant`
  - For Windows:
    - Download and install [Vagrant](https://www.vagrantup.com/docs/installation)

## How do I start?

- Run this command inside the current folder: `vagrant up`