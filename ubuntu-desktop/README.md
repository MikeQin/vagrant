# Ubuntu Desktop 18.04.4

Link: https://app.vagrantup.com/action-test/boxes/ubuntu-18.04-desktop-amd64

## VM Includes

- Basic Linux Packages
- Docker
- Docker Compose
- Node & NPM
- Open JDK 8
- Jenkins

## Vagrant Commands

```bash
# vagrant init action-test/ubuntu-18.04-desktop-amd64 \
#   --box-version 20200218.05

# To start VM
vagrant up

# To stop VM 
vagrant halt

# SSH
vagrant ssh

# VM Credential
user: vagrant
password: vagrant
```