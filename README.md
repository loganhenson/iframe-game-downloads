# IFrame Meadow â€” downloads

**Game source is private. This public repository distributes Windows builds only.**

## Install on another PC

1. [Download the automatic launcher](https://github.com/loganhenson/iframe-game-downloads/releases/latest/download/iframe-launcher-windows-x64.zip).
2. Extract the entire ZIP and keep the extracted folder.
3. Double-click **Update and Play.cmd**, or create a desktop shortcut to it.

The launcher prefers the LAN server's exact client on every relaunch. GitHub
provides the first download or fallback when no LAN update server is available.
Close the game and use the launcher again to update. No GitHub sign-in, Rust,
Node or separate installer is required.

Your player identity and companion survive updates. Downloads are checked with
SHA-256 before installation. If GitHub is unavailable, the launcher uses the last
working client. It keeps the current and previous versions for recovery.

## Play on the LAN

The server PC must be running the game server on the same local network. The
client discovers it automatically. GitHub delivers updates; game connections
and the persistent world stay on your LAN and server PC.

Server startup prepares and serves its matching client package. Local server
changes update players on relaunch without another GitHub release, including
model/client changes that keep the same protocol. An older launcher can stay:
after its first updater-aware public client download, that client checks the
server before opening the game. Its separate LAN cache prevents downgrades.
The host allows TCP 33332 for updates beside UDP 33330/33331 for gameplay.

WASD moves; hold Shift or right-click to sprint. Mouse looks; wheel zooms.
Click the world to play. Hold Alt or press Esc to free the cursor for UI.
Alt-Tab releases the cursor; click the world to resume. Close the window to quit.
Enter opens the command console. /reset starts your player over at spawn.
/unstuck returns safely to spawn while keeping your companion and progress.

Explore our anime-style Tyler/Rolling Acres neighborhood, enter the primary house
and decorate it with 150 distinct furniture/items. B toggles the picture catalogue;
its arrows or mouse wheel browse eight previews per page without categories.
Hold Left Alt for a free cursor. E interacts with doors/beds, and Space wakes you.
Claimed kittens explore the house, nap and play with the shared yarn ball.
A four-seat hatchback waits on the garage driveway. E enters when stopped; the
driver uses W/S to drive, A/D to steer and Ctrl to brake. Space gets out. Parking
survives server restarts.

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