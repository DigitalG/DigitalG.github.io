# Shikamaru
## Stats
- STR: 18 + 2.3
- AGI: 16 + 1.8
- INT: 25 + 3.5
- Attack Rate: 1.700000
- Attack Range: 600 (Ranged)
- Attack Damage: 20 - 30
- Armor: 0.000000
- Health: 200 + 0.300000
- Mana: 75 + -0.1
- Vision: 1800 | 800
## Abilities
### <b><font color='#BFBFBF'>Shadow Imitation</font></b>
Extends Shikamaru's shadow towards a target point <b><font color='#BFBFBF'>latching onto the first enemy Hero</font></b> it encounters. <br><br> Once bound, the enemy will be fully disabled while <b><font color='#BFBFBF'>copying Shikamaru's movement.</font></b> <br><br> Can be <b><font color='#f56342'>Toggled</font></b> after casting to cause affected enemies to <b><font color='#f56342'>move opposite of Shikamaru.</font></b>
|Behaviour|Damage Type|
|---|---|
|Point Target|Magical|

-RANGE:1300
-DURATION:1.50/2.00/2.50/3.00
### <b><font color='#9A86AC'>Shadow Sewing</font></b>
<b><font color='#FFFFFF'>CHANNELED</font></b> - <b><font color='#9A86AC'>Roots and Disarms</font></b> all enemies within the target radius while <b><font color='#9A86AC'>dealing Magic Damage overtime.</font></b>
|Behaviour|Damage Type|Target Team|Target Unit|
|---|---|---|---|
|Point Target/Channeled|Magical|Enemies|Heroes/Basic|

-RADIUS:225
-DURATION:1.8/2.2/2.6/3
### <b><font color='#FFFFFF'>Flash Bombs</font></b>
<b><font color='#FFFFFF'>Throws flash bombs</font></b> into the target area dealing minor <b>Magic Damage</b> while also applying a <b><font color='#FFFFFF'>Movement Speed Slow, Blind and Reveal</font></b>. <br><br> Enemies affected by <b><font color='#FFFFFF'>Flash Bombs</font></b> receive the following enchanced effects from spells: <br><br> <b><font color='#BFBFBF'>Shadow Imitation</font></b> - Duration increased by 1 second. <br> <b><font color='#9A86AC'>Shadow Sewing</font></b> - Silences affected targets.
|Behaviour|Damage Type|Target Team|Target Unit|
|---|---|---|---|
|Point Target|Magical|Enemies|Heroes/Basic|

-RADIUS:300/325/350/375
-RANGE:1000/1100/1200/1300
-MISS CHANCE25/30/35/40%
-MOVEMENT SPEED SLOW:-25/-30/-35/-40%
-DEBUFF DURATION:4
-DAMAGE:30/45/60/75
### <b><font color='#a3a2a2'>Wire Pull</font></b>
Pulls up wires within the target area causing all enemies to be <b><font color='#a3a2a2'>sucked towards the center,</font></b> disrupting them and dealing damage.<br><br>Causes any <b><font color='#EC5000'>Explosive Tag Traps</font></b> within the area to immediately trigger on the closest enemy hero.
|Behaviour|Damage Type|Target Team|Target Unit|
|---|---|---|---|
|Point Target|Magical|Enemies|Heroes/Basic|

-RADIUS400
-PULL DURATION:0.6
-DAMAGE:180
### <b><font color='#BFBFBF'>Shadow Imitation</font></b> - <b><font color='#f56342'>Switch</font></b>
Inverts the direction of <b><font color='#BFBFBF'>Shadow Imitation</font></b> victims.
|Behaviour|
|---|
|Toggle|

### <b><font color='#EC5000'>Explosive Tag Trap</font></b>
<b><font color='#BFBFBF'>Places an invisible Trap</font></b> that becomes active after a short delay. <br><br> Once active, the next enemy hero that steps in range is <b><font color='#9A86AC'>fully disabled</font></b> for a period of time. <br><br> Afterwards the trapped enemy explodes <b><font color='#EC5000'>dealing massive Magic Damage</font></b> around it. <br><br> Traps cannot be placed within the trigger radius of another Trap.
|Damage Type|
|---|
|Magical|

-TRIGGER RADIUS:300
-BIND DURATION:1.1/1.3/1.5
-MAX TRAPS:2/3/4 ([Talent] 5.0/6.0/7.0)
-ACTIVATION TIME:5/4/3 ([Talent] 3.0/2.0/1.0)
### <b><font color='#8cd973'>Meditation</font></b>
Shikamaru gains <b>Meditation Stacks</b> overtime while <b><font color='#8cd973'>not casting spells.</font></b> <br><br> Casting an ability consumes <b>Meditation Stacks</b> causing enemies affected by the ability to have lowered <b><font color='#8cd973'>Base Armor</font></b> <b><font color='#F7F7F7'>( +0.1% )</font></b> and <b><font color='#8cd973'>Base Magic Resistance.</font></b> <b><font color='#F7F7F7'>( +0.1% )</font></b>
|Behaviour|Damage Type|
|---|---|
|Passive|Magical|

-MAX STACKS:10
-ARMOR REDUCTION PER STACK:0.5%
-RESIST REDUCTION PER STACK:1%
-CHARGE RATE:5 ([Talent] 3.5)
-DEBUFF DURATION:8.0
## Talents
| | Talents | |
| :---: | :---: | :---: |
| +175 Radius Shadow Sewing Radius | 25 | +3 Tag Traps |
| -2s Explosive Trap Activation Time | 20 | +175 Flash Bomb Damage |
| -1.5s Meditation Charge Rate | 15 | -3s Shadow Imitation Cooldown |
| +0.5s Shadow Sewing Duration | 10 | +175 Health |
