---
layout: default
title: Druid
parent: Poplar's Overrides
nav_order: 1
---

# Druid

{: .summary}
> A practitioner of the eldest Arts, Druids are able to wear the skin of beasts and call the land to their aid.

| Level | Feats                                     | Wild Shape | Elemental Shape |
| ----- | ----------------------------------------- | ---------- | --------------- |
| 1     | Animal Companion, Zen Archery             | -          | -               |
| 2     |                                           | -          | -               |
| 3     |                                           | -          | -               |
| 4     |                                           | -          | -               |
| 5     | Wild Shape, Woodland Stride               | 2          | -               |
| 6     |                                           | 2          | -               |
| 7     |                                           | 2          | -               |
| 8     |                                           | 2          | -               |
| 9     |                                           | 2          | -               |
| 10    | Improved Wild Shape, Venom Immunity       | 4          | -               |
| 11    |                                           | 4          | -               |
| 12    |                                           | 4          | -               |
| 13    |                                           | 4          | -               |
| 14    |                                           | 4          | -               |
| 15    | Elemental Shape, Disease Immunity         | 6          | 2               |
| 16    |                                           | 6          | 2               |
| 17    |                                           | 6          | 2               |
| 18    |                                           | 6          | 2               |
| 19    |                                           | 6          | 2               |
| 20    | Elder Elemental Shape, Paralysis Immunity | Inf.       | 3               |

**Hit Die**: d8

**Proficiencies**: armor (light), weapons (druid)  

**Skill Points**: 4 + int modifier ( (4 + int modifier) * 4 at 1st level)   

**BaB Progression**: +3/4 / level (Mid)  

**Skill List**: animal empathy, concentration, craft armor, craft trap, craft weapon, heal, lore, parry, persuade, spellcraft  

**Special**: animal companion options include wizard/sorcerer familiars, spellcasting is now spontaneous

### Spell List

| Level | Life                 | Animal            | Nature            |
| ----- | -------------------- | ----------------- | ----------------- |
| 0     | Cure Minor Wounds    | Ultravision       | Owl's Wisdom      |
| 1     | Cure Light Wounds    | Summon Creature I | Entangle          |
| 2     | Cure Moderate Wounds | ... II            | Barkskin          |
| 3     | Cure Serious Wounds  | ... III           | Call Lightning    |
| 4     | Cure Critical Wounds | ... IV            | Stoneskin         |
| 5     | Healing Circle       | ... V             | Awaken            |
| 6     | Heal                 | ... VI            | Greater Stoneskin |
           
### Spell Progression

{% include two_third_caster.md %}

### Wild Shapes

{: .summary}
> See the [Wild Shape Wiki Page](https://nwn.fandom.com/wiki/Wild_shape) for the standard statistics. Note that armor and helmets have their properties added to the wildshape, but other items do not.

#### Standard Wildshape

| Name       | STR  | CON  | DEX  | AC   | Temp HP | Size   | Attack  | Notes                 |
| :--------- | :--- | :--- | :--- | :--- | :------ | :----- | :------ | :-------------------- |
| Badger     | 14   | 18   | 18   | 21   | +10     | tiny   | 1d4 + 2 | DR 5/+1, Blood Frenzy |
| Boar       | 18   | 18   | 18   | 19   | +10     | medium | 1d4 + 4 | Iron Horn             |
| Brown Bear | 26   | 22   | 10   | 14   | +20     | large  | 1d4 + 8 | -                     |
| Panther    | 18   | 14   | 22   | 21   | +10     | medium | 1d6 + 5 | Exp. Retreat          |
| Wolf       | 18   | 16   | 18   | 19   | +10     | medium | 1d6 + 5 | Fear Howl             |

#### Improved Wildshape

| Name            | STR  | CON  | DEX  | AC   | Temp HP | Size   | Attack   | Notes                             |
| :-------------- | :--- | :--- | :--- | :--- | :------ | :----- | :------- | :-------------------------------- |
| Dire Badger     | 16   | 22   | 20   | 26   | +20     | tiny   | 1d8 + 3  | DR 10/+2, Blood Frenzy            |
| Dire Boar       | 22   | 20   | 20   | 24   | +20     | medium | 1d8 + 6  | DR 5/+1, Iron Horn, Find Traps    |
| Dire Brown Bear | 30   | 24   | 12   | 19   | +40     | large  | 1d8 + 10 | DR 5/+1                           |
| Dire Panther    | 20   | 16   | 26   | 26   | +20     | medium | 2d6 + 5  | DR 5/+1, Exp. Retreat, Camouflage |
| Dire Wolf       | 22   | 18   | 20   | 24   | +20     | medium | 2d6 + 6  | DR 5/+1, Fear Howl, Stun Howl     |

#### Elemental Shape

| Name  | STR  | CON  | DEX  | AC   | Temp HP | Size   | Attack               | Notes                              |
| :---- | :--- | :--- | :--- | :--- | :------ | :----- | :------------------- | :--------------------------------- |
| Fire  | 20   | 26   | 20   | +5   | +20     | medium | 2d8 + 4 + 1d8 (fire) | DR 10/+2, Burning Hands            |
| Water | 26   | 20   | 22   | +5   | +20     | medium | 2d10 + 7             | DR 10/+2, Acid Arrow               |
| Earth | 30   | 22   | 10   | +10  | +20     | large  | 2d10 + 10            | DR 10/+2, Protection from Elements |
| Air   | 20   | 20   | 30   | +10  | +20     | medium | 2d8 + 4              | DR 10/+2, Gust of Wind             |

#### Elder Elemental Shape

| Name  | STR  | CON  | DEX  | AC   | Temp HP | Size   | Attack               | Notes                                       |
| :---- | :--- | :--- | :--- | :--- | :------ | :----- | :------------------- | :------------------------------------------ |
| Fire  | 24   | 30   | 20   | +10  | +30     | medium | 2d8 + 6 + 1d8 (fire) | DR 15/+3, Burning Hands, Elemental Shield   |
| Water | 30   | 24   | 22   | +10  | +30     | medium | 2d10 + 9             | DR 15/+3, Acid Arrow, Acid Sheath           |
| Earth | 34   | 22   | 10   | +15  | +30     | large  | 2d10 + 12            | DR 15/+3  Protection from Elements, Crumble |
| Air   | 24   | 20   | 34   | +15  | +30     | medium | 2d8 + 6              | DR 15/+3, Gust of Wind, Wounding Whispers   |


{% include notes.html content="
The Revised Druid is very different from their 3E counterpart.<br><br>

The new Druid is a hybrid class, not a full mage. They are more closely related to Bards than Wizards, and more heavily dependent on shapeshifting.<br><br>

They have fewer spells-per-day, but their spontaneous casting provides greater flexibility. Many of their forms have spell-like abilities as well. Several have had subtle improvements to creature weapons or armor.
" %}