# PM3
A plugin that makes PM3 plugins support PM4
# Notice
This plugin is still in-development
# What todo:
- change all pocketmine uses
Example:
```php
# PM3 Without Plugin
use pocketmine\Player;
# PM4 With this plugin
use ItsToxicGG\Player;
```
- change the api to api4
Example:
```yml
Api: 3.0.0 # change it to 4.0.0 like:
Api: 4.0.0
```
- Do not change pluginbase or protocol stuff keep it for a example:
```php
use pocketmine\plugin\PluginBase;
or
use pocketmine\Network; // if it do have pocketmine\network
```

