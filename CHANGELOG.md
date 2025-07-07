# 1.0.6
- Placed compendium in `Season of Ghosts Maps and Tools` folder

# 1.0.5
- Fix Willowshore Random Encounter Flat Check macro

# 1.0.4
- Fix broken links in Willowshore Random Encounter Table

# 1.0.1
- Because I messed up and released empty compendiums, this should bring back all the compendium data for v12 users.

# 1.0.0
v12 and v13 compatible 1.0.0 release.
- Includes optional dependency for Item Piles: PF2e which should ensure Item Piles works properly in the PF2e system for merchants.
- Installing this module should automatically prompt installing both Item Piles and the PF2e compatibility module (though it is still optional)
  - if you are just updating this module, it won't do this automatically. *Go install the compatibility module right now if you use Item Piles.*
- Macros fixed to make sure they work with v13
- Effects compendium should have had Book 1 and Book 2 effects but were missing and no one told me, so that is hopefully fixed now.
- Known issue, random encounter rolltables still have broken links, going to wait for a future system update to fix that

# 0.7.0

- Verified compatibility for v12
  - Item Piles continues to be marked as an *optional* dependency. It's not officially v12 compatible at the time of writing, but it should work for existing merchant actors in v12.
- Added some commonly used effects from Book 1, such as `Blessed Coins`, `Spider Gate Lantern`, and `Mirage Mist`. These can be placed on players to get permanent bonuses as long as they're needed.

# 0.6.0

- Add Shinzo merchant
- Includes hidden items to his inventory (only hidden with Item Piles, make them visible at the appropriate time)

# 0.5.0

- Update `Willowshore Random Encounters Flat Check` macro to also draw from the random encounters table if the check succeeds.
- Add `Hinterlands Random Encounters Flat Check` macro which links to two roll tables to draw from. One table for when the party is within 2 hexes of Willowshore, and another table for everywhere else in the Hinterlands.
- Fix the random encounter roll tables to output text with actor links instead of containing an actor. Should work when an encounter contains multiple types of creatures, and can specify multiple of one creature type.
- Add `Blood Rain` macro, which is just a simple flat check that outputs a result.

# 0.4.0

- Update merchant spell scrolls to remastered spells

# 0.3.0

- Update shop inventories with remastered items
- Adjust the inventories, remove some items from inventories that a shop shouldn't probably explicitly have
- Add github url to module.json

# 0.2.0

- Fix module.json to add download url and manifest link
- Update merchant token images