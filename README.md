# PF2e-Battle-Harbinger-Extended
The Battle Harbinger Extended module introduces an expanded version of the Pathfinder Second Edition (PF2e) Battle Harbinger archetype.

---

## Credits and Thanks

**Credit and thanks to the following:**

* **CptLask** (CptLask)
* **lago508** (lago508)
* **Omena** (omenatyyppi)
* **allegedgamer**
* **Lank** (lank891)
* **Moth** (mothmariner)
* **kalnix** (kalnix)
* **Feindel** (Vestige321)
* **Wrath** (WrathofKain)
* **Athare** (chocoenjoyer42)
* **Valenwoods**
* **Vappy**
* **Ezarian** (Will)

**PF2e Foundry:** Wave and Tikael for helping debug and provide automation recommendations.

**Cody M. – The Sleeping Dragon Inn**, and **Lee – Role Play Legends**: For letting me playtest these changes as a character in a campaign.

---

## Overall Design Philosophy

* **Front-load the Fantasy:** Early levels now deliver the “aura warrior” promise through baseline Aura Enhancement, scalable bonuses, and heavy-armor competence.
* **Player Agency & Action Economy:** Empowered Onslaught lets players decide how aggressively to spend actions/reactions; Notable Creed turns the Battle Font into a true round-by-round option.
* **High-Level Excitement:** Faith’s Flare and Devastation’s Herald provide set-piece moments akin to other martial-caster hybrids’ top-end feats.
* **Smoother Power Curve:** Level-based scaling and slot-refresh item prevent the archetype from feeling anemic at low levels or resource-starved on long adventuring days.
* **Deeper spell-slot progression:** Creed Magic now scales through Lv 18.
* **More versatile weapon customization:** Armament rune lines shift earlier and culminate at Lv 20.
* **Adds a proactive anti-magic strike:** Devout Unraveling.
* **Remastered, alignment-agnostic aura spells:** Matches Paizo’s 2024/2025 Sanctified rules.

---

## Battle Harbinger – Design Summary

The table below highlights the most significant differences between Paizo’s published **Battle Harbinger** archetype and the community-driven **Battle Harbinger Extended** revision. These changes collectively transform the Battle Harbinger from a niche support archetype into a flexible, front-line “holy herald” that can keep pace with Paizo’s martial wave-caster blends while preserving the original aura-centric identity.

| Design Area                | **Paizo Battle Harbinger (Original)**                                                                                     | **Battle Harbinger Extended (This Conversation)**                                                                                                                                                                 | Rationale & Impact                                                                                                            |
| -------------------------- | ------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| **Key Ability**            | Fixed to **Wisdom** (via Battle Creed).                                                                                | Player chooses **Strength, Dexterity, or Wisdom** at Dedication.                                                                                                                                                           | Enables STR-based melee concepts; broadens build space.                                                                       |
| **Heavy-Armor Access**     | Gated behind the *Harbinger’s Protection* feat (6th).                                                                     | Granted automatically in the **Dedication** (baseline).                                                                                                                                                           | Removes a “tax” feat; lets the archetype fulfill “holy knight” fantasy sooner.                                                |
| **Aura Enhancement**       | *Aura Enhancement* feat (4th) adds benediction/malediction slots.                                                         | That feat folded into **Battle Creed** baseline.                                                                                                                                                                  | Ensures every Harbinger feels like an aura specialist from level 2.                                                           |
| **Maximum Aura Bonus**     | Hard-capped at **+4** (reachable only after Lv 12 feat).                                                                  | Scales by level: +2 (1-6), +3 (7-13), +4 (14-20).                                                                                                                                                                 | Smooth power curve; early play no longer feels under-powered.                                                                 |
| **Empowered Onslaught**    | *Reaction* on a crit + Sustain; raises **one** aura +1.                                                                   | Split into two modes (once/round):<br>• **Lesser** *Free Action* on a hit (+1).<br>• **Greater** *Reaction* on a crit (+2).                                                         | Player choice: keep Reaction for Reactive Strike or defense or spend it for bigger boost. Works even if you can’t (or won’t) Sustain that round. |
| **Initiative Utility**     | None.                                                                                                                     | **Flash of Faith** feat 6: cast a Battle-Font spell *free* when rolling initiative.                                                                                                                               | Gives the archetype a signature “opening move.”                                                                               |
| **Creed Magic (Feat 8)**           | Two 2nd-rank slots (Resist Energy, See the Unseen, Sure Strike, Water Breathing) → **only** 3rd-rank at Lv 10 (adds Haste, Heroism) | **Progressive scaling:** <br> • Lv 8 : 2nd-rank slots (same list) <br> • Lv 10: 3rd-rank (+Haste, Heroism) <br> • Lv 12: 4th-rank (+Fly, Unfettered Movement) <br> • Lv 14: 5th-rank (+Death Ward, Wisdom of the Winds) <br> • Lv 16: 6th-rank (+Truesight, Scintillating Safeguard) <br> • Lv 18: 7th-rank (+Regenerate, Spell Riposte) | Keeps creed slots relevant through late game; emphasizes “combat-support caster” identity                         |
| **Armament Line**                  | **Harbinger’s Armament** (Lv 8) <br> **Greater Armament** (Lv 16)                                                                   | Shifted earlier for relevance: <br> • **Harbinger’s Armament** → Lv 4 (property rune pool) <br> • **Greater Armament** → Lv 12 (adds brilliant, elemental, etc.) <br> • **Exalted Armament** (new Lv 20): adds Animated, Greater Fearsome, Keen, etc.; 1-action rune swap                                                                | Early access to signature weapon; Lv 20 feat grants ultimate flexibility                                          |
| **Extra-Casting Economy**  | *Tandem Auras* feat 12 only makes Sustain more efficient.                                                                 | **Notable Creed** feat 12: cast **any** Battle-Font spell as **1 action** once per round.                                                                                                                         | Dramatically improves mid-fight spell cadence; replaces under-whelming original feat.                                         |
| **High-Level Power Spike** | *Empowered Onslaught* upgrade (+1) at Lv 12; no true capstone.                                                            | **Faith’s Flare** (14) over-charges one aura to max;<br>**Lasting Conviction** (14) can extend it to 2–3 rounds;<br>**Devastation’s Herald** (20) collapses up to 3 auras for 10d6 Spirit dmg each (60-ft burst). | Adds the big, cinematic moments expected at high levels and a meaningful Lv 20 “nuke.”                                        |
| **Dispelling Tool**                | None                                                                                                                                | **Devout Unraveling** (Feat 16): two-action Strike → counteract spell (rank = ½ level, uses class DC)                                                                                                                                                                                                                                    | Provides on-brand anti-magic ability, similar to the Rogue and Magus martials                                             |
| **Item Support**           | No archetype-specific items.                                                                                              | **Armored Gorget** (11): +2 Intimidation; 1/day restores a Battle-Aura slot.                                                                                                                                      | Solves long-day slot attrition without adding Focus mechanics.                                                                |
| **Martial Feat Access**    | None listed.                                                                                                              | *Slam Down* and *Crashing Slam* (fighter feats) added to the archetype’s bonus-feat list.                                                                                                                         | Small boost to weapon-centric builds; reflects “battlefield control” theme.                                                   |
| **Progression Rhythm**     | Several dead levels; minor features appear on even levels (off-cycle with Paizo’s class-feature every-odd-level pattern). | **Minor Creed** (Lv 3), **Notable Creed** (Lv 11), **True Creed** (Lv 15) realigned to Paizo’s odd-level cadence.                                                                                                 | Matches Paizo’s internal design guidelines; easier to read at a glance.                                                       |
| **Spell Options (New/Remastered)** | Alignment-based **Divine Aura** & **Divine Armageddon**                                                                             | **Faith’s Bulwark** (holy/unholy version of Divine Aura) <br> **Sanctified Armageddon** (remastered Divine Armageddon)                                                                                                                                                                                                                   | Alignment removed; uses Remaster’s holy/unholy & neutral damage, keeping class compatible with ORC-licensed rules |


---

### **Channel Combat Focus**

Once per round, you can use **Lesser** or **Greater Empowered Onslaught** to enhance the status bonus to a battle aura. Increase its current status bonus or penalty to a maximum based on your level. This bonus remains for the rest of that aura’s duration.

| Level | Maximum Aura Bonus |
| ----- | ------------------ |
| 1–6   | +2                 |
| 7–13  | +3                 |
| 14–20 | +4                 |
