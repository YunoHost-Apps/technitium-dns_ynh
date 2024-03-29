<!--
N.B.: Questo README è stato automaticamente generato da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON DEVE essere modificato manualmente.
-->

# Technitium DNS per YunoHost

[![Livello di integrazione](https://dash.yunohost.org/integration/technitium-dns.svg)](https://dash.yunohost.org/appci/app/technitium-dns) ![Stato di funzionamento](https://ci-apps.yunohost.org/ci/badges/technitium-dns.status.svg) ![Stato di manutenzione](https://ci-apps.yunohost.org/ci/badges/technitium-dns.maintain.svg)

[![Installa Technitium DNS con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=technitium-dns)

*[Leggi questo README in altre lingue.](./ALL_README.md)*

> *Questo pacchetto ti permette di installare Technitium DNS su un server YunoHost in modo semplice e veloce.*  
> *Se non hai YunoHost, consulta [la guida](https://yunohost.org/install) per imparare a installarlo.*

## Panoramica

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

... and much more!

**Versione pubblicata:** 11.3.0~ynh2

## Screenshot

![Screenshot di Technitium DNS](./doc/screenshots/example.jpg)

## Documentazione e risorse

- Sito web ufficiale dell’app: <https://technitium.com/dns/>
- Documentazione ufficiale per gli utenti: <https://technitium.com/dns/help.html>
- Documentazione ufficiale per gli amministratori: <https://technitium.com/dns/help.html>
- Repository upstream del codice dell’app: <https://github.com/TechnitiumSoftware/DnsServer>
- Store di YunoHost: <https://apps.yunohost.org/app/technitium-dns>
- Segnala un problema: <https://github.com/YunoHost-Apps/technitium-dns_ynh/issues>

## Informazioni per sviluppatori

Si prega di inviare la tua pull request alla [branch di `testing`](https://github.com/YunoHost-Apps/technitium-dns_ynh/tree/testing).

Per provare la branch di `testing`, si prega di procedere in questo modo:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/technitium-dns_ynh/tree/testing --debug
o
sudo yunohost app upgrade technitium-dns -u https://github.com/YunoHost-Apps/technitium-dns_ynh/tree/testing --debug
```

**Maggiori informazioni riguardo il pacchetto di quest’app:** <https://yunohost.org/packaging_apps>
