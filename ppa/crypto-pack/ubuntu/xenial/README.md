### Build release:
```
dpkg-scanpackages --multiversion pool > Packages
gzip -k -f Packages
```

### Sign release:
```
apt-ftparchive release . > Release
gpg --default-key "pw512@ya.ru" --personal-digest-preferences SHA256 -abs -o - Release > Release.gpg
gpg --default-key "pw512@ya.ru" --personal-digest-preferences SHA256 --clearsign -o - Release > InRelease
```
