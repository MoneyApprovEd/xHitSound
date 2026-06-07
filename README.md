# xHitSound

A lightweight Minecraft Paper/Spigot 1.20+ plugin that allows players to choose custom sound effects when they hit other entities. Fully configurable and permission-based.

## Features

- **15 Hit Sounds** across 5 categories (PvP Classics, High-Tech & Anime, Retro Arcade, Heavy Bass & Impact, Funny Memes)
- **54-Slot GUI** with border frame, status indicator, mute button, and close button
- **Permission-Based Access** — grant individual sounds or use `xhitsound.use.*`
- **100% Translatable** — every message, item name, and lore is in `config.yml`
- **Reload Command** — `/hitsound reload` to apply config changes without restarting

## Commands

| Command | Permission | Description |
|---|---|---|
| `/hitsound` | `xhitsound.use` | Opens the hit sound selection GUI |
| `/hs` | `xhitsound.use` | Alias for `/hitsound` |
| `/hitsound reload` | `xhitsound.reload` | Reloads config.yml |

## Permissions

| Permission | Default | Description |
|---|---|---|
| `xhitsound.use` | `true` | Allows using `/hitsound` command |
| `xhitsound.reload` | `op` | Allows reloading the config |
| `xhitsound.use.*` | `op` | Grants all hit sounds |
| `xhitsound.use.orb` | `op` | Classic Experience Orb |
| `xhitsound.use.ding` | `op` | Competitive Ding |
| `xhitsound.use.crit` | `op` | Bone Fracture (Crit) |
| `xhitsound.use.laser` | `op` | Laser Beam |
| `xhitsound.use.teleport` | `op` | Ender Zap |
| `xhitsound.use.magic` | `op` | Amethyst Spark |
| `xhitsound.use.click` | `op` | Retro Arcade Click |
| `xhitsound.use.level` | `op` | Arcade Level Up |
| `xhitsound.use.anvil` | `op` | Heavy Anvil Drop |
| `xhitsound.use.bass` | `op` | Subwoofer Bass |
| `xhitsound.use.glass` | `op` | Glass Shatter |
| `xhitsound.use.villager` | `op` | Angry Villager |
| `xhitsound.use.ghast` | `op` | Screaming Ghast |
| `xhitsound.use.slime` | `op` | Squishy Slime |
| `xhitsound.use.plink` | `op` | Plink Note |

### Granting all sounds to everyone

```
# Using LuckPerms:
/lp group default permission set xhitsound.use.* true
```

## Configuration

Edit any text field in `config.yml` to customize messages, item names, lores, and sounds. Run `/hitsound reload` after editing.

## Installation

1. Place the `xHitSound-1.0.0.jar` in your server's `plugins/` folder
2. Restart your server
3. Edit `plugins/xHitSound/config.yml` to customize
4. Run `/hitsound reload`

## Requirements

- **Server:** Paper 1.20.4+ (Spigot also supported)
- **Java:** 17 or higher

## License

MIT License

## Author

EMIRLQQ1
