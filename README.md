EN | [PL](README.pl.md) | [RU](README.ru.md)

# Description
If you want to enable devtools features you have to go to:
  1. Windows: "%USER%\\AppData\\Roaming\\Discord\\settings.json"
  2. Linux: it may be in different places ("/var/app/discord/config/discord", "~/.var/app/com.discordapp.Discord/config/discord" and others); try `find /var/app -name "settings.json"` and `find ~/.var/app -name "settings.json"`
and paste there `, "DANGEROUS_ENABLE_DEVTOOLS_ONLY_ENABLE_IF_YOU_KNOW_WHAT_YOURE_DOING": true`

And reset the entire discord. When restarting the program, you will get "devtools"
after receiving, you can turn on with hotkey `Ctrl + Shift + i`.

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

## Annotation from discord:
DANGEROUS, ENABLE DEVTOOLS ONLY ENABLE IF YOU KNOW WHAT YOU'RE DOING


