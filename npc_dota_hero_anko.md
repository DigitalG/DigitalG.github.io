# Anko
## Stats
STR: 25 + 3
AGI: 14 + 1.4
INT: 16 + 1.8
Attack Rate: 1.7
Attack Range: 128 (Melee)
Attack Damage: 39 - 45
Armor: 1
Health: 200 + 0.300000
Mana: 75 + 0.9
Vision: 1800 | 800
## Abilities
### <b><font color='#00B730'>Summoning: Giant Snake</font></b>
<b><font color='#00B730'>Sends out a snake</font></b> grabbing the first enemy it encounters, dealing <b><font color='#00B730'>Pure Damage and pulling</font></b> them to Anko. <br><br> <b><font color='#00B730'>Deals Triple Damage</font></b> to creeps.
|Behaviour|Damage Type|
|-|-|
|Point Target|Pure|
RANGE: 1300
DAMAGE: 150/220/290/360
CREEP DAMAGE:300%
### <b><font color='#78D590'>Cobra Strike</font></b>
Deals<b><font color='#78D590'> Magic Damage</font></b> and <b><font color='#78D590'>reduces the Movement Speed</font></b> of a target enemy unit for a short duration. <br><br> <b><font color='#78D590'>The enemy is Silenced</font></b> for the duration of the effect.
|Behaviour|Damage Type|Target Team|Target Unit|
|-|-|-|-|
|Unit Target|Magical|Enemies|Heroes/Basic|
DAMAGE PER SECOND : 25/45/65/85
MOVEMENT SPEED SLOW: -20/-30/-40/-50%
DURATION: 3
### <b><font color='#2CEA5E'>Venomous Assault</font></b>
<b><font color='#2CEA5E'>Unleashes snakes</font></b> from Anko overtime that deal <b><font color='#2CEA5E'>Magic Damage</font></b> to nearby enemies prioritizing Heroes. <br><br> Enemies take <b><font color='#2CEA5E'>increased damage for each consecutive snake</font></b> that damages them.
|Behaviour|Damage Type|Target Team|Target Unit|
|-|-|-|-|
|No Target|Magical|Enemies|Heroes|
DAMAGE: 40/50/60/70
BONUS DAMAGE: 10/12/14/16
SNAKE INTERVAL: 1
DURATION: 5 ([Shard] 7.0)
### <b><font color='#B8D3BE'>Twin Sacrfice</font></b>
Forms a suicide pact dealing <b><font color='#B8D3BE'>Magic Damage to both</font></b> Anko and the target enemy. <br><br> Damage dealt to both Heroes is <b><font color='#2CEA5E'>based on their missing Health</font></b>.
|Behaviour|Damage Type|Target Team|Target Unit|
|-|-|-|-|
|Unit Target|Magical|Enemies|Heroes/Basic|
MISSING HP AS DAMAGE: 50/60/70%
SELF MISSING HP AS DAMAGE: 50/60/70%%
### <b><font color='#AA43D8'>Student of Orochimaru</font></b>
Grants Anko passive <b><font color='#AA43D8'>Spell Lifesteal.</font></b> <b><font color='#F7F7F7'>(+0.5% )</font></b> <br><br> Additionally, a <b><font color='#AA43D8'>Basic Dispel</font></b> is applied to Anko after <b><font color='#AA43D8'>taking damage to a threshold. </font></b> <b><font color='#F7F7F7'>(-%damage_threshold_per_level_bonus% HP)</font></b><br><br><b><font color='#AA43D8'>Spell Lifesteal</font></b> is reduced to %creep_value%%% against creeps.
|Behaviour|
|-|
|Passive|
SPELL LIFESTEAL: 10.0%
DAMAGE THRESHOLD: 650.0
## Talents
| | Talents | |
| :-: | :-: | :-: |
| +1 Venomous Assault Snakes Per Second | 25 | -6s Giant Snake Cooldown |
| +20 Strength | 20 | +80 Venomous Assault Snake Damage |
| --15% Twin Sacrifice Self Damage | 15 | +2s Cobra Strike Slow Duration  |
| +12% Magic Resistance | 10 | +5 Armor |
