# 🔔 BleePo — Innovative Discord Notification Platform

<p align="center">
  <img src="https://via.placeholder.com/800x400/1e1e2e/bb9af7?text=BleePo+Dashboard" alt="BleePo Banner" width="100%" style="border-radius: 16px;" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Next.js-15-black?style=for-the-badge&logo=nextdotjs" alt="Next.js" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-4.2-06B6D4?style=for-the-badge&logo=tailwindcss" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/MongoDB-Shared-47A248?style=for-the-badge&logo=mongodb" alt="MongoDB" />
  <img src="https://img.shields.io/badge/Discord.js-14.x-5865F2?style=for-the-badge&logo=discord" alt="Discord.js" />
</p>

---

## 🚀 About the Project

**BleePo** is a comprehensive ecosystem tailored for content creators and demanding communities. It seamlessly connects **Twitch** and **YouTube** activity directly to Discord servers with near-zero latency.

The project architecture is divided into three major components:
1. **Frontend / Backend (Web):** A modern, sleek One-Page website built with Next.js 15, featuring a secure authentication system via Discord OAuth2 and an intuitive user dashboard.
2. **Core Alert Bot:** The heart of the system that monitors streaming/video APIs and dispatches highly customizable notifications to client servers.
3. **Support & Moderation Bot:** A dedicated bot operating on the official support Discord server (handling ticketing, automatic moderation, and real-time Premium role synchronization via a shared MongoDB database).

---

## ✨ Key Features

- ⚡ **Zero Latency:** Instant detection of live streams and newly published videos.
- 🎨 **Highly Customizable:** Fully adapt alert messages, mentions, destination channels, and craft 100% custom Discord Embeds (for Essential & Elite tiers).
- 🔄 **Fluid One-Page Architecture:** Optimized web navigation utilizing smooth scrolling without page reloads for a premium user experience.
- 💳 **Monetization & Role Sync:** A direct link between the website's MongoDB database and the support bot to instantly grant VIP/Premium roles upon purchase on the official Discord server.

---

## 🛠️ Tech Stack

### Web Application (Client & API)
* **Framework:** Next.js 15 (App Router)
* **Styling:** Tailwind CSS & Shadcn/ui
* **Icons:** Lucide React

### Database & Infrastructure
* **Database:** MongoDB (via Mongoose)
* **Authentication:** Discord OAuth2 SDK

### Discord Bots
* **Runtime Environment:** Node.js / TypeScript
* **Library:** Discord.js v14

---

👥 Team & Support
- Lead Developer: samuelba._.
- Official Support Server: [Join our Discord](https://discord.gg/B8pyYPAzpS)
