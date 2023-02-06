# SweepyBoop's Arena Helper
My lightweight addon to support arena plays.

Here is how my UI looks like:
![image](https://user-images.githubusercontent.com/78008331/212603812-af58c455-962c-45d2-8dc4-2c82cab7cd53.png)

## Class and pet icons
For friendly players and their primary pets, place a class (for players) or pet icon on top.

When selected, show an orange border to highlight.

This makes it much easier to track where your teammates are duing an arena match.

## Arena enemy cooldown tracking
The cooldown tracking mod comes with various advanced features:
- Shows duration when the cooldown is active with a glow, and shows cooldown timer otherwise (close to tournament UI)
- Sort icons by priority/threat, e.g., on an Assasination Rogue, Deathmark will always show before other icons
- Cooldown reduction: for instance, Windwalker Monk Storm, Earth, and Fire cooldown reduced by spending Chi, Fire Mage Combustion cooldown reduced by casting Fireball or crit damage

## Fix Blizzard raid frame aggro highlight
Blizzard's raid frame aggro highlight only tracks PvE threats. That means pet threats inside arenas, which is not very useful.

This module fixes that by highlighting the teammate who is targetted by enemy DPS players.

For this module to work, disable the following setting under Interface settings so that it stops showing PvE threats:
![image](https://user-images.githubusercontent.com/78008331/216872796-737ec8a0-336b-4721-a122-bb9daaf70583.png)

