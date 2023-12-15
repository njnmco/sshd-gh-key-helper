# sshd Github Key Helper

A Debian package which configures sshd to automatically pull keys from github.


### Build:

```
fakeroot dpkg-deb --build pkg sshd-gh-key-helper.deb
```

### Install:

```
sudo dpkg -i sshd-gh-key-helper.deb
```

### References

* https://gist.github.com/sivel/c68f601137ef9063efd7
* https://tldp.org/HOWTO/html_single/Debian-Binary-Package-Building-HOWTO/
* https://www.debian.org/doc/debian-policy/ch-maintainerscripts.html
