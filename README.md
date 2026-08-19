# Render-Bot-for-Discord-Server-Owners-Ark
A Discord bot for ARK tribes to manage base render timers, track material decay tiers, and send alert notifications.
# ARK Base Render & Decay Tracker

A Discord slash-command bot designed for ARK: Survival Evolved & Ascended tribes to track base render timestamps and structure decay across multiple servers and maps.

## Features
* 🏰 **Visual Map Cards**: Displays embed cards with image previews, server numbers, and decay timers.
* 🔄 **Reaction Refresh**: Simple one-click reaction (`🔄` or `🦖`) updates the render timestamp instantly.
* 🚨 **Decay Warnings**: Background checker alerts admins when base timers drop below 2 days.
* 🗺️ **Dynamic Maps**: Add or remove specific maps/servers on the fly using slash commands.
* ⏱️ **Material Tiers**: Supports Stone (12d), Metal (16d), and Tek (20d) decay rates.

---

## Setup Instructions

### 1. Prerequisites
* Python 3.8 or higher installed on your system.
* A Discord Bot Token from the [Discord Developer Portal](https://discord.com/developers/applications).
* **Bot Permissions Needed**:
  * `Send Messages`
  * `Embed Links`
  * `Manage Messages` (for deleting inactive cards)
  * `Add Reactions`
  * `Read Message History`
  * **OAuth2 Scope**: Select `bot` AND `applications.commands`.

---

### 2. Installation

1. **Clone or Download the Repository**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/ark-render-bot.git](https://github.com/YOUR_USERNAME/ark-render-bot.git)
   cd ark-render-bot
