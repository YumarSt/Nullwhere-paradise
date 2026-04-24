<div align="center">

# MiyMods
## Модпак для Minecraft 1.21.1 (NeoForge)

[![NeoForge](https://img.shields.io/badge/NeoForge-1.21.1-blue?logo=curseforge&logoColor=white)](https://neoforged.net/)
[![Minecraft](https://img.shields.io/badge/Minecraft-1.21.1-green?logo=minecraft&logoColor=white)](https://minecraft.net)
[![Memory](https://img.shields.io/badge/ОЗУ-6--8ГБ-orange)](https://ru.wikipedia.org/wiki/%D0%9E%D0%BF%D0%B5%D1%80%D0%B0%D1%82%D0%B8%D0%B2%D0%BD%D0%B0%D1%8F_%D0%BF%D0%B0%D0%BC%D1%8F%D1%82%D1%8C)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)

**Техническая сборка основанная на Create | Исследование биомов и данжей | Летательные аппараты**

</div>

---

## 📋 Содержание
- [Системные требования](#-системные-требования)
- [Быстрая установка](#-быстрая-установка)
- [Подробная установка](#-подробная-установка)
- [Полный список модов](#-полный-список-модов)

---

## 💻 Системные требования

| Компонент | Минимальные | Рекомендуемые |
|:----------|:------------|:---------------|
| **ОЗУ (игроку)** | 12 ГБ (выделить 6 ГБ) | 16 ГБ (выделить 8 ГБ) |
| **ОЗУ (серверу)** | 6 ГБ | 8-10 ГБ (на 5-6 игроков) |
| **Процессор** | Intel Core i5 / AMD Ryzen 5 | Intel Core i7 / AMD Ryzen 7 |
| **Видеокарта** | GTX 1050 / RX 560 | GTX 1660 / RTX 2060 |
| **ОС** | Windows 10 / 11 / macOS / Linux | — |

> ⚠️ **Важно:** Без выделения 6-8 ГБ ОЗУ игра будет вылетать с ошибкой `OutOfMemoryError`!

---

## ⚡ Быстрая установка

1. Скачайте и установите **[NeoForge 1.21.1](https://neoforged.net/)**
2. Скачайте все моды из zip архива
3. Поместите `.jar` файлы в папку `mods` (`.minecraft/mods`)
4. Выделите **6-8 ГБ памяти** в настройках лаунчера
5. Запустите игру с профилем NeoForge

---

## 📖 Подробная установка

<details>
<summary><b>🔧 Установка NeoForge (нажмите, чтобы развернуть)</b></summary>

1. Перейдите на [официальный сайт NeoForge](https://neoforged.net/)
2. Выберите версию **1.21.1** и скачайте установщик
3. Запустите `.jar` файл
4. Выберите **«Install client»** (установка клиента)
5. Укажите путь к папке `.minecraft` (обычно выбран автоматически)
6. Нажмите **«OK»** и дождитесь завершения установки
</details>

<details>
<summary><b>💾 Выделение памяти (JVM аргументы)</b></summary>

**Стандартный лаунчер Minecraft:**
- Откройте лаунчер → вкладка **«Установки»**
- Наведите на профиль NeoForge → три точки → **«Изменить»**
- Нажмите **«Дополнительные параметры»**
- Найдите в поле **«JVM аргументы»** строку `-Xmx2G`
- Замените `2` на `6` или `8` (например: `-Xmx6G`)
- Нажмите **«Сохранить»**

**CurseForge Launcher:**
- Откройте настройки (шестерёнка внизу слева)
- Перейдите в **Minecraft → Java Settings**
- Передвиньте слайдер **«Allocated Memory»** на 6144 MB (6 ГБ) или 8192 MB (8 ГБ)
</details>

---

## 📦 Полный список модов

### 🔧 Create и Create like моды

| Мод | Ссылка | Описание |
|:----|:-------|:---------|
| **Create** | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/create) | Основа сборки — механизмы, вращение, автоматизация |
| **Create: Aeronautics** | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/create-aeronautics) | Летательные аппараты с физикой (дирижабли, самолёты) |
| **Sable** | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/sable) | Библиотека физики (необходима для Aeronautics) |
| **Copycats+** | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/create-copycats-plus) | Декоративные блоки-копии для красивого дизайна |
| **Enchantment Industry** | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/create-enchantment-industry) | Автоматизация зачарований (жидкий опыт) |

---

### 🌍 Биомы и генерация мира

| Мод | Ссылка | Описание |
|:----|:-------|:---------|
| **Terralith** | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/terralith) | Эпичная переработка ландшафта — горы, каньоны, плато |
| **Regions Unexplored** | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/regions-unexplored) | 70+ новых биомов с уникальной растительностью |
| **TerraBlender** | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/terrablender) | Библиотека для совместимости модов на биомы |
| **Nature's Compass** | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/natures-compass) | Компас для поиска любых биомов |

---

### ⚡ Технические аддоны Create ???????

| Мод | Ссылка | Описание |
|:----|:-------|:---------|
| **Crafts & Additions** | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/createaddition) | Электричество — провода, генераторы, аккумуляторы |
| **Steam 'n' Rails** | [GitHub](https://github.com/Porters-of-Railways/Railway-1.21.1) | Улучшенные поезда и рельсы |
| **Connected** | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/create-connected) | Умные механизмы — сцепления, батареи, коробки передач |
| **Stuff 'N Additions** | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/create-stuff-additions) | Джетпаки, бур, дроны, экзоскелеты |
| **Molten Vents** | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/create-molten-vents) | Вулканические жерла для добычи руд |


---
<!--
### 🏛️ Структуры и приключения

| Мод | Ссылка | Описание |
|:----|:-------|:---------|
| **AdoraBuild: Structures** | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/adorabuild-structures) | 100+ новых структур по всему миру |
| **CTOV** | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/ctov) | Полная переработка деревень под каждый биом |
| **YUNG's Better Dungeons** | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/yungs-better-dungeons) | Улучшенные подземелья |
| **YUNG's API** | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/yungs-api) | Библиотека для модов YUNG |
| **Explorations** | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/explorations) | Небольшие руины и постройки |
| **L_Ender's Cataclysm** | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/l-enders-cataclysm) | Мощные боссы и эпические сражения |
| **Alex's Mobs** | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/alexs-mobs) | 70+ новых животных по всему миру |

---
-->
### 🔧 Моды для удобства (QoL)

| Мод | Ссылка | Описание |
|:----|:-------|:---------|
| **JEI** | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/jei) | Показывает все рецепты крафта |
| **Jade** | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/jade) | Информация о блоках под прицелом |
| **JourneyMap** | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/journeymap) | Карта мира с отметками |

---

### ⚡ Оптимизация

| Мод | Ссылка | Описание |
|:----|:-------|:---------|
| **Sodium** | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/sodium) | Повышает FPS и оптимизирует рендеринг |
| **FerriteCore** | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/ferritecore) | Снижает потребление оперативной памяти |

---

