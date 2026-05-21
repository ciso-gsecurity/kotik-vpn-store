# Kotik VPN 0.6.99

Whitelist/TSPU cleanup release for the public APK store.

## Downloads

- compat: `KotikVPN-0.6.99-compat-release.apk`
  - package: `ru.letsmobile.vpn`
  - versionCode: 116
  - versionName: `0.6.99-compat`
  - SHA-256: `f35e9324730ec54fa5a2e47d82e3e56c1d351a5daa9aec2b2263ad84c1cf3886`
- next: `KotikVPN-0.6.99-next-release.apk`
  - package: `ru.kotik.vpn`
  - versionCode: 116
  - versionName: `0.6.99-next`
  - SHA-256: `0d67bb9f04cbd70d25439598ba3f7c024357d09258d9f982d2a7baf33c188d5d`

## Changes

- WHITE/BLACK whitelist runtime uses `connIdle=8s` for faster TSPU freeze avoidance.
- Tier-2 SNI list was cleaned from duplicate and parent-covered entries.
- Health-check probes and whitelist VLESS candidate ordering tests were synchronized with production behavior.
- Release metadata now consistently points to 0.6.99 / versionCode 116.

## Verification

- `testCompatDebugUnitTest`
- `testNextDebugUnitTest`
- `assembleCompatRelease`
- `assembleNextRelease`
