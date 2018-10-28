# fish-shell-Openwrt
Crosscompiled fish shell for OpenWrt.

## Usage

```
cp <arch>/bin/* /bin
cp -r <arch>/etc/fish /etc
mkdir /share
cp -r <arch>/share/* /share
ln -s /usr/share/terminfo ~/.terminfo
fish
```

