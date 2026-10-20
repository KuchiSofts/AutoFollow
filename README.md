# AutoFollow has moved

> **AutoFollow now lives on as [VoiceChatFollower](https://github.com/KuchiSofts/BetterDiscord-Plugins#voicechatfollower)** in the [KuchiSofts/BetterDiscord-Plugins](https://github.com/KuchiSofts/BetterDiscord-Plugins) repository.

This repository never shipped a working plugin, and its `AutoFollow.plugin.js` was an empty placeholder. Everything AutoFollow was meant to do, following a user from voice channel to voice channel, is available in **VoiceChatFollower**, which is maintained there.

[![License: GPL-3.0](https://img.shields.io/badge/license-GPL--3.0-blue.svg)](LICENSE)
[![BetterDiscord](https://img.shields.io/badge/BetterDiscord-plugin-3a71c1.svg)](https://betterdiscord.app)

**[Download VoiceChatFollower.plugin.js](https://raw.githubusercontent.com/KuchiSofts/BetterDiscord-Plugins/main/VoiceChatFollower.plugin.js)**

## What VoiceChatFollower does

- Right-click a user and tick **Follow User** to start following them.
- You join their voice channel right away and move with them whenever they switch channels.
- Following stops by itself if they stay out of voice past a configurable timeout, or when you untick **Follow User**.
- Toast notifications tell you who you're following and when you're moved.
- Settings (check interval, inactivity timeout) are saved automatically.

## Installation

1. Install [BetterDiscord](https://betterdiscord.app).
2. Download [VoiceChatFollower.plugin.js](https://raw.githubusercontent.com/KuchiSofts/BetterDiscord-Plugins/main/VoiceChatFollower.plugin.js) and keep the file name.
3. Open **User Settings > Plugins > Open Plugins Folder** and move the file there.
4. Enable **VoiceChatFollower** under **User Settings > Plugins**.

Updates are delivered through BetterDiscord's built-in updater from the new repository. Please open issues and feature requests [there](https://github.com/KuchiSofts/BetterDiscord-Plugins/issues).

## License

This repository is licensed under the [GNU General Public License v3.0](LICENSE). VoiceChatFollower is licensed under GPL-3.0 as well, with portions derived from Zerthox's BetterVolume under the MIT License (see the new repository's `THIRD_PARTY_NOTICES.md`).

Client modifications such as BetterDiscord are against [Discord's Terms of Service](https://discord.com/terms). Use at your own risk.
