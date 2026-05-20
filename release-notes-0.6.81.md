# Kotik VPN 0.6.81

Публичный hotfix для BLUE-ноды.

> Superseded: `0.6.82` возвращает BLUE на строгий KotikDNS/MasterDnsVPN путь без VLESS fallback.

- BLUE больше не останавливается на внутреннем MasterDnsVPN runtime guard.
- BLUE выбирает FIN-01 Reality/VLESS профиль из bootstrap-подписки.
- Endpoint FIN-01 сохраняется как `fin01.b.lets-mobile.ru:443` и не переписывается на DNS-порт `53`.
- APK опубликованы для `ru.letsmobile.vpn` и `ru.kotik.vpn`.

## Checksums

- `KotikVPN-0.6.81-compat-release.apk`: `4f767a2a1e3f6e02e6cbb7877488c0b287025c85978b98b916d77b8a49c5e52d`
- `KotikVPN-0.6.81-next-release.apk`: `f42a27488c047a8e8c5cb536288739f9bd11a6bce76a245f1878433e976ea9d4`
