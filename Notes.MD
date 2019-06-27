# Merchant Sailing
## The Grid
- The game board in a grid ranging from -100 to 100. Player's start at point (0,0).
- Each square on the grid can either be ocean, island, or obsticle. 
- Sea squares can contain loot or monsters, and can be occupied by a ship.
- Island squares can have markets, outposts, or resources. They cannot be occupied by a ship. For a ship to interact with an island, they need to be on an ocean square touching the island.
## Islands
- Islands can be settled or unsettled.
- Settled islands have ports and can have outposts built on them.
- Unsettled islands have resources that can be harvested. Those resources will respawn over time. 
  - Outposts can be built on some unsettled islands , but cost a great deal more resources.
## Ships
- Players start with a small ship. New, better ships can be purchased at some ports. 
- Ships have a value, speed, attack, defense, max rations, current rations, max integrity(health) current integrity(health). Ships have a max number of cargo slots, defense slots, attack slots and auxilary slots.
- Ships have cargo slots, defense slots, attack slots and auxilary slots. How many of each slot depend on the ship.
  - Cargo slots can hold any item. When an item is in cargo, it is not active, none of its effects affect the ship.
  - Defense slots hold items that have a defense bonus. Items in defense slots increase defense.
  - Attack slots hold items that have an attack bonus. Items in attack slots increase defense.
  - Auxiliary slots hold items that have an auxliary bonus. This can increase speed, max integrity, max rations.
- Ships have a rations, as a ship moves, the ship consumes rations, if rations are used up, integrity begins to decrease. If integrity reaches zero, the ship sinks, and the player goes back to the nearest outpost.
- Integrity also decreases if a ship is attacked. 
- Speed is the amount of rations used with each tile. Speed also affects how quickly monsters and other ships move relative to the user's ship.
- Itegrity and rations can be increased by using consumable items. Itengrity and rations also reset to max at an outpost.
## Items
- Items can be almost anything. Items can be single use, ship upgrade, or merchant items. Single use items are consumables that can be used once and change the stats of a ship. Ship upgrades can be placed in slots to increase a certain stat (attack, defense, auxilary). Merchant items have no effect on the ship, but can be bought or sold. 
- Items have a base value. Depending on the player's buying power, and the demand for them at a particular port, they have a market value. Some ports will value certain items more than other ports.
## Outposts
- Outposts can be built at any settled island, and at some settled items.
- Depending on the location, outposts cost gold and or resources.
- Once built, outposts can store cargo.
- Ships can "rest" at an outpost to regain max itegrity and rations. 
- Outposts increase a player's buying power at that port.
## Players
- Players begin the game with a ship at (0,0), gold, an full rations and integrity. 
- Players begin at level 1, as they increase levels, they unlock new ships, items, or islands.
- Players collect gold by trading goods, harvesting goods, and defeating monsters.
- Players belong to a trading company, and can build outposts at ports that do not already have an outpost.
## Monsters
- Each ocean tile has a chance of containing a monster. Those odds depend upon the tile.
- Monsters have attack, defense, speed, and health.
- Players can fight the monster, or run away. 
  - The player and the monster will take turns attacking. If the monster is defeated, it will drop loot. The player will gain expereince.
  -If the monster is faster than the player, it will continue to attack as the ship moves. It will not stop the ship from moving. 
  - Monsters will not attack players that are on a tile touching an island. 
