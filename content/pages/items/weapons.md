---
title: "Weapons"
date: 2025-09-05T18:56:59-07:00
draft: true
---

# Weapons
Listed below are all of the weapons available to players at character creation.

## Longsword
| Stat           | Value           |
| -------------: | :-------------- |
| Type           | Sword (Martial) |
| Double-Handed  | Yes             |
| Hit Modifier   | STR             |
| Power          | `10 + STR`      |
| Damage Type    | Slashing        |
| Damage         | `1d8 +  STR`    |

{{% ability name="Cleave" type="Melee Attack" ap="2" %}}
Swing your sword in a wide arc, attacking all enemies within a unit around you. Has -1 to hit for each target.
{{% /ability %}}

## Shortsword
| Stat          | Value           |
| ------------: | :-------------- |
| Type          | Sword (Martial) |
| Double-Handed | No              |
| Hit Modifier  | STR/DEX         |
| Power         | `8 + MOD`       |
| Damage Type   | Slashing        |
| Damage        | `1d6 + MOD`     |

{{% ability name="Pommel Strike" type="Melee Attack" ap="1" power="8" %}}
Strike with the pommel of your blade, dealing `d4` damage.
{{% /ability %}}

## Shield
| Stat           | Value            |
| -------------: | :--------------- |
| Type           | Shield (Martial) |
| Double-Handed  | No               |
| Hit Modifier   | STR              |
| Wound Modifier | -1               |
| AC Bonus       | +1               |
| Power          | `4 + MOD`        |
| Damage Type    | Blunt            |
| Damage         | `1d4`            |

{{% ability name="Shield Bash" type="Melee Attack" ap="1" %}}
If this attack wounds, the target must make a Durability saving throw against your Strength (`10 + STR`) or be Disoriented.
{{% /ability %}}

## Staff
| Stat           | Value         |
| -------------: | :------------ |
| Type           | Staff (Basic) |
| Double-Handed  | Yes           |
| Hit Modifier   | DEX           |
| Power          | `4 + DEX`     |
| Damage Type    | Blunt         |
| Damage         | `1d4 + DEX`   |

{{% ability name="Swift Strike" type="Melee Attack" ap="1" %}}
Perform a melee attack against target creature.
{{% /ability %}}