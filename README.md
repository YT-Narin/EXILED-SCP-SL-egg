# EXILED-SCP-SL-egg
[![Trigger: Push action](https://github.com/EsserGaming/EXILED-SCP-SL-egg/actions/workflows/workflow.yml/badge.svg?branch=master)](https://github.com/EsserGaming/EXILED-SCP-SL-egg/actions/workflows/workflow.yml)

# ⚠️This is a fork of [Parkeymon's Repository](https://github.com/Parkeymon/EXILED-SCP-SL-egg)

A pterodactyl egg for SCP:SL that has [EXILED](https://github.com/Exiled-Team/EXILED) support plus some extra features.

Features:

- Beta tag support.
- EXILED support.
- Option to choose the pre-release or release of EXILED.
- Specific EXILED version support.
- Discord Integration support.
- SCPDiscord support.
- Automiatically checks if the egg is up to date and notifies you when there is an update.
- FFmpeg support (for use with audio player plugins).
- ~~Option to remove the EXILED auto updater~~
 - The auto updater is no longer a plugin, so therefore there currently isn't a way to remove it through Pterodactyl.
 - You can turn it off manually in `/home/container/.config/SCP Secret Laboratory/PluginAPI/plugins/global/Exiled Loader/config.yml` and set `enable_auto_updates:` to `false`.

## Custom Plugin installing 
This function is currently not functioning properly and isn't being worked on at the moment, so the documentation has been moved over [here](https://github.com/EsserGaming/EXILED-SCP-SL-egg/blob/master/CustomPlugins.md).

## Custom Docker Images

### Server Image
[![Server Image](https://github.com/EsserGaming/docker-scpsl/actions/workflows/docker-image.yml/badge.svg?branch=master)](https://github.com/EsserGaming/docker-scpsl/actions/workflows/docker-image.yml)

### Script Container
[![Script Container](https://github.com/EsserGaming/scpsl-install-docker/actions/workflows/docker-image.yml/badge.svg?branch=master)](https://github.com/EsserGaming/scpsl-install-docker/actions/workflows/docker-image.yml)
