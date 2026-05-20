# Kotik VPN 0.6.87

Публичный релиз APK для Kotik VPN.

## Что изменилось

- BLUE остается строгим KotikDNS/MasterDnsVPN профилем без FIN-01 VLESS fallback.
- Добавлена поддержка нескольких Yggdrasil Anycast IPv6 resolvers.
- Bootstrap MasterDnsVPN профили принимают plural-поля `yggdrasil_anycast_ipv6_resolvers`, `yggdrasil_anycast_resolvers`, `yggdrasil_resolvers`, `ygg_resolvers`, `anycast_ipv6_resolvers`.
- Yggdrasil resolvers ставятся первыми перед обычными MasterDnsVPN resolvers и дедуплицируются.
- MasterDnsVPN config включает stream failover, background recheck, timeout auto-disable и MTU diagnostics.

## APK

- compat `ru.letsmobile.vpn`: `KotikVPN-0.6.87-compat-release.apk`
- next `ru.kotik.vpn`: `KotikVPN-0.6.87-next-release.apk`

## SHA-256

- compat: `12ac087c518480a59ef23ae18c38a1669d3262b9299374eec719c3c7db4944dc`
- next: `fd2fde175d3bdfe7d16b40bde000bea63c4b7ebac3a40ad21949e8f8b935ee8e`
