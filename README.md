# Underlords Community Rotation — Crazy Offline Build

This is a community modification for **standalone Dota Underlords**, Steam App ID **1046930**. It is not a Dota 2 mod.

The Crazy build re-enables the hero and item definitions that are present in the installed Underlords data:

- 85 hero definitions
- 76 item definitions
- Recovered appearance resources for Sniper, Techies, Timbersaw, and Tinker
- Offline Standard/Easy bot matches

The goal is to let players experiment with retired heroes, old items, alliances, and unusual team combinations.

## Important limitations

This release is **offline only**. It does not provide multiplayer, private lobbies, ranked matchmaking, VAC changes, Steam authentication changes, anti-cheat changes, or executable modifications.

The 85-hero roster is an experimental stress build. Shop dilution, duplicate names or icons, missing effects, and incomplete visual behavior are possible.

You must own and install the original standalone Underlords game through Steam. This project does not redistribute the game client or Valve’s game archives.

## Downloads

Download the matching release file for your operating system:

- `mac-simple-v0.2.zip` — macOS
- `windows-simple-v0.2.zip` — Windows

The `.sha256` files contain checksums for verifying the downloads.

## macOS installation

1. Close Underlords.
2. Extract `mac-simple-v0.2.zip`.
3. Double-click `Crazy-Install-and-Play.command`.
4. Start a new Standard/Easy bot match.
5. Close Underlords when finished.
6. Double-click `Crazy-Restore.command`.

No Python or additional runtime is required.

If macOS blocks a command file, right-click it in Finder and choose **Open**. Do not disable Gatekeeper.

## Windows installation

1. Close Underlords.
2. Extract `windows-simple-v0.2.zip`.
3. Double-click `Crazy-Install-and-Play.cmd`.
4. Start a new Standard/Easy bot match.
5. Close Underlords when finished.
6. Double-click `Crazy-Restore.cmd`.

No Python or separate installer is required. Steam must be installed normally.

If the game is installed in a nonstandard Steam library, the installer will ask for the Underlords installation folder.

## Safety and restoration

The installer:

- Checks the supported Underlords build and file hashes
- Refuses to run while the game is open
- Creates backups before changing definition files
- Refuses existing asset conflicts
- Verifies installed files
- Restores the original definition files byte-for-byte

Keep the extracted tester folder until you have restored the game. Do not manually overwrite or delete the state files.

## Testing and feedback

Please start a new bot match after installation. Test heroes and items across different tiers, try a 2-star combination, and watch for missing models, effects, broken abilities, alliance problems, or crashes.

When reporting a problem, include:

- Hero or item name
- Round number
- What you attempted
- What happened
- A screenshot or log excerpt if available

The long-term project is a balanced rotating roster that brings back retired heroes while preserving the original Underlords gameplay.
