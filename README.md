## build
apt install debhelper
apt install dh-systemd
dpkg-buildpackage -us -uc

## notes
1. debian/control
2. debian/*.install
3. debian/rules
4. debian/*.services
