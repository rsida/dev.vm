Vagrant DEV Configuration
=========================

This files is used to configure a development environment using Vagrant support.

Requirements
------------

- [VirtualBox 5+](https://www.virtualbox.org/wiki/Downloads)
- [Vagrant 1.8+](https://www.vagrantup.com/downloads.html)
- [ChefDK - Opscode](https://downloads.chef.io/chef-dk/)
- Berkshelf for Vagrant
- Omnibus for Vagrant
- HostManager for Vagrant

Installation
------------

1. Download and install VirtualBox
2. Download and install Vagrant
3. Download and install ChefDK
4. Adding plugin to Vagrant:
```
    vagrant plugin install vagrant-berkshelf
    vagrant plugin install vagrant-omnibus
    vagrant plugin install vagrant-hostmanager
```
