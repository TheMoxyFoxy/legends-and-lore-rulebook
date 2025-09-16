---
title: "Weapons"
date: 2025-09-05T18:56:59-07:00
draft: true
---

# Weapons
Listed below are all of the weapons available to players at character creation.

## Dagger
| Stat           | Value            |
| -------------: | :--------------- |
| Type           | Dagger (Martial) |
| Melee          | Yes              |
| Double-Handed  | No               |
| Range          | 1 unit           |
| Hit Modifier   | DEX              |
| Power          | `4 + DEX`        |
| Damage Type    | Slashing         |
| Damage         | `1d4 +  DEX`     |

{{% ability name="Throw Dagger" type="Ranged Attack" ap="1" range="3 units" %}}
You throw your dagger at any target. You can collect the dagger by stepping on the hex it is at (where it fell, or next to the opponent it's stuck in) and activating Use Small Item.
{{% /ability %}}

{{% ability name="Thrust" type="Melee Attack" ap="1" %}}
You thrust your dagger forwards, dealing piercing damage to the target.
{{% /ability %}}

## Longsword
| Stat           | Value           |
| -------------: | :-------------- |
| Type           | Sword (Martial) |
| Melee          | Yes             |
| Double-Handed  | Yes             |
| Range          | 1 unit          |
| Hit Modifier   | STR             |
| Power          | `10 + STR`      |
| Damage Type    | Slashing        |
| Damage         | `1d8 + STR`     |

{{% ability name="Cleave" type="Melee Attack" ap="2" %}}
Swing your sword in a wide arc, attacking all enemies within a unit around you. Gets -1 to hit for each target.
{{% /ability %}}

## Shortsword
| Stat          | Value           |
| ------------: | :-------------- |
| Type          | Sword (Martial) |
| Melee         | Yes             |
| Double-Handed | No              |
| Range         | 1 unit          |
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
| Melee          | Yes              |
| Range          | 1 unit           |
| Hit Modifier   | STR              |
| Wound Modifier | -1               |
| AC Bonus       | +1               |
| Power          | `4 + MOD`        |
| Damage Type    | Blunt            |
| Damage         | `1d4`            |

{{% ability name="Shield Bash" type="Melee Attack" ap="1" %}}
If this attack wounds, the target must make a Durability saving throw against your Strength (`10 + STR`) or be Disoriented.
{{% /ability %}}

## Spear
| Stat           | Value           |
| -------------: | :-------------- |
| Type           | Spear (Martial) |
| Melee          | Yes             |
| Double-Handed  | Yes             |
| Range          | 2 units         |
| Hit Modifier   | STR             |
| Power          | `10 + STR`      |
| Damage Type    | Piercing        |
| Damage         | `1d8 +  STR`    |

## Staff
| Stat           | Value         |
| -------------: | :------------ |
| Type           | Staff (Basic) |
| Double-Handed  | Yes           |
| Melee          | Yes           |
| Range          | 1 unit        |
| Hit Modifier   | DEX           |
| Power          | `4 + DEX`     |
| Damage Type    | Blunt         |
| Damage         | `1d4 + DEX`   |

{{% ability name="Swift Strike" type="Melee Attack" ap="1" %}}
Perform a melee attack against target creature.
{{% /ability %}}