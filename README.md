# AnixartEX TUI

Терминальный клиент для [Anixart](https://anixart.tv).

**Версия:** 2.0.0 — *Celestia [Asmo] Beta*

Поддерживаемые платформы: **Linux**, **macOS**, **Windows**

## Требования

- Node.js 24 LTS+
- Терминал с UTF-8 и 256+ цветов (Windows Terminal, iTerm2, GNOME Terminal и др.)

## Установка

### Linux

```bash
curl -fsSL https://raw.githubusercontent.com/ShakhShirakawa/AnixartEX_TUI-releases/main/install-linux.sh | bash
```

### macOS

```bash
curl -fsSL https://raw.githubusercontent.com/ShakhShirakawa/AnixartEX_TUI-releases/main/install-macos.sh | bash
```

### Windows (PowerShell)

```powershell
irm https://raw.githubusercontent.com/ShakhShirakawa/AnixartEX_TUI-releases/main/install-windows.ps1 | iex
```

Конкретная версия (Linux/macOS):

```bash
curl -fsSL …/install-linux.sh | bash -s -- --version 2.0.0
```

## Запуск

```bash
anixartex
```

Если команда не найдена (Linux/macOS):

```bash
export PATH="$HOME/.local/bin:$PATH"
```

## Проверка архива

```bash
sha256sum -c checksums.txt
```

## Лицензия

Проприетарное ПО. Исходный код не распространяется.
