# SBA-Bearite-Menu — project status

## Target environment
- Game: Super Bear Adventure
- Game version: 13.0.9
- Mod loader: SBAModLoader 0.0.5a-compose (14)
- Mod type: Native Mod
- Android ABI: arm64-v8a

## Planned features
- God Mode
- Speed Hack
- Super Jump
- Infinite Jump
- Fly
- Infinite Coins
- No Clip

## Current status
- The target game version and Android ABI have been identified.
- The SBAModLoader native-mod packaging approach has been identified.
- Game-specific IL2CPP methods, signatures, and hook locations still require validation against the exact 13.0.9 game files.
- No functional native hooks or compiled mod binary are included yet.

## Safety and compatibility
Do not use guessed offsets or unverified patch addresses. Validate each hook against the exact game build before packaging or testing.
