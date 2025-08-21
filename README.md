<div align="center">

<img src="https://img.icons8.com/?size=100&id=123404&format=png&color=6E48AA" alt="EN Repository Logo" width="100">

# EN Repository 🌟

**Официальный репозиторий пакетов для EN-OS / Official package repository for EN-OS**

[![Arch Linux](https://img.shields.io/badge/Arch_Linux-1793D1?style=for-the-badge&logo=arch-linux&logoColor=white)](https://archlinux.org)
[![Pacman](https://img.shields.io/badge/Pacman-1793D1?style=for-the-badge&logo=pacman&logoColor=white)](https://wiki.archlinux.org/title/pacman)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-6e48aa?style=for-the-badge&logo=github)](https://github.com/Endscape-Coding/EN-Repository)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)](https://github.com/Endscape-Coding/EN-Repository)
[![License](https://img.shields.io/badge/License-GPL--3.0-blue?style=for-the-badge)](LICENSE)

</div>

<p align="center">
  <a href="#-русский">Русский</a> • <a href="#-english">English</a>
</p>

---

## 🇷🇺 Русский

<div align="center">

[📦 Пакеты](#-пакеты) • [⚡ Быстрый старт](#-быстрый-старт) • [🔧 Использование](#-использование) • [🤝 Сообщество](#-сообщество) • [❤️ Вклад в проект](#️-вклад-в-проект)

</div>

### 📦 Пакеты

EN Repository содержит тщательно собранные и оптимизированные пакеты для вашей системы. Полный список с подробным описанием доступен в нашем **[📋 Каталоге пакетов](PACKAGES.md)**.

**Некоторые из доступных пакетов:**

| Пакет | Версия | Описание | Размер |
|-------|--------|----------|--------|
| **`calamares`** | `25.02.2.1-4` | Установщик EN-OS с красивой темой (в разработке) 🎨 | `87 MB` |
| **`ayugram-desktop`** | `4.2.1-3` | Telegram клиент с улучшенным функционалом: чтение удаленок, режим призрака и.т.д. ✨ | `49 MB` |

[➡️ Посмотреть все пакеты...](PACKAGES.md)

---

### ⚡ Быстрый старт

```bash
# 1. Добавляем репозиторий
echo -e '\n[enrepo]\nSigLevel = Optional TrustAll\nServer = https://github.com/Endscape-Coding/EN-Repository/raw/main/repo/' | sudo tee -a /etc/pacman.conf

# 2. Обновляем базы
sudo pacman -Syy

# 3. Устанавливаем пакеты
sudo pacman -S enrepo/calamares enrepo/ayugram-desktop
```

---

### 🔧 Использование

#### Поиск пакетов
```bash
pacman -Sl enrepo
```

#### Информация о пакете
```bash
pacman -Si enrepo/calamares
```

#### Установка из конкретного репозитория
```bash
sudo pacman -S enrepo::package-name
```

---

### 🤝 Сообщество

Присоединяйтесь к нашему сообществу для обсуждения, помощи и новостей!

- **💬 Telegram-канал**: [@Linux_EN_OS](https://t.me/Linux_EN_OS)
- **👥 Telegram-чат**: [@enos_community](https://t.me/enos_community)
- **🐛 Баг-репорты**: [GitHub Issues](https://github.com/Endscape-Coding/EN-Repository/issues)

---

### ❤️ Вклад в проект

Мы приветствуем любую помощь в развитии репозитория!

- **Тестирование**: Устанавливайте пакеты и сообщайте о проблемах
- **Разработка**: Предлагайте новые пакеты через Pull Requests
- **Документация**: Помогайте улучшать документацию
- **Распространение**: Расскажите о репозитории друзьям

---

## 🇬🇧 English

<div align="center">

[📦 Packages](#-packages-1) • [⚡ Quick Start](#-quick-start) • [🔧 Usage](#-usage) • [🤝 Community](#-community-1) • [❤️ Contributing](#️-contributing)

</div>

### 📦 Packages

EN Repository contains carefully curated and optimized packages for your system. The complete list with detailed descriptions is available in our **[📋 Package Catalog](PACKAGES.md)**.

**Some of the available packages:**

| Package | Version | Description | Size |
|---------|---------|-------------|------|
| **`calamares`** | `25.02.2.1-4` | EN-OS installer with beautiful theme (in working..) 🎨 | `87 MB` |
| **`ayugram-desktop`** | `4.2.1-3` | Telegram client with intresting functional: ghost mode, read deleted messaged and more.. ✨ | `48 MB` |

[➡️ View all packages...](PACKAGES.md)

---

### ⚡ Quick Start

```bash
# 1. Add repository
echo -e '\n[enrepo]\nSigLevel = Optional TrustAll\nServer = https://github.com/Endscape-Coding/EN-Repository/raw/main/repo/' | sudo tee -a /etc/pacman.conf

# 2. Update database
sudo pacman -Syy

# 3. Install packages
sudo pacman -S enrepo/calamares enrepo/ayugram-desktop
```

---

### 🔧 Usage

#### Search packages
```bash
pacman -Sl enrepo
```

#### Package information
```bash
pacman -Si enrepo/calamares
```

#### Install from specific repository
```bash
sudo pacman -S enrepo::package-name
```

---

### 🤝 Community

Join our community for discussions, support, and news!

- **💬 Telegram Channel**: [@Linux_EN_OS](https://t.me/Linux_EN_OS)
- **👥 Telegram Chat**: [@enos_community](https://t.me/enos_community)
- **🐛 Bug Reports**: [GitHub Issues](https://github.com/Endscape-Coding/EN-Repository/issues)

---

### ❤️ Contributing

We welcome any contributions to the repository development!

- **Testing**: Install packages and report issues
- **Development**: Suggest new packages via Pull Requests
- **Documentation**: Help improve documentation
- **Spreading the word**: Tell your friends about the repository

---

<div align="center">

**⭐ Не забудьте поставить звезду на GitHub! / ⭐ Don't forget to star us on GitHub!**

[![GitHub stars](https://img.shields.io/github/stars/Endscape-Coding/EN-Repository?style=social)](https://github.com/Endscape-Coding/EN-Repository)

*Последнее обновление: $(date +%Y-%m-%d) / Last updated: $(date +%Y-%m-%d)*

</div>

---
