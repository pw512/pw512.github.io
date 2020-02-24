# PPA

### Import GPG-key:
```
wget -qO - https://pw512.github.io/ppa/KEY.gpg | sudo apt-key add -
```

### Add repo Ubuntu 16.04:
```
wget -qO - https://pw512.github.io/ppa/ubuntu/xenial/pw512.list > /etc/apt/sources.list.d/pw512.list
apt update
```
