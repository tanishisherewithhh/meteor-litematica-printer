# Meteor Litematica Printer Advanced

Fast printer to litematica mod without rubberbanding

## [Tutorial Video](https://clipchamp.com/watch/Vh1qFgzOsmd?utm_source=share&utm_medium=social&utm_campaign=watch)

Litematica printer addon for meteor [1.4 advanced](https://github.com/tanishisherewithhh/meteor-litematica-printer/releases/tag/1.4v).

This version improves baritone functioning. It also includes restock feature by placing and breaking shulkers from the hotbar.

### Restock feature includes:

- Place a shulker from the hotbar if an item in the `Item` setting is less than 5. (It does not support shulker in inventory)
- It does not automatically take items from the shulker. So, you need to enable inventory tweak's `auto steal`. You also need to add the shulker box screen to the `steal screen` and select _items to auto steal_.
- After 5 seconds, the addon automatically breaks the shulker. Incase the shulker breaks too quickly, switch from a pickaxe to hand.
- It will find the nearest block to place the shulker on (similar to echest farmer).
- Sometimes the restock may not work or the shulkers mined will not be picked up due to server or environment problems.
- Restock does not work on build height

[1.3 version](https://github.com/tanishisherewithhh/meteor-litematica-printer/releases/tag/1.3v) added.
1.3 adds the following to the printer addon:
- Uses baritone to automatically move to unplaced regions in the schematica
- New travel range and delay setting to travel to the unplaced regions.

## Suggested to be used for map arts or flat schematic (as in on the ground) as baritone may be weird for 3D structures.


### If any problems arise, contact me on my discord: `tanishisherewith`

If used with proper settings, it can be fast. 

# FAQ fixes:

- Increase `Travel Range` if baritone can't find an unplaced region.

- Increase `Travel delay` so that baritone moves less frequently and allows enough time to place blocks.

- If baritone gets stuck increase `Travel delay`. 

- Add `Items` in the item setting which should be check for restocking.

- Decrease `block/tick` if blocks aren't being placed properly
