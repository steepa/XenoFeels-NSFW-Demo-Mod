# Custom Intro Screens v2 — XenoFeels Demo NSFW Mod

Кастомные заставки для XenoFeels Demo. 
Custom intro screens for XenoFeels Demo. 
<img width="1576" height="962" alt="3-1784404482-1653486786 png" src="https://github.com/user-attachments/assets/5626e0da-dbca-492a-94c5-367ae0533670" />

⚠️ Автор оригинальных базовых артов мода: Kota Mota Games, я лишь выполнил их дорисовку и адаптацию. Графика не является моей собственной разработкой.

⚠️ Original core art by Kota Mota Games. I only edited and retouched the artwork; base visuals are not original to me.
---
The mod is available on the Discord server - https://discord.gg/WeSFeaeE9
мод находиться на сервере в дискорде - https://discord.gg/WeSFeaeE9
---

## Скачать / Download

Download the repository from Discord: https://discord.gg/WeSFeaeE9

---

## Требования / Requirements

- Python 3.8+
- Библиотека UnityPy:
```bash
pip install UnityPy Pillow
```

---

## Установка / Installation

### 1. Подготовка

Скопируй оригинальные ассеты из папки игры:
```
...\XenoFeels Demo\XenoFeels_Data\
```

Скопируй эти файлы в папку `original/` этого репозитория:
```
sharedassets4.assets
sharedassets4.assets.resS
```

### 2. Запуск патчера

```bash
python patch.py
```

Скрипт заменит текстуры и создаст патченные файлы в папке `output/`.

### 3. Установка

Скопируй файлы из `output/` в папку игры:
```
...\XenoFeels Demo\XenoFeels_Data\
```

Замени оригинальные файлы:
```
sharedassets4.assets
sharedassets4.assets.resS
```

### 4. Запусти игру

---

## Удаление / Uninstall

Верни оригинальные файлы из `original/` в папку игры.


## Соцсети автора игры / Game Author Socials
-  KotaMota Games
- **Steam:** https://store.steampowered.com/developer/kota_mota?l=russian
- **Discord сервер:** https://discord.gg/8BUuvbA4Mu
- **X (Twitter)**	https://x.com/KotaMotaa 
- **Telegram**	https://t.me/kotamotaclub 
- **Patreon**	https://www.patreon.com/KotaMotaGames 
- **Boosty**	https://boosty.to/kotamotagames 
- **YouTube**	https://www.youtube.com/@KOTOBYXA 
## Структура / Structure

```
MOD_Intro_v2/
├── textures/          # PNG текстуры для замены
│   ├── intro_general6_1.PNG
│   ├── intro_general6_2.PNG
│   ├── intro_general6_3.PNG
│   ├── intro_general7_1.PNG
│   ├── intro_general7_2.PNG
│   └── intro_general7_3.PNG
├── original/          # Оригинальные ассеты (сюда копируешь свои)
├── output/            # Патченные файлы (создается скриптом)
├── patch.py           # Скрипт патчинга
├── README.md
└── index.html

