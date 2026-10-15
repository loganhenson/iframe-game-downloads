# IFrame - Windows LAN launcher

**Game source is private. This public repository distributes the launcher.**

1. [Download the latest launcher](https://github.com/loganhenson/iframe-game-downloads/releases/latest/download/iframe-launcher-windows-x64.zip).
2. Extract the entire folder, replacing your old extracted launcher folder.
3. Run **Update and Play.cmd**, or make a desktop shortcut to it.

Keep the game server running on the same local network. The launcher gets the
server's exact game build directly from that PC. No GitHub account, Rust or
separate installer is needed. A progress window remains visible during startup.

The first install downloads the full game. Later updates reuse verified files
and transfer only changed files. Close the game and run the launcher to update.
Failed updates leave the working installation intact. It keeps current and
previous versions; older inactive versions are removed.

Your player identity and kitten survive replacing the launcher and updating the
game. They are separate from the installation under `%LOCALAPPDATA%\IFrameGame`.
The world stays on the server PC. This launcher uses the `lan-client` cache and
requires the LAN server; it does not fall back to an unrelated public game build.

The server host uses UDP 33330/33331 for play/discovery and TCP 33332 for updates.
No internet port forwarding is needed. Local game changes do not require another
GitHub release: the server supplies matching builds on relaunch.

Download the launcher asset, **not** GitHub's generated Source code ZIP, which
contains only this download documentation. Older full-client releases are historical.

## Controls

WASD moves. Shift/right-click dodges, then hold to sprint. Mouse looks; wheel zooms.
Hold Left Alt for the cursor. E interacts; Space exits beds and cars. B decorates.
Enter opens the console: type `/` and part of a command for a short typeahead list.
Tab or arrow keys browse matches; Enter runs the command. `/unstuck` returns safely
to spawn while keeping your kitten. K toggles admin flight.
