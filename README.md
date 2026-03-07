# 🌸 Интерактивная открытка к 8 марта / Interactive March 8 Greeting Card

<div align="center">

![Version](https://img.shields.io/badge/версия-1.0.0-ff69b4.svg?style=for-the-badge&labelColor=black)
![License](https://img.shields.io/badge/лицензия-GPLv3-blue.svg?style=for-the-badge&labelColor=black)
![Status](https://img.shields.io/badge/статус-stable-brightgreen.svg?style=for-the-badge&labelColor=black)
![Mobile](https://img.shields.io/badge/мобильная-адаптация-9cf.svg?style=for-the-badge&labelColor=black)

**✨ Уникальная веб-открытка с мини-играми, коллекцией тем и системой прогрессии ✨**

[🔗 Демо](https://su57ks.github.io/8march/)

---

*🎉 **Важно:** Проект создан как творческий эксперимент и не предназначен для реальных азартных игр. Все игровые механики — исключительно развлекательный контент к празднику.* 🎉

</div>

---

## 📋 Содержание
- [🌸 Русская версия](#-русская-версия)
  - [🚀 Запуск проекта](#-запуск-проекта)
  - [👥 Команда проекта](#-команда-проекта)
  - [📝 Описание проекта](#-описание-проекта)
  - [✨ Ключевые возможности](#-ключевые-возможности)
  - [🎮 Мини-игры](#-мини-игры)
  - [🎨 Темы оформления](#-темы-оформления)
  - [🔑 Промокоды и секреты](#-промокоды-и-секреты)
  - [📊 Система прогрессии](#-система-прогрессии)
  - [📁 Структура проекта](#-структура-проекта)
  - [🛠 Технологии](#-технологии)
  - [📜 Лицензия](#-лицензия)
- [🇬🇧 English version](#-english-version)
  - [🚀 Project Launch](#-project-launch)
  - [👥 Project Team](#-project-team)
  - [📝 Project Description](#-project-description)
  - [✨ Key Features](#-key-features)
  - [🎮 Mini-games](#-mini-games)
  - [🎨 Color Themes](#-color-themes)
  - [🔑 Promo Codes & Secrets](#-promo-codes--secrets)
  - [📊 Progression System](#-progression-system)
  - [📁 Project Structure](#-project-structure)
  - [🛠 Technologies](#-technologies)
  - [📜 License](#-license)

---

## 🌸 Русская версия

### 🚀 Запуск проекта

#### Простой способ
1. Перейдите по ссылке: **[su57ks.github.io/8march/](https://su57ks.github.io/8march/)**
2. Наслаждайтесь интерактивной открыткой! 🎉

#### Локальный запуск
```bash
# Клонируйте репозиторий
git clone https://github.com/su57ks/8march.git

# Перейдите в папку проекта
cd 8march

# Откройте index.html в браузере
# Или запустите локальный сервер (например, с помощью Live Server в VS Code)
```

#### Требования
- Любой современный браузер (Chrome, Firefox, Safari, Edge)
- Включенный JavaScript
- Поддержка LocalStorage

---

### 👥 Команда проекта

| Роль | Имя | Контакт |
|------|-----|---------|
| 👨‍💻 **Автор** | Aizen | [@su57ks](https://t.me/su57ks) |
| 💡 **Идеи** | Santus | [@selyswag](https://t.me/selyswag) |
| 🧪 **Тестеры** | Амир, Лёша и Ярослава | — |
| 🙏 **Благодарности** | Егору Е. и Денису С. | — |

---

### 📝 Описание проекта
**Интерактивная открытка к 8 марта** — это не просто статичное поздравление, а полноценное веб-приложение с игровыми механиками. Вместо обычной картинки пользователь получает возможность взаимодействовать с контентом: собирать виртуальные цветы, открывать новые темы оформления, играть в мини-игры и читать персонализированные поздравления.

Проект создан с душой и вниманием к деталям: каждая мелочь, от анимации лепестков до цветопада, призвана создать праздничное настроение.

---

### ✨ Ключевые возможности

| Категория | Функция | Описание |
|-----------|---------|----------|
| 🎨 **Интерфейс** | Адаптивный дизайн | Полная поддержка мобильных устройств, планшетов и десктопов |
| | PWA-подобный опыт | Работает офлайн после загрузки, сохраняет прогресс |
| | Кастомные модалки | 10+ типов модальных окон с уникальным дизайном |
| 🎮 **Геймплей** | Кликер-механика | Сбор цветов нажатием на большой цветок |
| | Система уровней | Каждые 100 цветов — особое поздравление |
| | Комплименты | Случайные комплименты каждые 50 цветов |
| 💾 **Сохранения** | LocalStorage | Автоматическое сохранение прогресса |
| | Синхронизация | Сохраняются цветы, открытые темы, использованные промокоды |
| 🎯 **Разблокировки** | Прогрессивное открытие | Новый контент доступен при достижении целей |
| | Секретные темы | 3 скрытые темы, открываемые через прогресс или промокоды |

---

### 🎮 Мини-игры

#### Сравнительная таблица мини-игр

| Характеристика | 🌼 Гадание на ромашке | 🎰 Казино "Букет" | 🎡 Колесо удачи |
|----------------|----------------------|-------------------|-----------------|
| **Файл** | `mini_games/chamomile.html` | `mini_games/casino.html` | `mini_games/bouquet.html` |
| **Стоимость** | 10🌸 | Бесплатно (доступ) / ставки цветами | 10🌸 |
| **Механика** | Отрывание лепестков | Ставки на множители | Случайный цветок |
| **Награда** | Предсказания | x0, x0.1, x1.5, x2, x5, x11 | Эмодзи цветка |
| **Сектора** | 9-12 лепестков | 8 секторов | 8 секторов |
| **Визуализация** | CSS-ромашка | Canvas-колесо | Canvas-колесо |
| **Уровень сложности** | 🟢 Простая | 🔴 Азартная | 🟡 Случайная |

#### Детальное описание

**🌼 Гадание на ромашке** (`chamomile.html`)
- От 9 до 12 лепестков на цветке
- 6 вариантов предсказаний:
  - "Любит 💖"
  - "Не любит 🖤"
  - "Плюнет 💧"
  - "Поцелует 💋"
  - "К сердцу прижмёт 🤗"
  - "К чёрту пошлёт 👿"
- При отрыве последнего лепестка — финальное предсказание
- Возможность "перегадать" (кнопка "Гадать")
- Анимация вращения при перегадывании

**🎰 Казино "Букет"** (`casino.html`)
- Система ставок с полем ввода
- Кнопка "Макс" для максимальной ставки
- 8 секторов с множителями: 0, 0, 0.1, 0.1, 1.5, 2, 5, 11
- Физика вращения с затуханием
- Результат показывается в модальном окне
- Цветопад при выигрыше

**🎡 Колесо удачи** (`bouquet.html`)
- 8 секторов с цветами: сакура, ромашка, тюльпан, гибискус, тюльпан, роза, сакура, роза
- Названия цветов с заглавной буквы
- При выпадении — ливень из соответствующего цветка
- Простая механика без ставок

---

### 🎨 Темы оформления

| Тема | Класс | Цветовая схема | Статус | Градиент |
|------|-------|----------------|--------|----------|
| **Розовая** | `theme-default` | Розово-персиковая | 🔓 По умолчанию | `#fef3f8 → #ffeef4` |
| **Белая** | `theme-white` | Монохромная светлая | 🔓 По умолчанию | `#ffffff → #f5f5f5` |
| **Сиреневая** | `theme-lilac` | Лавандово-сиреневая | 🔓 По умолчанию | `#f3e5f5 → #e1bee7` |
| **Ярко-розовая** | `theme-bright-pink` | Насыщенно-розовая | 🔓 По умолчанию | `#ffd0dd → #ffb0c5` |
| **Золотая** | `theme-gold` | Золотисто-медовая | 🔐 1000🌸 | `#fbf3e0 → #f5d0a0` |
| **Космическая** | `theme-cosmic` | Фиолетово-космическая | 🔐 Промокод `505` | `#0a0f1e → #2a1f4a` |
| **Тёмно-синяя** | `theme-dark-blue` | Глубокий синий | 🔐 Промокод `1337` | `#0a1a2a → #0a1f4a` |

---

### 🔑 Промокоды и секреты

| Промокод | Эффект | Тип |
|----------|--------|-----|
| `1488` | 🚫 Сброс прогресса (анти-нацистское послание) | Штрафной |
| `52` | 🏛️ +5200 цветов (Санкт-Петербург) | Бонусный |
| `67` | 😕 +1 цветок (шутка) | Шуточный |
| `69` | 😏 +690 цветов | Шуточный |
| `1337` | 👾 +133700 цветов + тёмно-синяя тема | Секретный |
| `505` | 🌟 +505812 цветов + космическая тема | Секретный |
| `МЫВАСЛЮБИМ` | 💖 +1 млрд цветов | Пасхалка |

**Подсказка в модалке промокодов:** "Например 2,71828" (число e) — отсылка к математике

---

### 📊 Система прогрессии

```
Начало игры
    ↓
Сбор цветов (кликер)
    ↓
├── 50🌸 → Случайный комплимент
├── 100🌸 → Поздравление с достижением
├── 500🌸 → Открытие всех базовых тем
└── 1000🌸 → Открытие казино + Золотая тема
         ↓
    Появление нижней навигации
         ↓
    ├── Главная страница
    └── Казино (ставки цветами)
         ↓
    Возможность выигрыша/проигрыша
```

---

### 📁 Структура проекта

```
📦 8march
├── 📄 index.html                          # Главный файл (все компоненты)
├── 📁 themes/
│   ├── 🎨 base.css                         # Базовая стилизация
│   └── 🎨 themes.css                        # CSS-переменные всех тем
├── 📁 mini_games/
│   ├── 🎰 casino.html                       # Казино с множителями
│   ├── 🌼 chamomile.html                     # Гадание на ромашке
│   └── 🎡 bouquet.html                       # Колесо удачи
└── 📄 README.md                            # Документация
```

---

### 🛠 Технологии

| Технология | Применение |
|------------|------------|
| **HTML5** | Структура страниц, семантическая разметка |
| **CSS3** | Стилизация, анимации, медиа-запросы, CSS-переменные |
| **JavaScript (ES6+)** | Логика игр, обработка событий, LocalStorage |
| **Canvas API** | Отрисовка колёс рулетки |
| **LocalStorage** | Сохранение прогресса пользователя |
| **Flexbox/Grid** | Адаптивная вёрстка |
| **CSS-переменные** | Динамическая смена тем |

---

### 📜 Лицензия

Проект распространяется под лицензией **GNU General Public License v3 (GPLv3)**.

```
                    GNU GENERAL PUBLIC LICENSE
                       Version 3, 29 June 2007

Это свободная лицензия: вы можете распространять и/или изменять
программу в соответствии с условиями GNU General Public License,
опубликованной Free Software Foundation, либо версии 3 лицензии,
либо (по вашему выбору) любой более поздней версии.

Данная программа распространяется в надежде, что она будет полезной,
но БЕЗ КАКИХ-ЛИБО ГАРАНТИЙ; даже без подразумеваемых гарантий
ТОВАРНОГО СОСТОЯНИЯ или ПРИГОДНОСТИ ДЛЯ КОНКРЕТНЫХ ЦЕЛЕЙ.
```

**Основные положения GPLv3:**
- ✅ Вы можете использовать, изменять и распространять код
- ✅ Вы обязаны сохранять авторские права
- ✅ Изменённые версии также должны распространяться под GPLv3
- ✅ Исходный код должен быть доступен
- ❌ Нельзя добавлять дополнительные ограничения

Полный текст лицензии доступен в файле [LICENSE](LICENSE).

<div align="center">

**Сделано с любовью к празднику и вниманием к деталям** 💗

*Если вам понравился проект — поставьте звезду на GitHub! ⭐*

</div>

---

## 🇬🇧 English version

### 🚀 Project Launch

#### Simple way
1. Go to the link: **[su57ks.github.io/8march/](https://su57ks.github.io/8march/)**
2. Enjoy the interactive greeting card! 🎉

#### Local launch
```bash
# Clone the repository
git clone https://github.com/su57ks/8march.git

# Go to the project folder
cd 8march

# Open index.html in your browser
# Or run a local server (e.g., with Live Server in VS Code)
```

#### Requirements
- Any modern browser (Chrome, Firefox, Safari, Edge)
- JavaScript enabled
- LocalStorage support

---

### 👥 Project Team

| Role | Name | Contact |
|------|------|---------|
| 👨‍💻 **Author** | Aizen | [@su57ks](https://t.me/su57ks) |
| 💡 **Ideas** | Santus | [@selyswag](https://t.me/selyswag) |
| 🧪 **Testers** | Amir, Lyosha and Yaroslava | — |
| 🙏 **Special thanks** | Egor E. and Denis S. | — |

---

### 📝 Project Description
**Interactive March 8 Greeting Card** is not just a static greeting, but a full-featured web application with game mechanics. Instead of a regular picture, the user gets an opportunity to interact with the content: collect virtual flowers, unlock new design themes, play mini-games, and read personalized congratulations.

The project is crafted with soul and attention to detail — every little thing, from petal animation to flower rain, is designed to create a festive mood.

---

### ✨ Key Features

| Category | Feature | Description |
|----------|---------|-------------|
| 🎨 **Interface** | Responsive Design | Full support for mobile, tablet, and desktop |
| | PWA-like experience | Works offline after loading, saves progress |
| | Custom modals | 10+ modal window types with unique design |
| 🎮 **Gameplay** | Clicker mechanic | Collect flowers by tapping the big flower |
| | Level system | Every 100 flowers — special greeting |
| | Compliments | Random compliments every 50 flowers |
| 💾 **Saves** | LocalStorage | Automatic progress saving |
| | Synchronization | Saves flowers, unlocked themes, used promo codes |
| 🎯 **Unlockables** | Progressive unlocking | New content available upon reaching goals |
| | Secret themes | 3 hidden themes unlocked via progress or promo codes |

---

### 🎮 Mini-games

#### Mini-games Comparison Table

| Feature | 🌼 Daisy Fortune | 🎰 "Bouquet" Casino | 🎡 Wheel of Fortune |
|---------|-----------------|---------------------|---------------------|
| **File** | `mini_games/chamomile.html` | `mini_games/casino.html` | `mini_games/bouquet.html` |
| **Cost** | 10🌸 | Free (access) / bet flowers | 10🌸 |
| **Mechanic** | Petal plucking | Bets on multipliers | Random flower |
| **Reward** | Predictions | x0, x0.1, x1.5, x2, x5, x11 | Flower emoji |
| **Sectors** | 9-12 petals | 8 sectors | 8 sectors |
| **Visualization** | CSS daisy | Canvas wheel | Canvas wheel |
| **Difficulty** | 🟢 Easy | 🔴 Gambling | 🟡 Random |

#### Detailed Description

**🌼 Daisy Fortune Telling** (`chamomile.html`)
- 9 to 12 petals on the flower
- 6 prediction options:
  - "Loves 💖"
  - "Doesn't love 🖤"
  - "Will spit 💧"
  - "Will kiss 💋"
  - "Will hug 🤗"
  - "Will send to hell 👿"
- Final prediction when the last petal is plucked
- "Fortune" button to restart
- Spin animation

**🎰 "Bouquet" Casino** (`casino.html`)
- Betting system with input field
- "Max" button for maximum bet
- 8 sectors with multipliers: 0, 0, 0.1, 0.1, 1.5, 2, 5, 11
- Physics-based spin with deceleration
- Result shown in modal window
- Flower rain on win

**🎡 Wheel of Fortune** (`bouquet.html`)
- 8 sectors with flowers: Sakura, Chamomile, Tulip, Hibiscus, Tulip, Rose, Sakura, Rose
- Flower names capitalized
- Rain of the corresponding flower on result
- Simple mechanic without bets

---

### 🎨 Color Themes

| Theme | Class | Color Scheme | Status | Gradient |
|-------|-------|--------------|--------|----------|
| **Pink** | `theme-default` | Pink-peach | 🔓 Default | `#fef3f8 → #ffeef4` |
| **White** | `theme-white` | Monochrome light | 🔓 Default | `#ffffff → #f5f5f5` |
| **Lilac** | `theme-lilac` | Lavender-lilac | 🔓 Default | `#f3e5f5 → #e1bee7` |
| **Bright Pink** | `theme-bright-pink` | Saturated pink | 🔓 Default | `#ffd0dd → #ffb0c5` |
| **Gold** | `theme-gold` | Golden-honey | 🔐 1000🌸 | `#fbf3e0 → #f5d0a0` |
| **Cosmic** | `theme-cosmic` | Purple cosmic | 🔐 Promo code `505` | `#0a0f1e → #2a1f4a` |
| **Dark Blue** | `theme-dark-blue` | Deep blue | 🔐 Promo code `1337` | `#0a1a2a → #0a1f4a` |

---

### 🔑 Promo Codes & Secrets

| Promo Code | Effect | Type |
|------------|--------|------|
| `1488` | 🚫 Progress reset (anti-Nazi message) | Penalty |
| `52` | 🏛️ +5200 flowers (St. Petersburg) | Bonus |
| `67` | 😕 +1 flower (joke) | Joke |
| `69` | 😏 +690 flowers | Joke |
| `1337` | 👾 +133700 flowers + dark blue theme | Secret |
| `505` | 🌟 +505812 flowers + cosmic theme | Secret |
| `МЫВАСЛЮБИМ` | 💖 +1 billion flowers | Easter egg |

**Hint in promo modal:** "For example 2.71828" (number e) — a math reference

---

### 📊 Progression System

```
Game Start
    ↓
Collect flowers (clicker)
    ↓
├── 50🌸 → Random compliment
├── 100🌸 → Achievement greeting
├── 500🌸 → All basic themes unlocked
└── 1000🌸 → Casino unlocked + Gold theme
         ↓
    Bottom navigation appears
         ↓
    ├── Main page
    └── Casino (bet flowers)
         ↓
    Win/lose opportunity
```

---

### 📁 Project Structure

```
📦 8march
├── 📄 index.html                          # Main file (all components)
├── 📁 themes/
│   ├── 🎨 base.css                         # Base styling
│   └── 🎨 themes.css                        # CSS variables for all themes
├── 📁 mini_games/
│   ├── 🎰 casino.html                       # Casino with multipliers
│   ├── 🌼 chamomile.html                     # Daisy fortune telling
│   └── 🎡 bouquet.html                       # Wheel of fortune
└── 📄 README.md                            # Documentation
```

---

### 🛠 Technologies

| Technology | Application |
|------------|-------------|
| **HTML5** | Page structure, semantic markup |
| **CSS3** | Styling, animations, media queries, CSS variables |
| **JavaScript (ES6+)** | Game logic, event handling, LocalStorage |
| **Canvas API** | Roulette wheel rendering |
| **LocalStorage** | User progress saving |
| **Flexbox/Grid** | Responsive layout |
| **CSS variables** | Dynamic theme switching |

---

### 📜 License

This project is licensed under the **GNU General Public License v3 (GPLv3)**.

```
                    GNU GENERAL PUBLIC LICENSE
                       Version 3, 29 June 2007

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
```

**Key GPLv3 provisions:**
- ✅ You may use, modify and distribute the code
- ✅ You must preserve copyright notices
- ✅ Modified versions must also be distributed under GPLv3
- ✅ Source code must be made available
- ❌ You may not add additional restrictions

The full license text is available in the [LICENSE](LICENSE) file.

<div align="center">

**Made with love for the holiday and attention to detail** 💗

*If you like the project — give it a star on GitHub! ⭐*

[⬆ Back to top](#-интерактивная-открытка-к-8-марта--interactive-march-8-greeting-card)

</div>
