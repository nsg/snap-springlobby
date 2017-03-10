# snap-springlobby

[Spring Engine](https://springrts.com) is a wonderful RTS game, designed
after the classic [Total Annihilation](https://en.wikipedia.org/wiki/Total_Annihilation)
game.

The lobby is used to download the actual game binaries, maps, mods and so on.

## Known problems

* On first launch we get a info dialog with the title "Error" that says "is not writable!". I have not tracked down exactly what it is trying to do but it's somewhere in [this function](https://github.com/springlobby/springlobby/blob/041655be4a4c9c0583c80138e90ad0d0652ffeb0/src/sysinfo.cpp#L57). It looks like that you can safely ignore it.

* After a connection to the server you are offered to download the latest engine, but it looks like that the server fails to find both `spring` and `libunitsync.so` even if the path is correct. A restart of the lobby will solve this. Not sure why.

## Tips

* A easy way to download a mod or map to test the game, just select "Battlelist" and right click a game and select "Download map" and "Download game". You can now try out the game with a mod and map under Singleplayer.
