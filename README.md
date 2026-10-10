# IFrame Meadow â€” downloads

**Game source is private. This public repository distributes Windows builds only.**

## Install on another PC

1. [Download the automatic launcher](https://github.com/loganhenson/iframe-game-downloads/releases/latest/download/iframe-launcher-windows-x64.zip).
2. Extract the entire ZIP and keep the extracted folder.
3. Double-click **Update and Play.cmd**, or create a desktop shortcut to it.

The first launch downloads the client. Every later launch checks for a newer
release before opening the game. Close the game and use the launcher again to
update. No GitHub sign-in, Rust, Node or separate installer is required.

Your player identity and companion survive updates. Downloads are checked with
SHA-256 before installation. If GitHub is unavailable, the launcher uses the last
working client. It keeps the current and previous versions for recovery.

## Play on the LAN

The server PC must be running the game server on the same local network. The
client discovers it automatically. GitHub delivers updates; game connections
and the persistent world stay on your LAN and server PC.

WASD or both mouse buttons move, Shift sprints, RMB orbits, and the wheel zooms.
Enter opens the command console. /reset starts your player over at spawn.

Walk to the signed **MEADOW HIGH** entrance near spawn and click **Sign up to
race**. At a server minute boundary, two to seven signed-up players begin a
one-lap race. Hold W or both mouse buttons to run your assigned lane; Shift
sprints. /race leave or Pull out cancels. Kittens cheer from the bleachers,
the winner celebrates, and participants return to the entrance after five seconds.

## Files in each release

- **iframe-launcher-windows-x64.zip** â€” recommended one-time download; updates on relaunch.
- **iframe-client-windows-x64.zip** â€” full standalone client for manual/offline installation.
- **update.json** â€” the version and package checksum used by the launcher.
- **SHA256SUMS.txt** â€” package checksums for manual verification.

Download the launcher asset, rather than GitHub's automatically generated
Source code ZIP. That source ZIP contains this downloads README, not the game.
The game source and Vox Studio assets are maintained in a separate private repo.

[Latest release](https://github.com/loganhenson/iframe-game-downloads/releases/latest)