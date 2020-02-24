# PPA

### Import GPG-key:
```
wget -O - https://pw512.github.io/ppa/KEY.gpg | sudo apt-key add -
```

### Add repo Ubuntu 16.04:
```
wget -O - https://pw512.github.io/ppa/ubuntu/dist/xenial/pw512.list > /etc/apt/sources.list.d/pw512.list
apt update
```
