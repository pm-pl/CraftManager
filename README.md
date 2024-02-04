[![Discord](https://img.shields.io/discord/1076553697192071268.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://discord.gg/pocketmine)
[![](https://poggit.pmmp.io/shield.dl/CraftManager)](https://poggit.pmmp.io/p/CraftManager)


### CraftManager

Allows you to create or delete crafts ! Works with the new pocketmine crafting system (>= 4.18)

If you have any problems please create an issue I will try to answer them as soon as possible. And feel free to star the project

Finally, if you are looking for private plugins at a good price, I can make some on my discord: [[Click here](https://discord.gg/pocketmine)]

### Config

```yaml
# Plugin Shop
#
# https://discord.gg/pocketmine
# https://maxoooz.mysellix.io/

# All items you want to remove from the workbench
# You can set the meta "-1" or not set it all to include all items
delete:
  - "Wooden Pickaxe"

new:
  -
    # Organization on the 9 slots in the workbench
    shape:
      - " A "
      - " A "
      - " B "

    # All items that relate to the letters you entered just above ^
    input:
      A: "Stone"
      B: "Cobblestone"

    # Item that will be given when the player makes the craft
    output: "Diamond:1"

    # Are the crafts for the basic item removed?
    remove-old-crafts: true
```

### Features

| Feature | CraftManager | CreateDelCraft | CraftingPlus | CustomCraftDraz | SimpleCustomCraft |
|-----------------------------------|-----------------|------------|--------------|--------------|--------------|
| `Create Craft` | ✔ | ✔ | ✔ | ✔ | ✔ |
| `Replace craft` | ✔ | ❌ | ❌ | ❌ | ❌ |
| `Delete craft` | ✔ | ❌ Not functional since PM 4.18 | ❌ | ❌ | ❌ |
