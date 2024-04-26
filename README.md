> [!Note]
> **This is a fork of [Parkeymon's Repository](https://github.com/Parkeymon/EXILED-SCP-SL-egg)**
# EXILED-SCP-SL-egg
**A Pterodactyl egg for SCP:Secret Laboratory that has [EXILED](https://github.com/Exiled-Team/EXILED) support plus some extra features.**

## Features:
- Beta tag support.
- EXILED support.
- Option to choose the pre-release or release of EXILED.
- Specific EXILED version support.
- Discord Integration support.
- SCPDiscord support.
- Automiatically checks if the egg is up to date and notifies you when there is an update.
- FFmpeg support (for use with audio player plugins).

### For more information on how to use SCPDiscord or Discord Integration, click one of the dropdowns below.
<details>
<summary>SCPDiscord bot</summary>
  
### Using the SCPDiscord bot.
1. Go to the startup tab in your server, then set `INSTALL SCP DISCORD?` to `true`.
2. Under the settings tab, press "Reinstall Server" and wait until the server has finished the process.
> **Re-installing will *not* delete your important files.**
3. Go to the files tab, and go to `/.egg/SCPDBot` and open `config.yml` to configure the bot.
> **To configure the bot and plugin, read the [installation guide](https://github.com/KarlOfDuty/SCPDiscord/blob/master/docs/Installation.md).**

</details>

<details>
<summary>How to use Discord Integration bot</summary>

### Using the Discord Integration bot.
 **Warning: Discord Integration's documentation is very sparse, and isn't maintained.**

1. Go to the startup tab in your server, then set `INSTALL DISCORD INTEGRATION?` to `true`.
2. Under the settings tab, press "Reinstall Server" and wait until the server has finished the process.
> **Re-installing will *not* delete your important files.**
3. Go to the files tab, and under the root directory, open `DiscordIntegration-config.json` to configure the bot.
</details>

## Custom Docker Images
### Server Image
[![Server Image](https://github.com/EsserGaming/docker-scpsl/actions/workflows/docker-image.yml/badge.svg?branch=master)](https://github.com/EsserGaming/docker-scpsl/actions/workflows/docker-image.yml)

### Script Container
[![Script Container](https://github.com/EsserGaming/scpsl-install-docker/actions/workflows/docker-image.yml/badge.svg?branch=master)](https://github.com/EsserGaming/scpsl-install-docker/actions/workflows/docker-image.yml)
