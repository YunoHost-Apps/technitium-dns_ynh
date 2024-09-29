<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Technitium DNS para Yunohost

[![Nivel de integración](https://dash.yunohost.org/integration/technitium-dns.svg)](https://ci-apps.yunohost.org/ci/apps/technitium-dns/) ![Estado funcional](https://ci-apps.yunohost.org/ci/badges/technitium-dns.status.svg) ![Estado En Mantención](https://ci-apps.yunohost.org/ci/badges/technitium-dns.maintain.svg)

[![Instalar Technitium DNS con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=technitium-dns)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarTechnitium DNS rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

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


**Versión actual:** 13.0.2~ynh1

## Capturas

![Captura de Technitium DNS](./doc/screenshots/screenshot.png)

## Documentaciones y recursos

- Sitio web oficial: <https://technitium.com/dns/>
- Documentación usuario oficial: <https://technitium.com/dns/help.html>
- Documentación administrador oficial: <https://technitium.com/dns/help.html>
- Repositorio del código fuente oficial de la aplicación : <https://github.com/TechnitiumSoftware/DnsServer>
- Catálogo YunoHost: <https://apps.yunohost.org/app/technitium-dns>
- Reportar un error: <https://github.com/YunoHost-Apps/technitium-dns_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [rama `testing`](https://github.com/YunoHost-Apps/technitium-dns_ynh/tree/testing).

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/technitium-dns_ynh/tree/testing --debug
o
sudo yunohost app upgrade technitium-dns -u https://github.com/YunoHost-Apps/technitium-dns_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
