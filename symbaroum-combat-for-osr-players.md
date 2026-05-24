# Symbaroum Combat for OSR Players
*A quick-start primer for players coming from OSE, Shadowdark, Dragonbane, and similar games*

---

## The One Rule That Changes Everything

In Symbaroum, **the players roll all the dice.** The GM never rolls. Enemy stats are fixed numbers that modify *your* rolls. Once you internalize this, the rest clicks into place quickly.

---

## The Core Mechanic

Roll **1d20 equal to or under your relevant Attribute** to succeed. That's it.

But almost every roll is *modified* — usually by an opponent's stat. The notation looks like this:

> **[Your Attribute ← Opponent's Attribute]**

The arrow means "modified by." Opponent attributes convert to modifiers using a simple table:

| Opponent's Attribute Value | Modifier Applied to **Your Attribute** | Effect on Your Chances |
|---|---|---|
| 5 | +5 | Much easier — your ceiling rises |
| 7 | +3 | Easier |
| 9 | +1 | Slightly easier |
| 10 | ±0 | No change |
| 11 | –1 | Slightly harder |
| 13 | –3 | Harder |
| 15 | –5 | Much harder — your ceiling falls |

> **Important for roll-under players:** The modifier adjusts your **Attribute** (the ceiling you're rolling under), not the die result. Adding +5 to your Attribute raises that ceiling, giving you more room to succeed. Subtracting 5 lowers it. This is the opposite sign convention from games that apply modifiers to the die roll — but the math works out the same way.

**Example:** Your Accurate is 13. You attack an enemy whose Defense is 11. Defense 11 = −1 modifier. Apply it to your Attribute: 13 − 1 = **12**. Roll 12 or under to hit.

Formula if you want to calculate it yourself: modifier = 10 − opponent's attribute value.

---

## The Eight Attributes

These replace both ability scores and skills. Everything flows from them.

| Attribute | What it Does in Combat |
|---|---|
| **Accurate** | Hitting things. Used for attack rolls. |
| **Quick** | Initiative order. Also used for acrobatics, standing up from prone. |
| **Strong** | Raw power. Determines your **Toughness** (hit points) and **Pain Threshold**. |
| **Cunning** | Knowledge and wit. Rarely used in direct combat. |
| **Discreet** | Stealth. Used for surprise attacks. |
| **Persuasive** | Social. Not a combat stat. |
| **Resolute** | Mental resistance and magic. Governs Corruption tolerance. |
| **Vigilant** | Perception and awareness. Used to avoid being surprised. |

### Secondary Stats (Derived from Attributes)

| Stat | Formula | What It Does |
|---|---|---|
| **Toughness** | = Strong (minimum 10) | Your hit points |
| **Pain Threshold** | = Strong ÷ 2 (round up) | Trigger point for knockdown effects |
| **Defense** | = Quick − Armor's Impeding value | Your dodge/parry target number |
| **Corruption Threshold** | = Resolute ÷ 2 (round up) | How much corruption before you get a stigma |

---

## Before Combat: Initiative

Whoever has the **highest Quick** chooses whether to act first or wait. There is no group initiative — it's individual, and it's fixed once set (you can delay your action to go later, but that delay becomes your slot for the rest of the fight).

**Tiebreakers in order:**
1. Highest **Vigilant**
2. Roll 1d20 — highest wins

**Long weapons get a free shot.** If you're carrying a weapon with the Long quality (spears, staves, polearms), you get one Free Attack when an enemy closes to melee range — unless they're *also* using a Long weapon. After that first contact, the advantage is gone.

---

## Each Turn: Your Action Economy

Every combatant gets **one Movement Action** and **one Combat Action** per turn. You can trade your Combat Action for a second Movement Action, but not the reverse.

### Movement Action — use it to:
- Move into or out of melee (enemies get a Free Attack if you disengage)
- Flank an enemy already engaged with an ally
- Draw or switch weapons
- Drink/apply an elixir on yourself
- Stand up from prone (requires a Quick test; fail = costs your whole turn)

### Combat Action — use it to:
- Attack (the main event)
- Use an active ability
- Administer first aid to a downed ally
- Replace it with a second Movement Action

### Reactions — unlimited per turn:
- **Defend yourself** (every incoming attack can be contested)
- **Free Attacks** (triggered by enemy movement — see below)

You don't spend actions to defend. Defense is always available as a reaction, as many times per turn as you're attacked.

---

## Resolving an Attack

### Step 1 — Attacker Rolls

The attacker makes an **[Accurate ← Defense]** test.

The defender's Defense is their Quick score, minus any penalty from their armor (armor's Impeding value). A shield adds +1 to Defense.

- If the roll **succeeds** (equal to or under the modified Accurate), the attack **hits**
- If the roll **fails**, the attack **misses**

> **OSR comparison:** There's no separate "to hit" roll vs. AC lookup. You're rolling under your own stat, modified by the enemy's dodge value. High enemy Quick = hard to hit. Low enemy Quick = easy to hit.

### Step 2 — Defender Can Contest (Reaction)

The defender may also roll **[Defense ← Accurate]** as a reaction. If *this* roll succeeds, the attack is completely avoided — parried or dodged. If it fails, the attack lands.

In practice: the attacker rolls first. If they miss, that's the end of it. If they hit, the defender may attempt their own Defense roll to negate it. Both getting to roll means combat has real tension on both sides — without the GM touching a die.

### Step 3 — Damage

If the attack lands and isn't negated:

1. **Attacker rolls weapon damage** (e.g., 1d8 for a sword)
2. **Defender rolls their Armor** (e.g., 1d4 for leather — yes, armor is rolled)
3. **Subtract armor from damage**: [Weapon Damage − Armor] = actual damage taken
4. Reduce the defender's **Toughness** by that amount

Minimum actual damage is 0 — if your armor roll beats the damage roll, you shrug it off.

> **OSR comparison:** Armor doesn't change your defense target number (that's Quick's job). Instead, armor *absorbs damage after a hit lands.* Think Dragonbane or Twilight 2000 more than OSE.

---

## Pain Threshold: When Big Hits Matter

If a single hit deals damage exceeding the target's **Pain Threshold** (Strong ÷ 2, rounded up), something extra happens. The *player who deals the damage* chooses which:

- The target is **knocked prone** (must spend a Movement Action and pass a Quick test to stand up; enemies get Advantage against prone targets)
- **OR** the attacker gets an immediate **Free Attack** against the target

This is a meaningful decision. Knocking a spellcaster prone wastes their turn. A Free Attack might down a nearly-dead enemy outright.

**Pain Threshold is per-hit, not cumulative.** Two hits of 4 each don't trigger a threshold of 6; one hit of 7 does.

---

## Free Attacks

A Free Attack is a bonus attack triggered by specific circumstances. It uses your weapon but only benefits from **passive** ability effects (not active ones):

**Triggers:**
- Enemy tries to disengage from melee (each engaged enemy gets one)
- Enemy moves *past* you to reach someone behind you
- You have a Long weapon and an enemy without one closes to melee (first turn only)
- Certain ability effects

You can gain at most one Free Attack per trigger type per turn — two enemies disengaging at once = one Free Attack, not two.

---

## Advantage

When you have Advantage on an attack:
- **+2 to your relevant Attribute** for the test
- **+1d4 extra damage** on a hit

**Conditions that grant Advantage:**
- Attacking someone who doesn't know you're there (successful [Discreet ← Vigilant] surprise)
- Flanking — two allies on opposite sides of a target both gain Advantage
- Target is prone
- You're attacking from higher ground

---

## Dying and Death

**Monsters** die at 0 Toughness.

**Player characters** at 0 Toughness are *dying*, not dead. They collapse and can't act. Each turn thereafter, on their initiative slot, they roll 1d20 for a **Death Test**:

| Roll | Result |
|---|---|
| 1 | Miracle — wake up with 1d4 Toughness, act next turn |
| 2–10 | Holding on — no change |
| 11–19 | Slipping away — third time this happens, you die |
| 20 | Dead (may speak last words) |

Someone can stabilize a dying character with first aid (a Combat Action + herbal cure, the Medicus ability, or a healing power).

Natural healing is **1 Toughness per day**. Herbal cures restore 1 immediately. The Medicus ability heals 1d4.

---

## Surprise

To surprise an enemy, the attacker makes a **[Discreet ← Vigilant]** test. Success grants one Free Attack at the start of the first turn, before initiative order kicks in.

For group ambushes: use the attackers' *lowest* Discreet against the defenders' *highest* Vigilant.

---

## Key Differences from OSR Games at a Glance

| | OSE / Shadowdark | Symbaroum |
|---|---|---|
| **Who rolls to hit** | Attacker only | Attacker rolls; defender can also roll to negate |
| **Armor** | Reduces chance to be hit (AC) | Absorbs damage after a hit lands |
| **Initiative** | Side-based or individual d6 | Individual; highest Quick chooses |
| **Damage floor** | Always 1 | Can be 0 if armor exceeds weapon damage |
| **HP** | Hit Dice, scales with level | = Strong (never below 10); changes slowly |
| **GM rolls** | GM rolls monsters | GM rolls nothing — all dice are yours |
| **Death** | At 0 HP | At 0 Toughness: start rolling Death Tests |
| **Big hits** | Same as small hits | Exceed Pain Threshold → knockdown or Free Attack |

---

## Solo Play Notes

Since the GM rolls nothing, Symbaroum works cleanly for solo play. Enemy stats are fixed numbers — you always know exactly what modifier you're rolling against. When adjudicating monster behavior, the Quick Start's narrative structure (scenes → turns → actions) maps well to oracle-driven solo play. Use the monster's **Resolute** to determine morale breaks, and its **Vigilant** to determine whether it notices stealth attempts.

For the Quick Start adventure *Blight Night*, the pre-made characters already have all their derived stats filled in, so you can focus on learning the attack resolution loop without doing any math first.

---

*Based on the Symbaroum Quick Start, Fria Ligan AB 2019*
