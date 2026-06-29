# SparkleMC

A Minecraft launcher built with Electron, React, and Material UI.

> **License:** This software is provided under a custom EULA. Redistribution, modification, or reverse engineering is prohibited without explicit permission from the author.

## Features

- **Multiple account types** — Microsoft OAuth, Ely.by OAuth, and offline mode
- **authlib-injector** — automatic download and injection for Ely.by authentication
- **Mod loader support** — Fabric installation for any Minecraft version
- **Java management** — auto-detect, compatibility checking, and Adoptium installation
- **Instance system** — separate game directories with per-instance Java and memory settings
- **Version manager** — browse, download, verify, and repair Minecraft versions
- **Material UI 3** — expressive dark/light theme with modern design
- **Console output** — real-time game log viewer with fade-in animations

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React 19, Material UI 7, Zustand, React Router |
| Backend | Electron 35, Node.js |
| Bundler | electron-vite, Vite 6 |
| Language | TypeScript 5 |

## Development

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Type-check
npm run typecheck

# Build for production
npm run build

# Package for Windows
npm run build:win

# Package for Linux
npm run build:linux
```

## Account Setup

### Microsoft
Click the **Microsoft** button in Accounts — opens a browser window for OAuth login.

### Ely.by
Click the **Ely.by** button — opens the Ely.by OAuth page.

### Offline
Click the **Offline** button — enter any username for local/unlicensed play. Works on servers with `online-mode=false`.

## Author

**SparkleSavvy** — [GitHub](https://github.com/SparkleSavvy)
