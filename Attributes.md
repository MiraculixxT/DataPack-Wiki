# Attributes
Change the behavior of players and other entities. 
Entities can be modified directly by commands or by applying attribute effects on items.

**Main Command**: `/attribute <target> <attribute> <base/get/modifier> [...]` \
``<target>`` ⇒ Limited to one target

## Examples
- Get your movement speed: `/attribute @s minecraft:generic.movement_speed base get`
- Change your max health: `/attribute @s minecraft:generic.max_health base set 10`

TODO: Add more examples for modifiers

## Generic Attributes
| ID                             |                             Description                             | Base Player |
|:-------------------------------|:-------------------------------------------------------------------:|:-----------:|
| `generic.armor`                |                    Reduces damage taken by value                    |    `0.0`    |
| `generic.armor_toughness`      |  Reduces damage taken by a percentage based on the incoming damage  |    `0.0`    |
| `generic.attack_damage`        |    Base damage dealt by attacks. Is modified by other attributes    |    `1.0`    |
| `generic.attack_speed`         |       Amount of full charged hits per second. Higher = faster       |    `4.0`    |
| `generic.attack_knockback`     |                   Base knockback dealt by attacks                   |      -      |
| `generic.fall_damage_provider` | 0 = no fall damage, 1 = normal fall damage, 2 = reduced fall damage |    `1.0`    |
| `generic.flying_speed`         |           Speed while flying with elytra or creative mode           |      -      |
| `generic.follow_range`         |              Distance mobs will follow the player from              |      -      |
| `generic.gravity`              |                    Gravity applied to the entity                    |   `0.08`    |



