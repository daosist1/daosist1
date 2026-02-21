# Hi, I am Rumin (daosist1)

Roblox LuaU backend and gameplay systems developer.
I build server-side systems with clear module boundaries, data safety, and production-ready structure.

## Focus

- Roblox LuaU backend scripting
- Gameplay systems and progression loops
- Matchmaking, economy, and reward logic
- Config-first architecture without OOP/metatables

## Featured Roblox Projects

### 1. Arena Combat Core
Round-based arena combat server systems with reward progression.

- Repository: [roblox-arena-combat-core](https://github.com/daosist1/roblox-arena-combat-core)
- Stack: LuaU, Roblox services, JSON player data flow

### 2. Tycoon Economy System
Server economy module with passive income, upgrades, and safe state updates.

- Repository: [roblox-tycoon-economy-system](https://github.com/daosist1/roblox-tycoon-economy-system)
- Stack: LuaU, config modules, database-ready structures

### 3. Lobby Matchmaking Core
Queue lifecycle and balanced team generation for multiplayer matches.

- Repository: [roblox-lobby-matchmaking-core](https://github.com/daosist1/roblox-lobby-matchmaking-core)
- Stack: LuaU, server validation, session flow modules

## Code Style

- No OOP and no metatables
- No compact `if return end` syntax
- Config modules use `return {}`
- Player data from `plr.DataBase`
- If table data is stored as string, decode with `HttpService:JSONDecode`
- Short English one-line comment before each function

## Contacts

- GitHub: [daosist1](https://github.com/daosist1)
