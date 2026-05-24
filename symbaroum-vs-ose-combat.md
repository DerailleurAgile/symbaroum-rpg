# Symbaroum Combat Rules: Compared to OSE (Old-School Essentials)

If you're familiar with **Old-School Essentials (OSE)** — the refined B/X D&D clone — Symbaroum's combat will feel very familiar: lethal, fast-paced, and narrative-driven. Both systems emphasize player skill, dangerous fights, and rulings over rules. However, Symbaroum streamlines things with **player-facing rolls** and attribute-based resolution.

**Core Philosophy (Shared with OSE)**:
- Deadly combat where positioning and smart play matter.
- No battle grids — theater of the mind with narrative description.
- GM as neutral arbiter (rulings, not just rules).

**Key Difference**: Symbaroum uses **roll-under** on attributes (1d20 ≤ Attribute). OSE uses **roll-over** THAC0 / Attack Matrix.

## PC Attributes: Symbaroum vs OSE

Symbaroum uses **8 attributes** (rated 5–15). OSE uses the classic **6 abilities** (3–18).

| Symbaroum Attribute | OSE Equivalent          | Primary Combat Role                          | Notes |
|---------------------|-------------------------|----------------------------------------------|-------|
| **Accurate**        | Strength / Dexterity    | To-hit with weapons (melee & ranged)        | Direct attack stat. |
| **Quick**           | Dexterity               | Initiative, movement, dodging                | Stronger initiative focus than OSE Dex. |
| **Strong**          | Strength / Constitution | Damage bonus, Toughness (HP), carrying       | Combines Str + Con. |
| **Vigilant**        | Wisdom                  | Perception, spotting ambushes, ties         | Like Wisdom for awareness. |
| **Resolute**        | Wisdom / Charisma       | Resisting magic, mental effects              | Mental fortitude / saves. |
| **Discreet**        | Dexterity               | Stealth, evasion                             | Sneaking / hiding. |
| **Persuasive**      | Charisma                | Social influence, intimidation               | Diplomacy & reactions. |
| **Cunning**         | Intelligence            | Problem-solving, alchemy, traps              | Knowledge & cleverness. |

**Key Contrasts**:
- **Fewer but Broader**: Symbaroum folds OSE's six into eight more specialized attributes. Every attribute is useful in combat/exploration (no "dump stats").
- **No Modifiers**: Symbaroum uses raw attribute scores for rolls (roll-under). OSE converts scores to small modifiers (+0 to +3).
- **Combat Integration**: Almost all Symbaroum attributes have direct combat applications (Accurate for attack, Quick for init, etc.). OSE relies more on class-based THAC0 and saves.
- **Balance**: Symbaroum characters feel more competent early on due to higher starting attributes and direct roll-under resolution.

**Example**: An OSE Fighter with high Strength gets attack/damage bonuses. A Symbaroum character with high Accurate gets better to-hit rolls directly.

## Core Resolution: Symbaroum vs OSE

| Mechanic              | Symbaroum                          | OSE Equivalent                     | Notes |
|-----------------------|------------------------------------|------------------------------------|-------|
| Core Roll             | 1d20 ≤ Attribute (modified)       | 1d20 ≥ THAC0 or target number     | Symbaroum: roll-under. OSE: roll-over. |
| To-Hit                | Accurate vs opponent's Defense    | Attack roll vs AC (THAC0 matrix)  | Defense acts like negative AC modifier. |
| Armor                 | Soak damage (roll armor die)      | Static AC bonus                   | Symbaroum armor reduces damage taken. |
| Initiative            | Highest Quick, tiebreak Vigilant  | 1d6 per side                      | Simpler, attribute-based. |
| Actions per Round     | 2 Actions                         | 1 Move + 1 Action                 | Similar flexibility. |
| Saving Throws         | Attribute checks or special       | Category-based saves (D/W/P/B/S)  | Symbaroum more flexible via attributes. |

## Turn Order & Initiative

**Symbaroum**: Compare **Quick** (highest first). Ties broken by **Vigilant**.

**OSE**: 1d6 per side.

**Comparison**: Symbaroum rewards fast characters more directly and removes dice variance.

## Attacking

**Symbaroum**:
1. Roll 1d20 ≤ **Accurate** (modified by opponent's **Defense**).
2. On hit: Weapon damage.
3. Opponent rolls armor die to soak.

**OSE**:
1. Roll 1d20 vs THAC0.
2. On hit: Weapon damage.

## Defense & Damage

**Symbaroum**: Active **Defense** roll when attacked. **Toughness** = HP. **Pain Threshold** = Dazed on excess damage.

**OSE**: Passive AC. Hit Points.

## Movement & Exploration

Both use similar exploration turns and encumbrance.

## Special Rules Comparison

| Symbaroum Feature     | OSE Parallel                     | Difference |
|-----------------------|----------------------------------|----------|
| Long Weapons          | Polearm reach / set spear        | Built-in Free Attack |
| Corruption            | No direct (like Sanity/Chaos)    | Mystical risk |
| Traits (Berserker)    | Fighter multiple attacks         | Ability-based |

**✅ File updated:** `Symbaroum_Combat_Rules_vs_OSE.md`

Here's the improved version with a **much more detailed, step-by-step combat example** showing actual rolls, modifiers, and clear explanations:

```markdown
# Symbaroum Combat Rules: Compared to OSE (Old-School Essentials)

... (previous sections remain unchanged) ...

## Detailed Combat Example (Side-by-Side)

**Scenario**: An ogre warrior (player character) with a long staff fights a heavily armored guard in a narrow corridor.

### Symbaroum Example

**Stats**:
- Ogre: Accurate 10, Quick 11, Strong 15, Defense 6, Robust (ignores 1D4 damage), Staff (1D6 damage, Long quality).
- Guard: Accurate 13, Defense +2 (from shield + armor), Armor 1D6 soak.

**Round 1**:
1. **Initiative**: Both have Quick 11 → Tie broken by Vigilant. Guard has higher Vigilant → Guard acts first.
2. **Ogre's Free Attack** (Long weapon): Ogre rolls 1d20 = **8** ≤ Accurate 10 (+1 Long) = **Hit!**
   - Damage: 1D6 = **5** + Robust bonus 1D4 = **3** → Total 8 damage.
   - Guard soaks with Armor 1D6 = **4** → Net **4 damage** to Guard's Toughness.
3. **Guard attacks**: Ogre rolls Defense 1d20 = **9** (needs ≤6 after -3 from Guard's Accurate 13) → **Miss!**
   - Guard hits for 1D8 = **6**. Ogre's Robust soaks 1D4 = **2** → Net **4 damage**.

**Round 2**:
- Ogre uses **Confusion** mystical power (Resolute roll) → Succeeds, paralyzing the Guard.
- Ogre smashes with staff: Automatic advantage vs paralyzed foe → Big hit!

**Outcome**: The fight is fast, swingy, and deadly. Armor soaks help, but one bad Defense roll can end you.

---

### OSE Equivalent Example (B/X Style)

**Stats**:
- Fighter (Level 2): THAC0 19, AC 4 (chain + shield), 1D8 damage.
- Guard: AC 4, HD 2, 1D8 damage.

**Round 1** (1d6 Initiative: Guard wins):
1. Guard attacks: Rolls 1d20 = **15** → Hits AC 4 (THAC0 19 needs 15+).
   - Damage 1D8 = **6**.
2. Fighter attacks: Rolls 1d20 = **17** → Hits AC 4.
   - Damage 1D8 = **5**.

**Key Contrast**:
- **Symbaroum**: Active Defense roll + variable armor soak makes every hit uncertain. Long weapons give tactical reach.
- **OSE**: Static AC + straightforward damage. More predictable but still deadly.

**Symbaroum feels more "active"** — you roll to defend yourself every time you're attacked, and armor can completely negate hits. OSE is faster to resolve but relies more on pre-calculated AC and THAC0.

## Tips for OSE Players in Symbaroum

- Treat **Accurate** like your attack bonus / THAC0.
- **Defense** is like rolling a saving throw to avoid being hit.
- **Armor soak** replaces OSE's static AC — it's more cinematic and swingy.
- Use your **2 Actions** creatively (Move + Attack, Attack + Power, etc.).
