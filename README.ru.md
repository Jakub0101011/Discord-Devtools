[EN](README.md) | [PL](README.pl.md) | RU

# Описание
Если Вы хотите включить devtools в Discord, откройте файл:
  1. Windows: "%USER%\\AppData\\Roaming\\Discord\\settings.json"
  2. Linux: может быть в разных местах ("/var/app/discord/config/discord", "~/.var/app/com.discordapp.Discord/config/discord" и т.д.); попробуйте `find /var/app -name "settings.json"` и `find ~/.var/app -name "settings.json"`

и вставьте `, "DANGEROUS_ENABLE_DEVTOOLS_ONLY_ENABLE_IF_YOU_KNOW_WHAT_YOURE_DOING": true`

После чего перезайдите в Discord (через иконку в трее). После этого вы сможете открыть devtools с помощью хоткея `Ctrl + Shift + i`.

![tools](https://user-images.githubusercontent.com/94227436/15627004-baf4e4ac-3b95-4cde-bc83-2ce5a1ac575f.PNG)

# Settings.json
```json
{
  "BACKGROUND_COLOR": "#202225",
  "IS_MAXIMIZED": false,
  "IS_MINIMIZED": false,
  "WINDOW_BOUNDS": {
    "x": 375,
    "y": 134,
    "width": 1264,
    "height": 705
  },
  "DANGEROUS_ENABLE_DEVTOOLS_ONLY_ENABLE_IF_YOU_KNOW_WHAT_YOURE_DOING": true
}
```

# Примечание от Discord
DANGEROUS, ENABLE DEVTOOLS ONLY ENABLE IF YOU KNOW WHAT YOU'RE DOING

(перевод: ОПАСНО, ВКЛЮЧИТЬ DEVTOOLS. ВКЛЮЧАЙТЕ ТОЛЬКО ЕСЛИ ВЫ ЗНАЕТЕ ЧТО ВЫ ДЕЛАЕТЕ)

