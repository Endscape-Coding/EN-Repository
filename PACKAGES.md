# 📦 Каталог пакетов EN Repository / Package Catalog

## 🛠️ Системные утилиты / System Utilities

### calamares
**Версия:** 25.02.2.1-4 
**Размер:** ~87.3 MB  
**Описание:** Установщик EN-OS с кастомными темами и конфигурациями  
**Зависимости:** qt5-base, kconfig, kcoreaddons  
**Команда установки:** `sudo pacman -S enrepo/calamares`

### en-system-manager
**Версия:** 1.2-1 
**Размер:** ~11.1 MB  
**Описание:** Менеджер системы (графический менеджер проприетарных драйверов видеокарт, графический менеджер пакетов, Zapret Manager GUI, и.т.д.). Может работать на большей части arch подобных дистрибутивах  
**Зависимости:** python3 python-pyqt5  
**Команда установки:** `sudo pacman -S en-system-manager`

### en-os-mojave
**Версия:** 1.1-1 
**Размер:** ~600 KB  
**Описание:** Тема sddm для EN-OS  
**Зависимости:** sddm  
**Команда установки:** `sudo pacman -S en-os-mojave`

### en-os-simpleblue
**Версия:** 1.0-1 
**Размер:** ~170 KB  
**Описание:** Анимация при входе в KDE plasma  
**Зависимости:** plasma-workspace qt5-declarative kconfig kpackage  
**Команда установки:** `sudo pacman -S en-os-simpleblue`

### mkinitcpio-openswap
**Версия:** 0.1.0-3 
**Размер:** ~50 KB  
**Описание:** Mkinitcpio хук  
**Зависимости:** mkinitcpio  
**Команда установки:** `sudo pacman -S mkinitcpio-openswap`

### en-plymouth-theme
**Версия:** 1.0-1 
**Размер:** ~170 KB  
**Описание:** Тема plymouth для EN-OS  
**Зависимости:** plymouth  
**Команда установки:** `sudo pacman -S en-plymouth-theme`

### yay
**Версия:** 12.5.0-1 
**Размер:** ~19.3 MB  
**Описание:** Aur менеджер пакетов (аналог Paru)  
**Зависимости:** git pacman>6.1   
**Команда установки:** `sudo pacman -S yay`

### en-pamac
**Версия:** 1-1 
**Размер:** ~19.3 MB  
**Описание:** Менеджер пакетов и обновлений с поддержкой Aur, flatpak и snap пакетов  
**Зависимости:** gtk3 libnotify json-glib libhandy libadwaita archlinux-appstream-data polkit en-libpamac
**Команда установки:** `sudo pacman -S en-pamac`

## 💻 Приложения / Applications

### ayugram-desktop
**Версия:** 5.16.3-2 
**Размер:** ~49.4 MB  
**Описание:** Telegram клиент с интересными фишками: чтение удаленок, режим призрака, расширенная кастомизация и.т.д. 
**Зависимости:** qt5-base, openssl  
**Команда установки:** `sudo pacman -S enrepo/ayugram-desktop`

## 🎮 Игры / Games

### steam-nvidia
**Версия:** 1.0.0.82-2  
**Размер:** ~19 MB  
**Описание:** Магазин игр от valve, поддерживает proton, для видеокарт nvidia  
**Зависимости:** lib32-nvidia-utils  
**Команда установки:** `sudo pacman -S steam-nvidia`

### steam-amd  
**Версия:** 1.0.0.82-2  
**Размер:** ~19 MB  
**Описание:** Магазин игр от valve, поддерживает proton, для видеокарт amd  
**Зависимости:** lib32-vulkan-radeon  
**Команда установки:** `sudo pacman -S steam-amd`

### miside-linux-crack  
**Версия:** 1.0-1  
**Размер:** ~1.1 GB  
**Описание:** Полностью рабочий порт кряка игры MiSide на Linux, работает через wine  
**Зависимости:** wine winetricks fuse-overlayfs dwarfs  
**Команда установки:** `sudo pacman -S miside-linux-crack`
