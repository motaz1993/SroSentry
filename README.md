# SroSentry

Desktop helper for **Silkroad Online private servers**.
Multi-account monitoring, auto-login, alarms and live character stats.

**Author:** Touched

Support for more private servers is planned.

---

## Features

### Characters
- Character list with online status, drag to re-order
- Add (single or bulk), edit, delete
- Per-character options: Auto login, Auto hunt after login, Hide client after login
- Start / stop the auto login system, start / kill / hide selected clients

### Live info
- Name, level, region, position
- HP / MP / EXP bars
- Gold, arrows, pet time (when the game values can be read)

### Alarms (per character)
- No HP potions, no MP potions
- Out of arrows
- Not getting EXP
- Dead with no revive
- Disconnected
- Level up
- Reach target level
- Optional: mute all alarms while you are using the PC

### Event alerts
- Event schedule with a time-left countdown for every event
- Alerts when an event starts or 10 / 5 / 1 minutes before
- Sound and Windows notifications, mute single events
- Time offset setting if the schedule is off by an hour

### Auto update game (beta)
- If clients keep closing right after they start, the tool can close them, run the game launcher so it patches, and start your clients again

### App
- Dark / Light / Bronze themes, remembers its window size
- Minimize to tray, Potato PC mode, start with Windows
- Tooltips on every option
- Updates itself: checks GitHub once a day when it starts

---

## Requirements
- Windows 10 / 11
- .NET Framework 4.8
- Run as administrator (the tool reads game memory)

## Install
1. Put `SroSentry.exe` in your game folder, next to `SroMacroClient.exe`.
2. Run `SroSentry.exe`. Your settings are saved in `accounts.txt` and `config.txt` in that folder.

## Antivirus note
SroSentry reads another program's memory (your game client), so some antivirus programs warn about it. Download it only from this page. You may need to add the game folder as an exclusion.

## Notes
- For personal use with your own accounts on private servers you play.
- After big client patches, memory addresses can change and a new version may be needed.

## License
See [LICENSE](LICENSE). All rights reserved.
