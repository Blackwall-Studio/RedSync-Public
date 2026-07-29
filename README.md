# 🔴 RedSync

**Multiplayer Mod for Cyberpunk 2077**

RedSync brings full cooperative and competitive multiplayer to Cyberpunk 2077 — a game that was never designed for online play. Built from the ground up with custom netcode, dedicated server infrastructure, and seamless player synchronization.

> **⚠️ PUBLIC MIRROR** — This is a public-facing mirror of the active development repository. For the full source, build instructions, and latest builds, please visit our [Discord server](https://discord.gg/redsync).

## Features

### Gameplay
- **Full Co-Op Campaign** — Experience Night City's story with friends. Shared quest progression, loot, and exploration
- **Competitive Modes** — Arena combat, races, and custom game modes
- **Seamless Synchronization** — Custom netcode ensures smooth player movement, combat, and world interaction
- **Proximity Voice Chat** — Built-in spatial voice communication

### Technical
- **Custom Client-Server Architecture** — All multiplayer logic runs through dedicated servers — no P2P hacks
- **C++ Networking Core** — Low-latency synchronization engine for real-time gameplay
- **Dedicated Server** — .NET 9 server with Docker support for 24/7 hosting
- **Anti-Cheat** — Built-in detection and prevention systems
- **Admin Tools** — In-game admin panels, player management, and event triggers (Project Smasher, Cerberus)
- **Auto-Healing Watchdog** — Crash detection and automatic server restart

## Getting Started

### Players
1. Download the [RedSync Launcher](https://github.com/Blackwall-Studio/RedSync-Public)
2. Install and launch — the launcher handles mod installation, updates, and server browsing
3. Click "Jack In" and connect to any server

### Server Hosts
```bash
# Docker (recommended)
docker pull blackwallstudio/redsync-server
docker run -p 7777:7777 blackwallstudio/redsync-server

# Manual
# See server documentation for configuration options
```

## Project Structure

| Component | Description |
|---|---|
| RedSync Launcher/ | Avalonia UI (.NET) desktop launcher for mod installation, updates, and server browsing |
| server/ | .NET 9 dedicated server with C++ networking, admin panels, combat events, voice chat |
| client/ | RED4ext plugin for Cyberpunk 2077 — hooks game engine for multiplayer support |
| release/ | Build scripts, deployment tooling, and release artifacts |

## Community

- [Discord](https://discord.gg/redsync) — Development updates, server listings, support
- [GitHub Issues](https://github.com/Blackwall-Studio/RedSync-Public/issues) — Bug reports and feature requests

## License

See LICENSE file in repository root.

---

*Built by Blackwall Studio — Extending the Lives of Games.*
