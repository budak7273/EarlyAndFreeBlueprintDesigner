1.1 support.




This update brought to you by Robb.
If you enjoy my work, please consider donating to my [completely optional tip jar](https://ko-fi.com/robb4).

## Fixed Stuff

- Fix for multiplayer clients not seeing the adjusted (free) cost.
  Not sure if this was an unreported bug from 1.0 or if it was introduced in 1.1's schematic and recipe replication optimizations.

## Extensibility

If you are a mod developer and you have created some mods that add more Blueprint Designers,
you can easily make this mod detect them by adding the
`EarlyAndFreeBlueprintDesigner.MakeThisRecipeFree` Content Tag to your designer's recipe
and `EarlyAndFreeBlueprintDesigner.GiveThisSchematic` to your designer's unlocking schematic.
Learn about Content Tags in the [modding documentation](https://docs.ficsit.app/satisfactory-modding/latest/Development/ModLoader/ContentTagRegistry.html).
