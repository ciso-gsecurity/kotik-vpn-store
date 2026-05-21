# Kotik VPN 0.6.90

Публичный релиз APK для Kotik VPN.

## Что нового

- WHITE/BLACK VLESS-кандидаты сортируются по bypass-скору: XHTTP, chrome fingerprint, XTLS-Vision, SNI-RU/CIDR и RU-мост `r.b.lets-mobile.ru`.
- Профили с битым `pbk` отбрасываются до попытки подключения.
- Для white-list runtime XHTTP без `mode` включает `packet-up`, TLS fingerprint принудительно `chrome`, `connIdle` сокращён до 45 секунд против фриза длинных TCP-сессий ТСПУ.
- РКН live monitor из 0.6.89 сохранён: IP, DNS, флаг страны и live RX/TX остаются на месте.

## APK

- `KotikVPN-0.6.90-compat-release.apk`
  - Package: `ru.letsmobile.vpn`
  - Version code: `107`
  - SHA-256: `f67382aa6686b2430efa8779c7533fb241c9a40fdf25dc3b046d34956172a37c`
- `KotikVPN-0.6.90-next-release.apk`
  - Package: `ru.kotik.vpn`
  - Version code: `107`
  - SHA-256: `36311fb481759b7b20abeafabbfbb6c7765f24669b5db7f156d026824b7dfe42`
