# SroSentry

Desktop helper for **Silkroad Online private servers**.  
Multi-account monitoring, auto-login, alarms, and live character stats.

**Author:** Touched  
**Current version:** 1.5

Support for additional private servers is planned.

---

## Features

### Accounts
- Account list (username / character)
- Add / Edit / Delete accounts
- Per-character options:
  - Auto Login
  - Auto Hunt
  - Auto Hide
- **Start / Stop Auto Login** (green = start, red = stop)
- **Auto Login on Launch** — starts the system when the tool opens
- **Startup with Windows** — runs with Windows

### Character info
- Name, level, region, position
- HP / MP / EXP bars
- Gold
- Pet time
- Arrows status
- Client version when the client is running

### Alarms (per character)
- No HP pots
- No MP pots
- No arrows
- EXP stuck
- Dead with no revive
- Disconnected
- Level-up
- Reach target level (checkbox + level box)

### Events
- Event alert window
- Schedule loading with fallback
- Optional sound / popup alerts

### App settings (global)
- Theme: Default (Bronze) / Light / Dark
- Minimize to tray
- Potato PC mode
- Combined log at the bottom of the main window

### Other
- Single-instance app
- Tray icon
- Settings in `config.txt` (app) and `accounts.txt` (per character)

---

## Requirements
- Windows
- .NET Framework 4.8
- Compatible game client on the same machine

## Run
1. Place `SroSentry.exe` in your working folder (with `accounts.txt` / `config.txt` as needed).
2. Run `SroSentry.exe`.

## Notes
- For personal use with your own accounts on private servers you play.
- Client updates may change memory layouts; a new build may be required after major client patches.

## License
See [LICENSE](LICENSE). All rights reserved.