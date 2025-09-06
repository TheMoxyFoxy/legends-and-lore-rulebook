---
title: "Stats"
date: 2025-09-05T13:49:36-07:00
draft: true
---

# Stats

Characters have 5 primary stats:
| Name       | Shorthand | Description                                    |
| ---------: | :-------: | :--------------------------------------------- |
| Durability | DUR       | How durable the character's body and will are. |
| Strength   | STR       | How physically capable the character is.       |
| Dexterity  | DEX       | How swift and nimble the character is.         |
| Intellect  | INT       | How intelligent and learned the character is.  |
| Wisdom     | WIS       | How wise and adaptable the character is.       |

Base primary stats can only go up to a maximum of 6, though they can be increased beyond that through other influences, such as items or spells.

In addition, each character has _derived_ stats. These are stats that are directly influence by other stats and/or items.
| Name          | Shorthand | Description                                                                                                                                                                 |
| ------------: | :-------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Health Points | HP        | How much damage your character can take before being knocked unconscious. If you take twice this in damage, your character immediately dies.                                |
| Speed         | Speed     | How swift the character can move. This dictates how far they can move in a turn. This is based on `3 + DEX / 2`.                                                            |
| Evasion       | EVA       | How nimble or capable the character is in dodging and deflecting attacks. This is based on `10 + DEX`. This is used in Hit Rolls.                                           |
| Armor Class   | AC        | How strong the character in combination with their armor is. This starts at `8` and is increased (or even decreased) based on various bonuses. This is used in Wound Rolls. |
| Action Points | AP        | How many actions your character can take in a turn. At level 1, you start with 3, and gain 1 every 5 levels.                                                                |