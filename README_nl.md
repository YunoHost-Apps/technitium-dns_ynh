<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Technitium DNS voor Yunohost

[![Integratieniveau](https://apps.yunohost.org/badge/integration/technitium-dns)](https://ci-apps.yunohost.org/ci/apps/technitium-dns/)
![Mate van functioneren](https://apps.yunohost.org/badge/state/technitium-dns)
![Onderhoudsstatus](https://apps.yunohost.org/badge/maintained/technitium-dns)

[![Technitium DNS met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=technitium-dns)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Technitium DNS snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

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


**Geleverde versie:** 13.4~ynh1

## Schermafdrukken

![Schermafdrukken van Technitium DNS](./doc/screenshots/screenshot.png)

## Documentatie en bronnen

- Officiele website van de app: <https://technitium.com/dns/>
- Officiele gebruikersdocumentatie: <https://technitium.com/dns/help.html>
- Officiele beheerdersdocumentatie: <https://technitium.com/dns/help.html>
- Upstream app codedepot: <https://github.com/TechnitiumSoftware/DnsServer>
- YunoHost-store: <https://apps.yunohost.org/app/technitium-dns>
- Meld een bug: <https://github.com/YunoHost-Apps/technitium-dns_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/technitium-dns_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/technitium-dns_ynh/tree/testing --debug
of
sudo yunohost app upgrade technitium-dns -u https://github.com/YunoHost-Apps/technitium-dns_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
