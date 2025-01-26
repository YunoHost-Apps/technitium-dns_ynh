<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# Technitium DNS for YunoHost

[![Integration level](https://apps.yunohost.org/badge/integration/technitium-dns)](https://ci-apps.yunohost.org/ci/apps/technitium-dns/)
![Working status](https://apps.yunohost.org/badge/state/technitium-dns)
![Maintenance status](https://apps.yunohost.org/badge/maintained/technitium-dns)

[![Install Technitium DNS with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=technitium-dns)

*[Read this README in other languages.](./ALL_README.md)*

> *This package allows you to install Technitium DNS quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

Technitium DNS Server is an open source tool that can be used for blocking Internet Ads using DNS Sinkhole, self hosting a local DNS server for privacy & security or, used for experimentation/testing by software developers on their computer.

### Features

- Block ads & malware using one or more block list URLs.
- High performance DNS server based on async IO that can serve millions of requests per minute even on a commodity desktop PC hardware (load tested on Intel i7-8700 CPU with more than 100,000 request/second over Gigabit Ethernet).
- Self host DNS-over-TLS and DNS-over-HTTPS DNS service on your network.
- Use public DNS resolvers like Cloudflare, Google & Quad9 with DNS-over-TLS and DNS-over-HTTPS protocols as forwarders.
- Advanced caching with features like serve stale, prefetching and auto prefetching.
- Supports working as an authoritative as well as a recursive DNS server.
- DNSSEC validation support with RSA & ECDSA algorithms for recursive resolver, forwarders, and conditional forwarders.
- DNSSEC support for all supported DNS transport protocols including encrypted DNS protocols (DoT, DoH, & DoH JSON).
- CNAME cloaking feature to block domain names that resolve to CNAME which are blocked.
- Self host your domain names on your own DNS server.
- Wildcard sub domain support.


**Shipped version:** 13.4~ynh1

## Screenshots

![Screenshot of Technitium DNS](./doc/screenshots/screenshot.png)

## Documentation and resources

- Official app website: <https://technitium.com/dns/>
- Official user documentation: <https://technitium.com/dns/help.html>
- Official admin documentation: <https://technitium.com/dns/help.html>
- Upstream app code repository: <https://github.com/TechnitiumSoftware/DnsServer>
- YunoHost Store: <https://apps.yunohost.org/app/technitium-dns>
- Report a bug: <https://github.com/YunoHost-Apps/technitium-dns_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/technitium-dns_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/technitium-dns_ynh/tree/testing --debug
or
sudo yunohost app upgrade technitium-dns -u https://github.com/YunoHost-Apps/technitium-dns_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
