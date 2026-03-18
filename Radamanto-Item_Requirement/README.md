# Item Requirement

Allows you to restrict **crafting** and **usage** of items based on **skills or attributes**, creating a more balanced and RPG-like experience.

## Features

- **Custom Skill Requirements**  
  Define personalized requirements for each item through the configuration file.

- **EpicMMO System Integration**  
  Fully compatible with **EpicMMOSystem**, allowing attributes to be used as requirements.

- **Server-Synced Configuration**  
  All settings are synchronized with the server, ensuring consistent gameplay for all players.

- **Integrated Translations**  
  Automatic in-game localization and label generation based on the selected game language.

## Supported Skills

### EpicMMOSystem Attributes
```
Strength  
Agility 
Intellect  
Endurance  
Vigour  
Specializing  
Level
```

### Vanilla Skills
```
Blocking  
Swim  
Run  
Jump  
Sneak  
Fishing  
WoodCutting  
Pickaxes  
Unarmed  
Bows  
Crossbows  
Swords  
Knives  
Clubs  
Spears  
Polearms  
Axes  
ElementalMagic  
BloodMagic
```

## Configuration Guide

After running the game for the first time with the mod installed, a configuration folder will be created inside BepInEx/config/.
This folder allows you to add and manage multiple configuration files instead of using a single configuration file.

All configuration files must follow this naming pattern:

radamanto.ItemRequirement.<identifier>.yml

Examples:

radamanto.ItemRequirement.weapons.yml
radamanto.ItemRequirement.armor.yml
radamanto.ItemRequirement.magic.yml
radamanto.ItemRequirement.epicmmo.yml

Files that do not follow this prefix pattern will not be loaded by the mod.
Inside these .yml files, you can define the skill or attribute requirements for each specific item.

### Example Configuration

```
- PrefabName: HelmetPadded
  Requirements:
  - Skill: Strength
    Level: 50
    BlockCraft: true
    BlockEquip: true
    EpicMMO: true
  - Skill: Swords
    Level: 40
    BlockCraft: true
    BlockEquip: true
    EpicMMO: false
- PrefabName: ArmorPaddedCuirass
  Requirements:
  - Skill: Strength
    Level: 50
    BlockCraft: true
    BlockEquip: true
    EpicMMO: true
  - Skill: Swords
    Level: 40
    BlockCraft: true
    BlockEquip: true
    EpicMMO: false
- PrefabName: ArmorPaddedGreaves
  Requirements:
  - Skill: Strength
    Level: 50
    BlockCraft: true
    BlockEquip: true
    EpicMMO: true
  - Skill: Swords
    Level: 40
    BlockCraft: true
    BlockEquip: true
    EpicMMO: false
```

### Notes

- You can use **any name** listed in the “Supported Skills” section above.  
- If the player does not meet the requirement, they **will not be able to craft or equip** the item.  
- All configurations are **server-synced**, meaning the same restrictions apply to everyone connected to the server.  
- Editing the configuration file while the game is running **automatically updates for all players**.

## Original Mod Reference

This mod is based on the original **ItemRequiresSkillLevel** created by [**Detalhes**](https://thunderstore.io/c/valheim/p/Detalhes/ItemRequiresSkillLevel/).
