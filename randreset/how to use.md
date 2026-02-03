All the entries are managed by an array situated in the storage `minecraft:resetspawners`, under `pools`.

## Syntax of an entry :**

`{pos:[[1,2,3],[4,5,6],[7,8,9],[0,1,2]],pool:["minecraft:zombie","minecraft:skeleton"]}`
By adding in this entry, we define that the spawners at the followong locations:
- 1 2 3
- 4 5 6
- 7 8 9
- 0 1 2
Will be set on each reset to be summoning either a zombie or a skeleton.

To set the entry list, run
`data modify storage minecraft:resetspawners pools set value <ARRAY_OF_ENTRIES>`
