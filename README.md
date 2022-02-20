<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# VPN Client for YunoHost

[![Integration level](https://dash.yunohost.org/integration/vpnclient.svg)](https://dash.yunohost.org/appci/app/vpnclient) ![](https://ci-apps.yunohost.org/ci/badges/vpnclient.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/vpnclient.maintain.svg)  
[![Install VPN Client with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=vpnclient)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install VPN Client quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

* Install a VPN connection on your self-hosted server.
* Useful for hosting your server behind a filtered (and/or non-neutral) internet access.
* Useful to have static IP addresses (IPv6 and IPv4).
* Useful to easily move your server anywhere.
* Strong firewalling (internet access and self-hosted services only available through the VPN, not leaking to your commercial ISP)
* Combine with the [Hotspot app](https://github.com/YunoHost-Apps/hotspot_ynh) to broadcast VPN-protected WiFi to other laptops without any further technical configuration needed.



**Shipped version:** 2.0.2~ynh9



## Screenshots

![](./doc/screenshots/vpnclient.png)

## Disclaimers / important information

Please note that this application is designed to interface with **dedicated, public IP VPNs accepting inbound traffic**, preferably with an associated `.cube` (or `.ovpn/.conf`) configuration file. **Do not** expect that any VPN you randomly bought on the Internet can be used! Checkout the [list of known compatible providers](https://yunohost.org/providers/vpn) for more info.

## Documentation and resources

* YunoHost documentation for this app: https://yunohost.org/app_vpnclient
* Report a bug: https://github.com/YunoHost-Apps/vpnclient_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/vpnclient_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/vpnclient_ynh/tree/testing --debug
or
sudo yunohost app upgrade vpnclient -u https://github.com/YunoHost-Apps/vpnclient_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps