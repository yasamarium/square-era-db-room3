# Square Era Database - Room 3: Builder's Paradise

Persistent world modifications, player profiles, and session state for Square Era 3D Voxel Sandbox Room 3.

## Room Overview
- Room ID: 3
- Room Name: Builder's Paradise
- Game Mode: CREATIVE
- Description: Infinite Creative Canvas for megastructures, pixel art, and architectural exploration.
- Server Repository: [yasamarium/square-era-server-room3](https://github.com/yasamarium/square-era-server-room3)

## Schema & Files
- `data/world.json`: JSON map of persistent chunk modifications `[ ["x,y,z", blockId], ... ]`.
- `data/players.json`: Registered player profiles and session records.
- `data/chat.json`: Persistent in-room chat history.
- `data/sessions.json`: 5-hour runner cycle timestamps and synchronization checkpoints.

Zero external databases required. Backed 100% by GitHub Git persistence.
