# Vagrant

To create Ubuntu 18.04.3:
- [Ubuntu Desktop](ubuntu-desktop/README.md)
- [Ubuntu Server](ubuntu-server/README.md)

```bash
# Init
vagrant init

# Then go to file: ~/.vagrant.d\boxes\peru-VAGRANTSLASH-ubuntu-18.04-server-amd64\20200207.01\virtualbox
# Remove line 31: 
virtualbox.customize ["modifyvm", :id, "--clipboard-mode", "bidirectional"]

# To start VM
vagrant up
```