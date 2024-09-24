<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Technitium DNS

[![集成程度](https://dash.yunohost.org/integration/technitium-dns.svg)](https://ci-apps.yunohost.org/ci/apps/technitium-dns/) ![工作状态](https://ci-apps.yunohost.org/ci/badges/technitium-dns.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/technitium-dns.maintain.svg)

[![使用 YunoHost 安装 Technitium DNS](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=technitium-dns)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Technitium DNS。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

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


**分发版本：** 13.0.1~ynh1

## 截图

![Technitium DNS 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 官方应用网站： <https://technitium.com/dns/>
- 官方用户文档： <https://technitium.com/dns/help.html>
- 官方管理文档： <https://technitium.com/dns/help.html>
- 上游应用代码库： <https://github.com/TechnitiumSoftware/DnsServer>
- YunoHost 商店： <https://apps.yunohost.org/app/technitium-dns>
- 报告 bug： <https://github.com/YunoHost-Apps/technitium-dns_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/technitium-dns_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/technitium-dns_ynh/tree/testing --debug
或
sudo yunohost app upgrade technitium-dns -u https://github.com/YunoHost-Apps/technitium-dns_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
