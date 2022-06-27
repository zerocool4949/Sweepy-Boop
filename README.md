# aSweepyBoop
My library addon to support advanced arena cooldown tracking WeakAuras as well as a clean Plater Nameplate profile.

All the Weakauras and Plater profiles linked below depend on this library, which means you need to install this addon for them to work 😉

Here is how my UI looks like:
![image](https://user-images.githubusercontent.com/78008331/175856082-319be90f-8967-445b-9373-62e9fcc402cd.png)


## WeakAuras
Here are the arena WeakAuras based on this addon:

- [Arena Enemy CC Cooldowns](https://wago.io/G3Ai96asn)
- [Arena Enemy Offensive Cooldowns](https://wago.io/EtVxNHjcg)
- [Arena Enemy Defensive Cooldowns](https://wago.io/ZqFOXpRY-)
- [Arena Enemy Dispel Cooldowns](https://wago.io/a_AIv4HJp)
- [Arena Enemy Interrupt Cooldowns (similar as default Omnibar)](https://wago.io/UgjuEm1mk)

- [Mortal Strike Debuff on Team](https://wago.io/pCKbpzW-Q)
- [Group member stun DR on raid frames](https://wago.io/FUT9JPGxV)
- [Player's own DR timer](https://wago.io/cD-yK8HTF)

The cooldown tracking WeakAuras come with various advanced features:
- Cooldown reduction: Hammer of Justice (from Fist of Justice), Combustion (from Pyrokinesis, Kindling, Shifting Power), etc.
- Talent memorization such as:
  - If a paladin casts Repentance or Blinding Light, Fist of Justice calculation for that player would be suppressed
  - If a priest casts a second Psychic Scream within 60 sec after the first one, we know they are playing Psychic Voice, thus will adjust the Psychic Scream cooldown for that unit to 30 sec

## Plater
[Plater profile based on this addon](https://wago.io/KnkjLULX7)

The main feature of this profile is called "Nameplate Filtering" inside arenas:
- For enemy units, only show nameplates of enemy players, primary pets, and high priority non-player units that are whitelisted
  - Primary pet refer to the main warlock pets (i.e., you will not see a horde of wild imps running around), and the main hunter pet (which means for Beast Mastery hunters, you will only see the real pet with 120 focus)
  - High priority units are generally those you want to target and kill instantly, e.g., Grounding Totem, Psyfiend, War Banner, Tremor Totem (if you are playing a class that has fear spells)
- If you are playing with friendly nameplates on, party members' nameplates will be reduced to half width, the names on top will be hidden (and raid markers, which most arena players use on their teammates, would take the place), and buffs/cast bar will be hidden.
  - The logic behind this is for many players especially healers, they want to be able to track their teammates' positioning easily, but with a strong distinction between friendly/enemy units

## Fix Blizzard raid frame aggro highlight
Blizzard's raid frame aggro highlight only tracks PvE threats. That means pet threats inside arenas, which is rather unreliable.

This module fixes that by highlighting the teammate who is targetted by the most enemy players.

For this module to work, disable the following setting under Interface settings so it stops showing PvE threats:
![image](https://user-images.githubusercontent.com/78008331/175849539-7a7180d4-28f8-4453-b979-d98f56a2623c.png)

