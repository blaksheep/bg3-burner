# Burner

A Baldur's Gate 3 mod that supports permanent deletion of inventory items in a conjured Burner Chest. This mod supports the full release version of BG3.

## About

The Baldur's Gate 3 Burner mod expands merchant inventory with the "Burner Chest Conjuring Ring". When equipped, your character has a new "Conjure Burner Chest" spell that allows you to conjure a ground-targeted chest to dispose of unwanted inventory equipment.  Fill the Burner Chest up, then use any attack to destroy the Chest. The items that you place in it are permanently deleted when you destroy the Chest.

## Why Destroy Items?

There may be a number of reasons to do this.  For example, you might want to eliminate mod-generated items from characters before you remove the mod that was used to generate the items.

## Install

1. Download the [latest Burner.zip archive release](https://github.com/blaksheep/bg3-burner/releases) of the Burner mod.
2. Follow your mod manager BG3 mod installation instructions, or published instructions on how to manually install BG3 mods. Development installation testing takes place with [Laughing Leader's BG3ModManager](https://github.com/LaughingLeader/BG3ModManager). The are no known mod load order issues with Burner. It should work in any mod load order.

## Mod Usage

1. Purchase the "Burner Chest Conjuring Ring" from the merchant, [Arron](https://bg3.wiki/wiki/Arron).
2. Equip the ring
3. Click the new "Conjure Burner Chest" spell and target the location where you want to place the Chest on the ground. Use the spell.
4. Open the chest and deposit all unwanted equipment.
5. Use any attack on the Chest to destroy it and all enclosed items. The Chest has Sturdy Toughness and you must use at least 10 damage, but has full vulnerability.

## Uninstall

1. Drop the "Burner Chest Conjuring Ring" in a new Burner Chest and destroy it.
2. Save
3. Logout of your character account and close BG3.
4. Deactivate and remove the mod from the mod order list using your mod manager, then save the mod order list and re-export it (or use published instructions to do this manually).
5. Launch BG3 and continue on the save above. The "Burner Chest Conjuring Ring" will no longer be available in the merchant inventory.

## Develop

The mod source is defined in the `Burner` directory of this repository.  Make your edits, then re-package the `Burner.pak` mod in a `Burner.zip` archive with the [Baldur's Gate 3 Modder's Multitool](https://github.com/ShinyHobo/BG3-Modders-Multitool). Please do consider proposing any useful new changes that you make in this upstream repository!

## Issues

Please use [the tracker on this repository](https://github.com/blaksheep/bg3-burner/issues) to identify existing and [report new issues](https://github.com/blaksheep/bg3-burner/issues/new).

## License

The source code in this repository is released under the [Apache License v2.0](LICENSE). Please feel free to use and adapt the source released here according to this license.
