<p align="center">
  <img src="https://cdn.discordapp.com/avatars/761358247373438997/6d5668707a08fff7fd4e8324fc5cb9d2.png?size=128" style="border-radius: 100%;" />
</p>

# ash-public

Ash 2: Discord bot - Administration service for StormLands (Stormworks RP server)

Written in JavaScript (discord.js on Node.js)

(@qcwrenshu turnip)

# Features

- Economy system based on accounts
- Leaderboards
- Group system --> nations and factions
- Entity permissions system
- In-game player data and verification framework
- Command handler for both prefix and app commands
- GraphQL server

## Differences from StormLands Ash

Ash Public omits some features from StormLands Ash that we are not ready to release yet.

Notably, it omits:
- Ash Vehicles (Vehicles system)
- AshSSM (Stormworks server manager) (and by extension, linking verification system)
- SWLink (Stormworks server reflection system)

One may reimplement these functions themselves if they so desire to regain features such as verification.

See the comments at the top of each file for more information.

# Getting started

1) Clone this repository to a folder
2) Install Node.js if it is not already installed
3) Run `npm install` to install dependencies
    - Some dependencies such as `better-sqlite3` may require build tools
4) Configure bot administrators and other details in `config.json` (important! Do this before continuing)
5) Run `firstrun.js` to initialize the database
6) Run `index.js` to start Ash

# For more information

For more information, see the comments at the top of each file.

Thank you for using StormLands Ash.

This version of Ash is provided with no warranty, no guarantee, and no support. Please attribute correctly!
