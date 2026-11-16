# Blind OS updates

This repository holds only the signed package repository that Blind OS installs
update from (the `apt` release). There is no source code here.

Every Blind OS install already trusts this source:

```
Types: deb
URIs: https://github.com/Blind-os/updates/releases/download/apt/
Suites: ./
Signed-By: /usr/share/keyrings/blind-os-archive-keyring.gpg
```

Packages are signed with the Blind OS archive key
`BA8E DE40 4F35 696C 7B75  C280 DB06 EAF3 1412 5918`;
apt refuses anything not signed by it. The public key is attached to the `apt` release.
