# fish-shell-Openwrt

Crosscompiled fish shell for OpenWrt.

All binary is from the fish-2.7.1 tarball and statically linked.

## Usage

```
# In OpenWrt
cp -r <arch>/bin /
cp -r <arch>/etc /
cp -r <arch>/share /
ln -s /usr/share/terminfo ~/.terminfo
fish
```

