# [helmiau/helmiwrt-packages](https://github.com/helmiau/helmiwrt-packages) repository is already include this repository, and further updates will be there.

### badvpn and corkscrew package for openwrt
This repository is for archiving badvpn & corkscrew which working with latest snapshot OpenWrt build. Collected by [helmiau](http://www.github.com/helmiau)

tun2socks openwrt v1.999.128 **NEW DEC 2020** update by friyadhibiermann

Support :
```
NSS
NSPR
badvpn-server
badvpn-client
badvpn-tun2socks
badvpn-udpgw
badvpn-tunctl
badvpn-ncd
badvpn-ncd-request
```

#### Usage :
- Git this repo to your local files by running this command
```
git clone --depth=1 https://github.com/helmiau/badvpn_corkscrew
```
- Then add lines below to your **.config** file
```
CONFIG_PACKAGE_badvpn=y
CONFIG_PACKAGE_corkscrew=y
```

#### Credits :
- [Ambroz Bizjak](https://github.com/ambrop72/badvpn) for main badvpn source.
- [agroman.net](http://www.agroman.net/corkscrew/) for main corkscrew source.
- [Galih Prastowo Aji](https://github.com/hillz2/corkscrew) for corkscrew openwrt Makefile.
- [Friyadhi Biermann](https://github.com/friyadhibiermann/openwrt_badvpn-tun2socks) for badvpn openwrt Makefile and update.
- [Asrofur Rizqi](https://github.com/AsrofurRizqi) for clue to build these packages.

#### References :
- https://github.com/ambrop72/badvpn/wiki/Tun2socks
- https://code.google.com/archive/p/badvpn/downloads
- https://github.com/hillz2/corkscrew
- https://github.com/patpadgett/corkscrew

