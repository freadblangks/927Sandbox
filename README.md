# Sandbox
9.2.7 WoW sandbox. 

Code donated by Arctium for local modding purposes only, do not ask them for support. 

## Usage
Use with a correctly set up 9.2.7 client as well as the launcher available from [here](https://github.com/ModernWoWTools/Launcher).

## Available commands
|Command          |Description              |
|-----------------|-------------------------|
|!fly `on`/`off`|
|!runspeed `value` | 1-1000 |
|!flightspeed `value` | 1-1000 | 
|!swimspeed `value` | 1-1000 |
|!tele `x` `y` `z` `o` `mapid`|Teleports to location, `o` (orientation) is optional  |
|!tele `name`|Teleports to location name (added with !loc) |
|!loc `name` | Prints location, adding a `name` adds it to locations.txt for !tele |
|!addnpc `creatureId`| 
|!delnpc `currentSelection` |
|!additem `itemIds` | You can use multiple IDs separated by spaces |
|!additem `itemId,version` | Where `version` is normal, heroic, mythic or lfr. |
|!emote `id` |
|!weather `id` `intensity`| Where `id` is a [weather ID](https://wago.tools/db2/Weather?build=9.2.7.45745) and `intensity` is an amount (higher than 0.0, requires more research) | 
|!commentator `on`/`off` |Detaches the camera from the character. Change speed with /script C_Commentator.SetMoveSpeed(40)
|!time `hour` `minute` | e.g. "!time 13" for 13:00/1PM or "!time 13 25" for 13:25/1:25PM

## License
MIT, see LICENSE file for additional notes on this specific release.
