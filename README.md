# STA-VPN

Персональный VPN клиент на базе Xray, VK TURN, WireGuard и AmneziaWG.

Основан на WINGS V и Hiddify. Адаптирован для личного использования.

## Возможности
- Xray (VLESS Reality), VK TURN + WireGuard/AmneziaWG, WireGuard/AmneziaWG
- Samsung One UI интерфейс
- Root-раздача VPN (Wi-Fi/USB/Bluetooth/Ethernet)
- Маршрутизация по приложениям
- Формат ссылок: `stavpn://`
- Импорт: `vless://`, `awg-quick`

## Сборка
```bash
git clone --recurse-submodules https://github.com/mobstardos/sta-vpn-android.git
cd sta-vpn-android
./gradlew :app:assembleDebug
```

Требуется: Android SDK, NDK, Go, protoc, gomobile, Rust + cargo-ndk.

## Сервер
```
IP: 201.51.21.213
Порт: 443
Протокол: VLESS Reality
```
