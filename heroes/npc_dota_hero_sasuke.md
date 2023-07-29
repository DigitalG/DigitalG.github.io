# Sasuke
## Stats
- STR: 17 + 1.6
- AGI: 19 + 1.5
- INT: 23 + 2.8
- Attack Rate: 1.700000
- Attack Range: 128 (Melee)
- Attack Damage: 13 - 18
- Armor: 1.000000
- Health: 200 + 0.300000
- Mana: 75 + -0.1
- Vision: 1800 | 800
## Abilities
### <b><font color='#36B4EE'>Chidori</font></b>
<b><font color='#36B4EE'>Dashes towards a target point</font></b> at instant speed, dealing <b>Magic Damage</b> to all enemies caught in his path and briefly rooting them. <br><br> Additional <b>Magic Damage</b> is dealt <b><font color='#36B4EE'>based on Sasuke's Attack Damage</font></b>.
|Behaviour|Damage Type|Target Team|Target Unit|
|---|---|---|---|
|Point Target|Magical|Enemies|Heroes/Basic|

- ROOT DURATION: 0.1/0.2/0.3/0.4
- MAX DISTANCE: 650/700/750/800
- %BONUS DAMAGE: 100
### <b><font color='#8ee1fa'>Chidori Stream</font></b>
An electrical current is discharged around Sasuke <b><font color='#8ee1fa'>dealing Magic Damage and Stunning</font></b> all enemies within the radius.
|Behaviour|Damage Type|Target Team|Target Unit|
|---|---|---|---|
|No Target|Magical|Enemies|Heroes/Basic|

- RADIUS: 425 ([Talent] 600.0)
- DAMAGE: 75/125/175/225 ([Talent] 150.0/200.0/250.0/300.0)
- STUN DURATION: 0.5/0.6/0.7/0.8
### <b><font color='#ff0000'>Sharingan</font></b>
Grants <b><font color='#ff0000'>full Damage Evasion</font></b> for a limited number of damage instances or until the duration expires. <br><br> Additionally, <b><font color='#ff0000'>grants Attack Speed</font></b> for a short duration.
|Behaviour|
|---|
|No Target|

- INSTANCES:3/4/5/6
- BONUS ATTACK SPEED:20/30/40/50
- DURATION:8
### <b><font color='#ff9b0f'>Great Fireball Technique</font></b>
Sends out a fireball dealing <b><font color='#ff9b0f'>Magic Damage to enemies in a line.</font></b> <br><br> Enemies hit by the fireball <b><font color='#ff9b0f'>receive a Movement Speed Slow</font></b> and take minor <b>Magic Damage</b> over time.
|Behaviour|Damage Type|Target Team|Target Unit|
|---|---|---|---|
|Point Target|Magical|Enemies|Heroes/Basic|

- DAMAGE:320
- DAMAGE PER SECOND:20
- %MOVEMENT SLOW:35
- DURATION:3
### Curse Mark Level 2
Activates Sasuke's Curse Mark granting him new properties to his Basic Abilities as well as additional Spell Lifesteal and increased Movement Speed.<br><br><b><font color='#36B4EE'>Chidori:</font></b> Causes an afterimage <b><font color='#36B4EE'>Chidori</font></b> to trigger 0.5s after casting, dealing 50%% damage.<br><br><b><font color='#8ee1fa'>Chidori Stream:</font></b> Reduces enemy Magic Resistance by %stream_magic_reduction%%% for %stream_duration% seconds. Stacks up to %stream_max_stacks% times.<br><br><b><font color='#ff0000'>Sharingan:</font></b> Grants %sharingan_evasion%%% Evasion while active.<br><br><b><font color='#ff9b0f'>Great Fireball Technique:</font></b> Increases Damage by %fireball_damage%, duration by %fireball_bonus_duration% seconds, and reduces the healing and regeneration of affected targets by %fireball_heal_debuff%%%.
|Behaviour|
|---|
|No Target|

- BONUS MOVE SPEED:50
- %SPELL LIFESTEAL (Heroes):15
- %SPELL LIFESTEAL (Creeps):3
- DURATION:25
### <b><font color='#00D4FF'>Kirin</font></b>
<b><font color='#A5E3FF'>Marks the target unit</font></b> with Kirin, granting <b>True Sight</b> of the target unit for a short duration of time. <br><br> After the duration expires, the target is struck with a <b><font color='#00D4FF'>massive bolt of lightning dealing Magic Damage</font></b>. <br><br> Additional <b>Magic Damage</b> is dealt to the target <b><font color='#4DADFF'>based on health lost from Sasuke</font></b> during the effect’s duration.
|Behaviour|Damage Type|Target Team|Target Unit|
|---|---|---|---|
|Unit Target|Magical|Enemies|Heroes/Basic|

- DURATION: 6
- %LOST HEALTH BONUS DAMAGE: 30/45/60
### <b><font color='#dbf2ff'>Chidori Light Sword</font></b>
<b><font color='#dbf2ff'>After casting an ability</font></b>, Sasuke’s next <b>Basic Attack</b> inflicts <b><font color='#dbf2ff'>additional Magic Damage.</font></b> <b><font color='#F7F7F7'>(+4)</font></b> and briefly reduces <b>Attack Speed</b> and <b>Movement Speed</b>.

Nearby Enemies are also affected.
|Behaviour|Damage Type|
|---|---|
|Passive|Magical|

- BONUS DAMAGE:15 ([Talent] 40.0)
- %MOVE SPEED SLOW:70
- %ATTACK SPEED SLOW:60
- RADIUS:300
- SLOW DURATION:0.8
## Talents
| | Talents | |
| :---: | :---: | :---: |
| +7 Sharingan Instances | 25 | +60% Chidori Attack Damage |
| +175 Chidori Stream Radius | 20 | +275 Chidori Max Range |
| +75 Chidori Stream Damage | 15 | +12 Strength |
| +2.5 Mana Regen | 10 | +25 Chidori Light Sword Damage |
