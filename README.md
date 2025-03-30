# Nieuserver - Game Server Hosting Portal

[![Website](https://img.shields.io/badge/Visit-nieuserver.online-blue?style=for-the-badge&logo=internet-explorer)](https://nieuserver.online)
![GitHub last commit](https://img.shields.io/github/last-commit/yourusername/nieuserver?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

![Nieuserver Banner](assets/images/banner.png) <!-- Replace with your actual banner path -->

Official website for Nieuserver's game hosting services, featuring Minecraft and Terraria servers.

## 🌐 Live Demo
[https://nieuserver.online](https://nieuserver.online)

## 🎮 Server Status
| Server      | Status | Version | IP Address |
|-------------|--------|---------|------------|
| Minecraft   | ![Online](https://img.shields.io/badge/Online-00ff00?style=flat-square) | 1.20.1 | `play.nieuserver.online` |
| Terraria    | ![Online](https://img.shields.io/badge/Online-00ff00?style=flat-square) | 1.4.4 | `terraria.nieuserver.online` |

## 🚀 Features
- Real-time server status monitoring
- One-click IP copy functionality
- Responsive design (desktop & mobile)
- Server rules and documentation
- Player statistics display
- Maintenance announcements

## 🛠️ Tech Stack
**Core:**
- Astro (Static Site Generator)
- HTML5 / CSS3 / JavaScript
- Tailwind CSS

**Integrations:**
- Minecraft Server Query API
- Terraria Status Checker
- Discord Webhook (for notifications)

## 📂 Project Structure
```bash
src/
├── components/       # Reusable UI components
│   ├── ServerCard.astro
│   ├── StatusBadge.astro
│   └── Navbar.astro
├── layouts/          # Page layouts
├── pages/           # Website routes
│   ├── index.astro   # Homepage
│   ├── rules.astro
│   └── contact.astro
├── styles/           # Global styles
└── scripts/          # JS utilities
