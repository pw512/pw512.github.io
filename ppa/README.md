# PPA

### Import GPG-key:
```
wget -qO - https://pw512.github.io/ppa/KEY.gpg | sudo apt-key add -
```

### Add repo Ubuntu 16.04:
```
wget -qO - https://pw512.github.io/ppa/crypto-pack/ubuntu/xenial/crypto-pack.list > /etc/apt/sources.list.d/crypto-pack.list
apt update
```
