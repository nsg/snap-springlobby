# snap-springlobby

[![Snap Status](https://build.snapcraft.io/badge/nsg/snap-springlobby.svg)](https://build.snapcraft.io/user/nsg/snap-springlobby)

[Spring Engine](https://springrts.com) is a game engine for RTS styles games, designed
after the now classic game [Total Annihilation](https://en.wikipedia.org/wiki/Total_Annihilation).

The snap contains:

* [SpringLobby](https://springlobby.springrts.com/)
* The tool `pr-downloader` that you can use to download engines, games, maps and so on
* The latest engine, the game Zero-K and a map is included out of the box to make it playable.

The lobby can be used to easily launch single or multiplayer games. It has also a built in utility to download games, maps and other tings from users. If you prefer to use pr-downloader, the command is `springlobby-nsg.pr-downloader`. For example, to download the latest release of BA type `springlobby-nsg.pr-downloader ba:stable` (Balanced Annihilation is a popular game that is similar to the original Total Annihilation).

## Tips

* A easy way to download a mod or map to test the game, just select "Battlelist" and right click a game and select "Download map" and "Download game". You can now try out the game with a mod and map under Singleplayer.

## Install

The package is named `springlobby-nsg`. The default channel i stable and contains verified builds. The edge channel are automatically built and are untested, this channel should always contain the latest release.

```
# install stable release (recommended)
snap install springlobby-nsg

# test the edge release
snap install --edge springlobby-nsg # new install
snap refresh --edge springlobby-nsg # switch from stable to edge
```

## Is there a new version?

Open an [issue](https://github.com/nsg/snap-springlobby/issues). If you like to help, try the edge channel and tell me if that version works on your system.
