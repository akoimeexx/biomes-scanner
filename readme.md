# Biomes Scanner Datapack
Biomes Scanner Datapack for Minecraft 1.14.4+. Provides an data-driven means of 
detecting player biome to minecraft commands via advancements or scoreboard 
values

`readme.md` is not required in the datapack zip file, but may be included with 
no ill effects.

`LICENSE` is not required in the datapack zip file, but may be included with 
no ill effects.

## Usage

```
/execute as @a[advancements={biomes:detect/dry=true}] run tellraw @s "You're in a dry biome group"
/execute as @a[advancements={biomes:detect/neutral/desert_hills=true}] run tellraw @s "You're in a Desert Hills biome"
/execute as @a[scores={biomes.current=9}] run tellraw @s "You're in The End biome (that's the main end island!)"
```
