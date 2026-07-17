# Duckling VPN

## Download

**[Download the latest release »](https://github.com/BABYSHKABIKE/DucklingEXE/releases/latest)**

On the latest release page:

- `Duckling-Setup-<version>.exe` — recommended installer
- `Duckling-Portable-<version>.zip` — portable version
- `SHA256SUMS.txt` — checksums

This build is unsigned, so Windows SmartScreen may show a "Windows protected your PC" prompt. This is expected — click **More info**, then **Run anyway**. To verify a download, compare its SHA-256 with the matching line in `SHA256SUMS.txt`:

```powershell
Get-FileHash .\Duckling-Setup-<version>.exe -Algorithm SHA256
```

## Quick Start

1. Download and install Duckling from the latest release.
2. Open Telegram bot: `@Ducklingproxybot`.
3. Copy your connection key fully.
4. Open Duckling and paste the key.
5. Connect from the app.

## Скачать

**[Скачать последнюю версию »](https://github.com/BABYSHKABIKE/DucklingEXE/releases/latest)**

На странице последнего релиза:

- `Duckling-Setup-<версия>.exe` — рекомендуемый установщик
- `Duckling-Portable-<версия>.zip` — portable-версия
- `SHA256SUMS.txt` — контрольные суммы

Сборка не подписана цифровым сертификатом, поэтому Windows SmartScreen может показать предупреждение «Система Windows защитила ваш компьютер». Это ожидаемо — нажмите **Подробнее**, затем **Выполнить в любом случае**. Проверить загрузку можно, сравнив её SHA-256 со строкой в `SHA256SUMS.txt`:

```powershell
Get-FileHash .\Duckling-Setup-<версия>.exe -Algorithm SHA256
```

## Важно

Перед использованием Duckling отключите другие VPN-клиенты на устройстве. Одновременная работа нескольких VPN может мешать подключению.
