# wsdd

* [Overview](#overview)
* [Install](#install)
* [Uninstall](#uninstall)
* [Info](#info)

## Overview
**A Web Service Discovery host daemon.**  
This is only the site of wsdd deb package, tested with Debian 10 Buster and Debian 11 Bullseye. If you have Debian 12 Bookworm you don't need this deb file because it is already part of the official Debian 12 repository and you can install it directly with "apt install wsdd".

## Install
```bash
curl -sSfL https://raw.githubusercontent.com/mapi68/wsdd/master/wsdd-install | bash
```

## Uninstall
```bash
sudo apt --purge remove wsdd -y
```

## Info
**Do I need wsdd?**  
If you have a Linux machine with a Samba server and you don't see your shares on your Windows machine, I'll say: "Yes, of course!".  

*For additional info about wsdd, go [here](https://github.com/christgau/wsdd).*
