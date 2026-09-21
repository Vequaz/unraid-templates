# Unraid Templates

Central repository for my Unraid Docker templates and icons.

## Applications

| Application | Template | Icon |
| --- | --- | --- |
| Anime-Loads | `templates/anime-loads.xml` | `icons/anime-loads.png` |
| Anime-Watcher | `templates/anime-watcher.xml` | `icons/anime-watcher.png` |
| AnimeL Telegram | `templates/animel-telegram.xml` | `icons/animel-telegram.png` |

## Raw template URLs

- https://raw.githubusercontent.com/Vequaz/unraid-templates/main/templates/anime-loads.xml
- https://raw.githubusercontent.com/Vequaz/unraid-templates/main/templates/anime-watcher.xml
- https://raw.githubusercontent.com/Vequaz/unraid-templates/main/templates/animel-telegram.xml

## Raw icon URLs

- https://raw.githubusercontent.com/Vequaz/unraid-templates/main/icons/anime-loads.png
- https://raw.githubusercontent.com/Vequaz/unraid-templates/main/icons/anime-watcher.png
- https://raw.githubusercontent.com/Vequaz/unraid-templates/main/icons/animel-telegram.png

## Structure

```text
unraid-templates/
├── icons/
│   ├── anime-loads.png
│   ├── anime-watcher.png
│   └── animel-telegram.png
├── templates/
│   ├── anime-loads.xml
│   ├── anime-watcher.xml
│   └── animel-telegram.xml
└── README.md
```

The XML templates reference the icons from this repository directly, so Unraid can load them through `raw.githubusercontent.com`.
