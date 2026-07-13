## Tiny tools for home labs

Small, single-purpose utilities I built to run my own setup: a retro arcade cabinet, a TrueNAS/Plex media server, a smart home, and a rack that needs to stay quiet. All MIT, all documented, all things I actually run daily.

### 🕹️ Batocera / retro arcade
- **[batocera-toolbox](https://github.com/t3chnaztea/batocera-toolbox)** — Couch-friendly, gamepad-driven utility menu: backup/restore, ROM audit, 1G1R dedup, version-aware BIOS check, shaders, run-ahead, RetroAchievements.
- **[batocera-skills](https://github.com/t3chnaztea/batocera-skills)** — Agent skills + Claude Code plugin for running a Batocera cabinet with a coding agent: SSH ops, ROM/gamelist curation, shaders & bezels, performance tuning, maintenance.
- **[batocera-holidays](https://github.com/t3chnaztea/batocera-holidays)** — Config-driven seasonal ROM rotation. Un-hides themed games in season so attract-mode shows them, re-hides them after.
- **[HA-Batocera](https://github.com/t3chnaztea/HA-Batocera)** — Home Assistant integration over MQTT: live gaming, system, and session stats.

### 🎮 PlayStation
- **[awesome-psnstats](https://github.com/t3chnaztea/awesome-psnstats)** — Export your PS4/PS5 play history to CSV/JSON and build an AI-ready taste profile: per-game enjoyment scoring, five player traits, and a `preferences.json` an AI agent can use for recommendations. Local-first CLI, NPSSO never leaves your machine (`pipx install awesome-psnstats`).

### 🖥️ Home server
- **[home-assistant-skills](https://github.com/t3chnaztea/home-assistant-skills)** — Agent skills + Claude Code plugin for running a Home Assistant smart home with a coding agent: SSH/REST connection doctrine, instance mapping, verified automations, price- and LLM-driven triggers.
- **[dell-ipmi-fan-control](https://github.com/t3chnaztea/dell-ipmi-fan-control)** — Temperature-based IPMI fan control for Dell PowerEdge. Quiet your R-series in a closet.
- **[plex-preroll-roulette](https://github.com/t3chnaztea/plex-preroll-roulette)** — Weighted-random Plex pre-roll bumpers: occasionally arm a surprise movie intro (FBI warning, feature presentation, countdown).

### 💻 Desktop
- **[fastfetch-macos-gradient-hud](https://github.com/t3chnaztea/fastfetch-macos-gradient-hud)** — macOS fastfetch HUD with per-cell gradient usage/temp bars, rainbow volume, and now-playing. One cached spawn feeds six live readings.
