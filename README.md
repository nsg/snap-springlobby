# snap-springlobby

[![Snap Status](https://build.snapcraft.io/badge/nsg/snap-springlobby.svg)](https://build.snapcraft.io/user/nsg/snap-springlobby) [![Build Status](https://travis-ci.org/nsg/snap-springlobby.svg?branch=master)](https://travis-ci.org/nsg/snap-springlobby)

[Spring Engine](https://springrts.com) is a wonderful RTS game, designed
after the classic [Total Annihilation](https://en.wikipedia.org/wiki/Total_Annihilation)
game.

The snap contains the [springlobby](http://springlobby.info) client. It is used to play multi and single player games, download the actual game binaries, maps, mods and so on.

## Tips

* A easy way to download a mod or map to test the game, just select "Battlelist" and right click a game and select "Download map" and "Download game". You can now try out the game with a mod and map under Singleplayer.

## Is there a new version?

Open an [issue](https://github.com/nsg/snap-springlobby/issues) or submit a
[Pull Request](https://github.com/nsg/snap-springlobby/pulls).

### Checklist to update the build:

- Update `version`, `SPRINGLOBBY_REV` and the `VERSION` to the new release.
- Update `source-tag` to the release tag.
- Make a test build with `snapcraft cleanbuild`
- Submit a PR
