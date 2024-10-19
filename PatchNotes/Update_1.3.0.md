Satisfactory 1.0 release support. Now uses Content Tags to decide which designers to unlock and make free.




This update brought to you by Robb.
If you enjoy my work, please consider donating to my [completely optional tip jar](https://ko-fi.com/robb4).

## Changed Stuff

- All blueprint designers now cost 1 Leaves item to place instead of nothing
  - This is to work around a base-game bug causing buildings with no cost to never finish the build animation.
    As soon as the bug is resolved I will change it back to costing nothing.

## Extensibility

If you are a mod developer and you have created some mods that add more Blueprint Designers,
you can easily make this mod detect them by adding the
`EarlyAndFreeBlueprintDesigner.MakeThisRecipeFree` Content Tag to your designer's recipe
and `EarlyAndFreeBlueprintDesigner.GiveThisSchematic` to your designer's unlocking schematic.
Learn about Content Tags in the [modding documentation](https://docs.ficsit.app/satisfactory-modding/latest/Development/ModLoader/ContentTagRegistry.html).
