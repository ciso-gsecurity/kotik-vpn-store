# Kotik VPN 0.6.85

BLUE UI/runtime diagnostic hotfix.

## Что нового

- BLUE теперь использует `blue.gif` как полноценный animated background при выборе ноды.
- Отдельный котик BLUE поверх фона убран, лишняя анимация при подключении не запускается.
- Tap-зона на месте котика сохранена для подключения и отключения.
- MasterDnsVPN runtime пишет DEBUG-логи resolver/MTU/session, чтобы быстрее видеть причину сбоя на конкретной сети.
- Проверенный KotikDNS endpoint сохранен: `195.63.134.100:2053`.
- Обновлены публичные зеркала `kotik.lets-mobile.ru` и `vpn.lets-mobile.ru`.

## APK

| Track | Package | Size | SHA-256 |
| --- | --- | ---: | --- |
| compat | `ru.letsmobile.vpn` | `185564829` | `6a9476060291ac94c9b5f850efbd7f49dd517065a6abf745182015cb79e45f41` |
| next | `ru.kotik.vpn` | `185564561` | `2e2a0e1af951114ea9bace375afa709ff3b3f1002f63086e9ccaa6c876181359` |
