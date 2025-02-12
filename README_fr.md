<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Technitium DNS pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/technitium-dns)](https://ci-apps.yunohost.org/ci/apps/technitium-dns/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/technitium-dns)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/technitium-dns)

[![Installer Technitium DNS avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=technitium-dns)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Technitium DNS rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Technitium DNS Server est un outil open source qui peut être utilisé pour bloquer les publicités Internet à l'aide de DNS Sinkhole, pour héberger automatiquement un serveur DNS local pour des raisons de confidentialité et de sécurité ou pour l'expérimentation/les tests par les développeurs de logiciels sur leur ordinateur.

### Caractéristiques

- Bloquez les publicités et les logiciels malveillants à l'aide d'une ou plusieurs URL de liste de blocage.
- Serveur DNS hautes performances basé sur des E/S asynchrones qui peuvent traiter des millions de requêtes par minute, même sur un matériel PC de bureau standard (charge testée sur un processeur Intel i7-8700 avec plus de 100000 requêtes/seconde sur Gigabit Ethernet).
- Auto-hébergez les services DNS DNS-over-TLS et DNS-over-HTTPS sur votre réseau.
- Utilisez des résolveurs DNS publics comme Cloudflare, Google et Quad9 avec les protocoles DNS-over-TLS et DNS-over-HTTPS comme redirecteurs.
- Mise en cache avancée avec des fonctionnalités telles que le service obsolète, la prélecture et la prélecture automatique.
- Prend en charge le travail en tant que serveur DNS faisant autorité et récursif.
- Prise en charge de la validation DNSSEC avec les algorithmes RSA et ECDSA pour le résolveur récursif, les redirecteurs et les redirecteurs conditionnels.
- Prise en charge DNSSEC de tous les protocoles de transport DNS pris en charge, y compris les protocoles DNS cryptés (DoT, DoH et DoH JSON).
- Fonctionnalité de masquage CNAME pour bloquer les noms de domaine résolus en CNAME qui sont bloqués.
- Hébergez vous-même vos noms de domaine sur votre propre serveur DNS.
- Prise en charge des sous-domaines génériques.

**Version incluse :** 13.4.1~ynh1

## Captures d’écran

![Capture d’écran de Technitium DNS](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Site officiel de l’app : <https://technitium.com/dns/>
- Documentation officielle utilisateur : <https://technitium.com/dns/help.html>
- Documentation officielle de l’admin : <https://technitium.com/dns/help.html>
- Dépôt de code officiel de l’app : <https://github.com/TechnitiumSoftware/DnsServer>
- YunoHost Store : <https://apps.yunohost.org/app/technitium-dns>
- Signaler un bug : <https://github.com/YunoHost-Apps/technitium-dns_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/technitium-dns_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/technitium-dns_ynh/tree/testing --debug
ou
sudo yunohost app upgrade technitium-dns -u https://github.com/YunoHost-Apps/technitium-dns_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
