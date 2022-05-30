# PM3toPM4 Guide
A Little guide
# File Changes:
```php
// Do not use pocketmine\level\Level; this cause a error in-game since it is not found now use pocketmine\world\World;
# PM3
use pocketmine\level\Level;
use pocketmine\level; // if the use has pocketmine\level change it to pocketmine\world
# for example, level\Position is pm4 now change it to pm4 what is world\Posititon rememeber anything that is has pocketmine\level change it to pocketmine\world
# PM4
use pocketmine\world\World;
use pocketmine\world;
# end ----- of world
// Player, player has moved  and its now pocketmine\player\Player; not the pm3
# PM3
use pocketmine\Player;
# PM4
use pocketmine\player\Player;
# end ----- of player
there are more ill do it in later changes.


