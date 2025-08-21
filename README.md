# EN-Repository 🚀

Официальный репозиторий пакетов для EN-OS. Здесь содержатся специально собранные и оптимизированные пакеты для вашей системы.

## 📦 Доступные пакеты

### Calamares для EN-OS
**Установка:**
```bash
sudo pacman -S enrepo/calamares
```

**Описание:**  
Кастомная сборка установщика Calamares, оптимизированная для EN-OS. Включает все необходимые конфигурации и модули для удобной установки системы.

**Версия:** 25.02.2.1-4  
**Размер:** ~122 MB  
**Зависимости:** Автоматически разрешаются pacman

---

### Ayugram Desktop
**Установка:**
```bash
sudo pacman -S enrepo/ayugram-desktop
```

**Описание:**  
Фирменный desktop-клиент Ayugram с дополнительными возможностями и улучшенной интеграцией с EN-OS.

**Версия:** Последняя стабильная  
**Размер:** ~52 MB  
**Особенности:** Нативные уведомления, оптимизация под Arch Linux

---

## ⚡ Быстрый старт

### 1. Добавление репозитория
Добавьте в `/etc/pacman.conf`:
```ini
[enrepo]
SigLevel = Optional TrustAll
Server = https://github.com/Endscape-Coding/EN-Repository/raw/main/repo/
```

### 2. Обновление баз данных
```bash
sudo pacman -Syy
```

### 3. Установка пакетов
```bash
sudo pacman -S enrepo/calamares
sudo pacman -S enrepo/ayugram-desktop
```

## 🔧 Дополнительные команды

### Поиск пакетов в репозитории
```bash
pacman -Sl enrepo
```

### Информация о пакете
```bash
pacman -Si enrepo/calamares
```

### Установка конкретной версии
```bash
sudo pacman -S enrepo/calamares-25.02.2.1-4
```

## 🛠️ Для разработчиков

### Структура репозитория
```
EN-Repository/
└── repo/
    ├── enrepo.db.tar.gz      # База данных пакетов
    ├── enrepo.files.tar.gz   # Файловая база
    ├── calamares-25.02.2.1-4-x86_64.pkg.tar.zst
    └── ayugram-desktop-*.pkg.tar.zst
```

### Обновление репозитория
```bash
cd ~/EN-Repository/repo
repo-add enrepo.db.tar.gz *.pkg.tar.zst
git add .
git commit -m "Update: добавлены новые пакеты"
git push origin main
```

## ❓ Частые вопросы

### Ошибка 404 при обновлении
Убедитесь, что ссылка в pacman.conf заканчивается на `/`:
```ini
Server = https://github.com/.../raw/main/repo/
```

### Пакет не находится
Обновите базы данных:
```bash
sudo pacman -Syy
```

### Конфликт версий
Для установки из конкретного репозитория:
```bash
sudo pacman -S enrepo::package-name
```

## 📊 Статус репозитория

| Пакет | Версия | Статус |
|-------|--------|---------|
| Calamares | 25.02.2.1-4 | ✅ Стабильный |
| Ayugram Desktop | latest | ✅ Стабильный |

## 🤝 Участие в разработке

Предложения по улучшению пакетов и новые PR приветствуются! 

1. Форкните репозиторий
2. Создайте ветку для ваших изменений
3. Откройте Pull Request

## ⚠️ Важная информация

- Репозиторий оптимизирован для EN-OS и Arch Linux-based систем
- Все пакеты проходят тестирование перед добавлением
- Рекомендуется регулярно обновлять пакеты: `sudo pacman -Syu`

---

**Поддержите проект:** ⭐ Поставьте звезду на GitHub!

*Последнее обновление: $(date +%Y-%m-%d)*
