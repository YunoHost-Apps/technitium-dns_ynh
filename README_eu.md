<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Technitium DNS YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/technitium-dns.svg)](https://dash.yunohost.org/appci/app/technitium-dns) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/technitium-dns.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/technitium-dns.maintain.svg)

[![Instalatu Technitium DNS YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=technitium-dns)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Technitium DNS YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

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


**Paketatutako bertsioa:** 11.3.0~ynh2

## Pantaila-argazkiak

![Technitium DNS(r)en pantaila-argazkia](./doc/screenshots/example.jpg)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://technitium.com/dns/>
- Erabiltzaileen dokumentazio ofiziala: <https://technitium.com/dns/help.html>
- Administratzaileen dokumentazio ofiziala: <https://technitium.com/dns/help.html>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/TechnitiumSoftware/DnsServer>
- YunoHost Denda: <https://apps.yunohost.org/app/technitium-dns>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/technitium-dns_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/technitium-dns_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/technitium-dns_ynh/tree/testing --debug
edo
sudo yunohost app upgrade technitium-dns -u https://github.com/YunoHost-Apps/technitium-dns_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
