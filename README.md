# OPieExtraConditions

An addon for World of Warcraft, adding extra visibility conditions to [OPie](https://www.curseforge.com/wow/addons/opie) slices.

CurseForge: https://www.curseforge.com/wow/addons/opieextraconditions

# Available conditions

OPie visibility conditions can use [the vanilla macro conditions](https://wowpedia.fandom.com/wiki/Macro_conditionals) and [OPie extended conditionals](https://www.townlong-yak.com/addons/opie/extended-conditionals).

This addon adds the following conditions:

## `[map]`

A `[map]` condition can be used to check whether the player is on a given map (or its submap).

For example, `[map:dragon isles]` will be active if the player is on any Dragon Isles map, including the city of Valdrakken.

As usual, `[nomap:whatever]` also works, just like other conditions.

## `[riding]`

A `[riding]` condition can be used to check whether the player has learned any (or a specific) rank of the riding/flying skill.

Just `[riding]` will be active if the player has learned any rank of riding/flying.

You can specify the rank of the skill like this: `[riding:<rank>]`:
* apprentice/60
* journeyman/100
* expert/150/flying
* master/310

For example, `[riding:flying]` will be active if the player has learned at least the Expert rank of riding (so, Expert or Master).

As usual, `[noriding]` or `[noriding:whatever]` also works, just like other conditions.

## `[dragonridable]`

A `[dragonridable]` condition can be used to check whether Dragonriding mounts can be used in the given zone.

As usual, `[nodragonridable]` also works, just like other conditions.

# Release notes

## 1.0.0
Released 3 December 2022.

* Initial release.