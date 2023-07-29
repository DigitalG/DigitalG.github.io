# Onoki
## Stats
- STR: 23 + 2.8
- AGI: 17 + 2.2
- INT: 20 + 2.3
- Attack Rate: 1.700000
- Attack Range: 128 (Melee)
- Attack Damage: 10 - 12
- Armor: 1.000000
- Health: 200 + 0.300000
- Mana: 75 + -0.1
- Vision: 1800 | 800
## Abilities
### <b><font color='#ffffff'>Atomic Dismantling</font></b>
<b><font color='#ffffff'>Launches a small cube</font></b> that expands upon reaching the targeted area. All enemies caught inside the cube are <b><font color='#ffffff'>Rooted for a short duration</font></b>. <br><br> Once the Root duration expires, all enemies still within the area take <b><font color='#ffffff'>Magical Damage and are Stunned.</font></b>
|Behaviour|Damage Type|Target Team|Target Unit|
|---|---|---|---|
|Point Target|Magical|Enemies|Heroes/Basic|

- DAMAGE: 80/160/240/320 ([Talent] 280.0/360.0/440.0/520.0)
- RADIUS:300
- ROOT DURATION:1.5
- STUN DURATION:1.0/1.2/1.4/1.6
### <b><font color='#C1943D'>Stalagmite Armor</font></b>
<b><font color='#C1943D'>Increases the target's Armor</font></b> and gives a chance to deal <b><font color='#C1943D'>Physical Damage and Stun</font></b> when hit by a<b> Basic Attack.</b>
|Behaviour|Damage Type|Target Team|Target Unit|
|---|---|---|---|
|Unit Target|Physical|Allies|Heroes/Basic|

- RETURN DAMAGE: 60/120/180/240
- %RETURN CHANCE: 20/20/20/20
- STUN DURATION: 0.8/0.8/0.8/0.8
- BONUS ARMOR: 3/5/7/9 ([Talent] 11.0/13.0/15.0/17.0)
- ARMOR DURATION: 9/10/11/12
### <b><font color='#FFD67E'>Weighted Rock Technique</font></b>
<b><font color='#FFFFFF'>ON ALLY</font></b> - <b><font color='#FEEDC9'>Increases an ally's Movement Speed</font></b> and decreases the mana costs of their abilities for a short duration. <br><br> <b><font color='#FFFFFF'>ON ENEMY</font></b> - <b><font color='#D86C26'>Decreases an enemy's Movement Speed</font></b> and increases the mana cost of their abilities for a short duration.
|Behaviour|Target Team|Target Unit|
|---|---|---|
|Unit Target|Both|Heroes/Basic|

- %MOVE SPEED INCREASE: 16/24/32/40
- %MOVE SPEED SLOW: 16/24/32/40
- %MANA COST MODIFIER:10/15/20/25
- DURATION: 3/4/5/6
### <b><font color='#785b2f'>Boulder Throw</font></b>
<b><font color='#785b2f'>Throws a weighted boulder</font></b> at the targeted area dealing <b><font color='#785b2f'>Physical Damage</font></b> and <b><font color='#785b2f'>Stunning</font></b> enemies within the radius. <br><br> Damage and Stun are <b><font color='#785b2f'>based on Onoki's current Armor.</font></b>
|Behaviour|Damage Type|Target Team|Target Unit|
|---|---|---|---|
|Point Target|Magical|Enemies|Heroes/Basic|

- DAMAGE PER ARMOR:15
- STUN DURATION PER ARMOR:0.06
- RANGE:1200
- RADIUS:225
### <b><font color='#a89b87'>Rock Clone</font></b>
On use, <b><font color='#a89b87'>creates a Rock Clone</font></b> near Onoki. Only one Rock Clone can be active at a time. <br><br> Clones will automatically use <b><font color='#996c68'>Rock Fist Technique</font></b> and are created with <b><font color='#C1943D'>Stalagmite Armor</font></b> and <b><font color='#FFD67E'>Weighted Rock Technique</font></b> applied to them. <br><br> On death, Rock Clones will emit 1 pulse of the current level of <b><font color='#CABA9E'>Turn to Dust.</font></b>
|Behaviour|
|---|
|No Target|

- CLONE DURATION: 20
- %CLONE OUTGOING DAMAGE: 25
- %CLONE INCOMING DAMAGE: 400
### <b><font color='#CABA9E'>Turn to Dust</font></b>
<b><font color='#CABA9E'>Deals Pure Damage around Onoki</font></b> across 5 ([Talent] 6.0) Pulses based on each enemy's maximum HP. <br><br> The final pulse will deal <b><font color='#FFFFFF'>4% </font></b> <b><font color='#C1943D'>increased maximum HP damage.</font></b> <br><br> <b><font color='#FFFFFF'>Enemy's below a heath threshold</font></b> are <b>Instantly Killed</b> when damaged by a Pulse.
|Behaviour|Damage Type|Target Team|Target Unit|
|---|---|---|---|
|No Target|Pure|Enemies|Heroes/Basic|

- %MAX HEALTH PER PULSE6/7/8
- %INSTANT DEATH THRESHOLD: 10/12/14
- RADIUS: 400
- PULSES:5 ([Talent] 6.0)
- PULSE INTERVAL: 1
### <b><font color='#996c68'>Rock Fist Technique</font></b>
Onoki's next attack deals <b><font color='#996c68'>bonus Magic Damage</font></b> based on his current <b>Armor.</b> <br><br> Affected enemies have <b><font color='#996c68'>reduced Armor</font></b> <b><font color='#F7F7F7'>(+0.5)</font></b> for a short duration.
|Behaviour|Damage Type|
|---|---|
|Passive|Magical|

- DAMAGE PER ARMOR:5.0
- ARMOR REDUCTION:1.0
- DEBUFF DURATION:4.0
## Talents
| | Talents | |
| :---: | :---: | :---: |
| +5x Rock Fist Armor to Attack Multiplier | 25 | +200 Atomic Dismantling Damage and Pure |
| +1 Turn to Dust Pulse | 20 | +8 Stalagmite Extra Armor |
| +14% Cooldown Reduction | 15 | +225 Atomic Dismantling Range |
| +7%/-7% Weighted Rock Movement Effect | 10 | +12% Magic Resistance |
