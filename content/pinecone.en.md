---
title: "Pinecone (Minecraft launcher)"
subtitle: "Install it, play offline singleplayer, and join the server"
---

**PineconeMC** is a **free** Minecraft launcher, a fork of **Prism Launcher** (formerly ElyPrismLauncher). It supports **offline** and **Ely.by** accounts (no Microsoft account needed) — perfect for our server, which runs in **offline mode**.

> Official download: **[pineconemc.com/download](https://pineconemc.com/download)** (or [pineconemc.org](https://pineconemc.org/download)). Only download from these sites.

## 1. Installation

1. Download the **portable** build (recommended) for your OS: **Windows 10+**, **Linux** or **macOS**.
2. Extract the archive anywhere and run the executable — no install needed.
3. On first run, let Pinecone download **Java** automatically (or point it to a Java 21+ in *Settings → Java*).

## 2. Create an offline account

1. Top right: **Accounts** → **Add offline account**.
2. Pick a **nickname** (no spaces) — this is your in-game name.
3. *(Optional)* Add an **Ely.by** account to show a skin.
4. Tick the account to activate it.

## 3. Launch Minecraft

1. **Add Instance** → choose a version. Our server is **Paper 26.2**; older versions also work thanks to **ViaVersion/ViaBackwards**.
2. Name the instance (e.g. “Retro”) and confirm.
3. Select it and press **Play**. The first launch downloads the version and assets (may take a few minutes).

## 4. Play offline singleplayer

- In game: **Singleplayer** → **Create New World** → play.
- **No internet or Microsoft account** required. Your worlds stay local (the instance’s folder button opens the directory).

## 5. Join our server

1. In game: **Multiplayer** → **Add Server**.
2. Enter:
   - **Name:** `New World`
   - **Address:** `192.168.1.109:25565`
3. The server also shows in the **LAN** tab (thanks to LANBroadcaster).
4. The server is in **offline mode**: your offline account just works.
5. In game: `/lobby` returns to the hub, then take a **portal** to the minigames (BedWars, OneBlock, Parkour, Creative).

> 🔒 Public address (`mc.girard-davila.net`): **coming later**. The server is currently reachable on the **local network** only.

## Troubleshooting

- **Version download stuck**: your ISP may block the servers; try a VPN.
- **“This app can't run on your PC”**: wrong CPU architecture (ARM64 vs x64) — grab the right file.
- **Black screen / no sound**: check Java (*Settings → Java*) and the allocated RAM.
- **Server not showing up**: are you on the same `192.168.1.x` network? Otherwise add it manually (step 5).
