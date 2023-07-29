# Naruto
## Stats
- STR: 24 + 3.2
- AGI: 16 + 1.6
- INT: 19 + 2.0
- Attack Rate: 1.700000
- Attack Range: 128 (Melee)
- Attack Damage: 34 - 37
- Armor: 0.000000
- Health: 200 + 0.000000
- Mana: 75 + -0.1
- Vision: 1800 | 800
## Abilities
### <b><font color='#ff8000'>Shadow Clone</font></b>
<b><font color='#FFFFFF'>ACTIVE</font></b> - <b><font color='#ff8000'>Consumes a Shadow Clone charge</font></b> creating clones that spawn in random locations within a nearby radius. <br><br> Shadow Clone charges <b><font color='#ff8000'>are restored overtime</font></b> with a maximum of 3 charges. <br><br> <b><font color='#FFFFFF'>AUTO-CAST</font></b> - Clones will <b><font color='#ff8000'>automatically attack visible enemies</font></b> prioritizing heroes.
|Behaviour|
|---|
|No Target|

- CLONE PER CHARGE:1/2/3/4
- %CLONE DAMAGE:25 ([Talent] 39.0)
- %CLONE DAMAGE TAKEN:700
- CLONE DURATION:12.0
### <b><font color='#0fc7ff'>Rasengan</font></b>
Gathers Chakra in the User's hand causing their next attack to <b><font color='#0fc7ff'>deal additional Magic Damage</font></b>. <br><br> On impact the <b><font color='#0fc7ff'>target will be knocked forward</font></b> and receive a short <b>Movement Speed</b> slow.
|Behaviour|Damage Type|
|---|---|
|No Target|Magical|

- DAMAGE:90/180/270/360 ([Talent] 320.0/410.0/500.0/590.0)
- %MOVEMENT SLOW:20/25/30/35
- SLOW DURATION:3.0
- KNOCKBACK:450
- RASENGAN DURATION:12.0
### <b><font color='#ffb300'>Naruto Rendan</font></b>
<b><font color='#FFFFFF'>ACTIVE</font></b> - <b><font color='#ffb300'>Charges an enemy unit</font></b> granting additional <b>Physical Damage</b> and appearing <b><font color='#ffb300'>behind the enemy </font></b>on next attack. <br><br> <b><font color='#FFFFFF'>PASSIVE</font></b> - <b><font color='#ffb300'>Clones will use this ability</font></b> automatically when attacking dealing Physical Damage on next attack.
|Behaviour|Damage Type|Target Team|Target Unit|
|---|---|---|---|
|Unit Target|Physical|Enemies|Heroes/Basic|

- HERO DAMAGE60/100/140/180
- CLONE DAMAGE10/14/18/22
- CHARGE SPEED:650/700/750/800
### <b><font color='#3CFEFF'>Rasenshuriken</font></b>
Throws a Rasenshuriken at the target dealing <b><font color='#3CFEFF'>Magic Damage and Stunning</font></b> nearby enemies on impact. <br><br> Additional Magic Damage is dealt to enemies <b><font color='#3CFEFF'>based on Naruto's Attack Damage.</font></b>
|Behaviour|Damage Type|Target Team|Target Unit|
|---|---|---|---|
|Unit Target|Magical|Enemies|Heroes/Basic|

- BASE DAMAGE:100
- ATTACK DAMAGE MULTIPLIER:2.0
- STUN DURATION:1.2
- RADIUS:250
### <b><font color='#ab0270'>Tailed Beast Ball</font></b>
<b><font color='#ab0270'>Fires a massive ball</font></b> of massed chakra after charging the attack. <br><br> The ball of chakra deals <b>Magic Damage</b> that is <b><font color='#ab0270'>amplified by Naruto's Strength.</font></b>
|Behaviour|Damage Type|
|---|---|
|Point Target|Magical|

- RANGE:2200
- RADIUS:300
- BASE DAMAGE:250
- %STRENGTH DAMAGE:400
### <b><font color='#ffc400'>Kyuubi Chakra Mode</font></b>
Enters Kyuubi Chakra Mode (KCM) gaining increased <b><font color='#ffc400'>Movement Speed,</font></b> lowered <b><font color='#ffc400'>Base Attack Time,</font></b> and tripling the effects of <b><font color='#ffc757'>Kyuubi Chakra</font></b>. <br><br> Additionally, grants the following per level: 


<font color='yellow'>LEVEL 1</font> - <b><font color='#0fc7ff'>Rasengan</font></b> has no cast time.
<font color='orange'>LEVEL 2</font> - Grants <b><font color='#3CFEFF'>Rasenshuriken.</font></b>
<font color='red'>LEVEL 3</font> - Grants <b><font color='#ab0270'>Tailed Beast Ball.</font></b>
|Behaviour|
|---|
|No Target|

- DURATION:25
- BASE ATTACK TIME:1.5/1.4/1.3
- BONUS MOVESPEED:50
### <b><font color='#ffc757'>Kyuubi Chakra</font></b>
Passively grants increased <b><font color='#ffc757'>Health Regeneration</font></b> <b><font color='#F7F7F7'>(+0.75)</font></b> and <b><font color='#ffc757'>Mana Regeneration.</font></b> <b><font color='#F7F7F7'>(+0.25)</font></b> <br><br> Effect is tripled while under the effect of <b><font color='#ffc400'>Kyuubi Chakra Mode.</font></b>
|Behaviour|
|---|
|Passive|

- HEALTH REGEN:1.5
- MANA REGEN:0.5
## Talents
| | Talents | |
| :---: | :---: | :---: |
| Tailed Beast Bomb Pure Damage | 25 | KCM Expiring Restores Shadow Clone Charges |
| +14% Shadow Clone Damage | 20 | +230 Rasengan Damage |
| +4 Kyuubi Chakra Health Regen | 15 | +2.5 Kyuubi Chakra Mana Regen |
| +5 All Stats | 10 | +175 Rendan Movement Speed |
