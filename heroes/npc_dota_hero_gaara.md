# Gaara
## Stats
- STR: 18 + 2.0
- AGI: 14 + 1.5
- INT: 24 + 3.4
- Attack Rate: 1.700000
- Attack Range: 600 (Ranged)
- Attack Damage: 23 - 30
- Armor: 1
- Health: 200 + 0.300000
- Mana: 75 + 0.9
- Vision: 1800 | 800
## Abilities
### <b><font color='#D86C26'>Sand Coffin</font></b>
<b><font color='#FFFFFF'>CHANNELED</font></b> - Encases the target in sand <b><font color='#D86C26'>fully disabling them</font></b> while the ability is <b>Channeled.</b> <br><br> If the <b>Channel</b> is completed, the unit will take <b><font color='#D86C26'>Magic Damage</font></b> and is <b><font color='#D86C26'>Stunned.</font></b>
|Behaviour|Damage Type|Target Team|Target Unit|
|---|---|---|---|
|Unit Target/Channeled|Magical|Enemies|Heroes/Basic|

- DAMAGE: 80/160/240/320
- CHANNEL DURATION: 1.5
- STUN DURATION: 0.4/0.6/0.8/1.0
- CAST RANGE:700
### <b><font color='#C1943D'>Sand Shower</font></b>
<b><font color='#C1943D'>Massively slows enemies</font></b> caught within the radius. <br><br> Enemies are <b><font color='#C1943D'>dealt Magic Damage over time</font></b> while in the radius.
|Behaviour|Damage Type|Target Team|Target Unit|
|---|---|---|---|
|Point Target|Magical|Enemies|Heroes/Basic|

- RADIUS: 425
- %MOVE SPEED SLOW: 35/40/45/50
- DAMAGE PER SECOND: 30/55/80/105
- DURATION: 3.0
### <b><font color='#FFDD93'>Sand Armor</font></b>
Target friendly Unit absorbs <b><font color='#FFFFFF'>30%</font></b> Incoming Damage <b><font color='#FFDD93'>in exchange for Gaara's Mana</font></b> for a short duration. <br><br> Gaara absorbs <b><font color='#FFFFFF'>60%</font></b> Incoming Damage <b><font color='#FFDD93'>if casted upon himself.</font></b>
|Behaviour|Target Team|Target Unit|
|---|---|---|
|Unit Target|Allies|Heroes|

- REDUCED DAMAGE PER MANA: 0.55/0.7/0.85/1
- %MAX MANA USED:25/30/35/40
- SHIELD DURATION: 6/9/12/15
### <b><font color='#a88768'>Sand Spire</font></b>
<b><font color='#a88768'>Creates a Sand Spire</font></b> at target location that applies the current level of <b><font color='#AF9A88'>Blinding Sand</font></b> to enemies around it. <br><br> The <b>Sand Spire</b> allows you to cast Basic Abilities <b><font color='#a88768'>within Cast Range of the Sand Spire.</font></b> <br><br> Additionally, casting <b><font color='#D86C26'>Sand Coffin</font></b> near the <b>Sand Spire</b> or hitting it with <b><font color='#C1943D'>Sand Shower</font></b> or <b><font color='#CB5000'>Sand Tsunami</font></b> will consume it, amplifying the used ability.
|Behaviour|
|---|
|Point Target|

- DURATION:10
- BLINDING SAND RADIUS:400
- BONUS SAND COFFIN DAMAGE:120
- BONUS SAND COFFIN STUN:0.5
- BONUS SAND SHOWER RADIUS:225
- BONUS SAND TSUNAMI DAMAGE:150
### <b><font color='#CB5000'>Sand Tsunami</font></b>
<b><font color='#CB5000'>Unleashes a large wave of sand</font></b> towards a target point, dealing <b><font color='#C1943D'>Magic Damage and Stunning</font></b> all enemies in it's path.
|Behaviour|Damage Type|Target Team|Target Unit|
|---|---|---|---|
|Point Target/Unit Target|Magical|Enemies|Heroes/Basic|

- STUN DURATION: 1.5/2.0/2.5
### <b><font color='#AF9A88'>Blinding Sand</font></b>
Enemies affected by Gaara's <b>Basic Attacks</b> or <b>Abilities</b> have <b><font color='#AF9A88'>reduced Vision</font></b> and receive an <b><font color='#AF9A88'>Attack Speed Slow</font></b> <b><font color='#F9F9F9'>(+3)</font></b> for a short duration. <b><font color='#F9F9F9'>(+0.25s)</font></b>
|Behaviour|
|---|
|Passive|

- ATTACK SPEED SLOW: 10
- %VISION REDUCTION: 40
- DURATION: 4.0
## Talents
| | Talents | |
| :---: | :---: | :---: |
| Global Sand Tsunami Range | 25 | +380 Sand Coffin Damage |
| +1 Sand Armor Damage per Mana | 20 | +120 Sand Shower Radius |
| +250 Sand Coffin Range | 15 | +70 Attack Damage |
| +2 Mana Regen | 10 | +6% Spell Amplification |
