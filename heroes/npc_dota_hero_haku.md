# Haku
## Stats
- STR: 18 + 1.8
- AGI: 22 + 2.8
- INT: 23 + 3.4
- Attack Rate: 1.700000
- Attack Range: 550 (Ranged)
- Attack Damage: 21 - 26
- Armor: -1.000000
- Health: 200 + 0.300000
- Mana: 75 + -0.1
- Vision: 1800 | 800
## Abilities
### <b><font color='#9784FF'>Crippling Senbon</font></b>
Fires a senbon at the target dealing <b><font color='#9784FF'>Magic Damage and a brief Stun.</font></b> <br><br> Deals additional Damage based on Haku's <b><font color='#9784FF'>Attack Damage.</font></b> <br><br> Adds stacks of <b><font color='#95EEF1'>Endless Wounds.</font></b>
|Behaviour|Damage Type|Target Team|Target Unit|
|---|---|---|---|
|Unit Target|Magical|Enemies|Heroes/Basic|

- STUN DURATION: 0.2/0.3/0.4/0.5
- ENDLESS WOUNDS STACKS: 9/10/11/12
- %ATTACK DAMAGE MULT: 20/35/50/65
### <b><font color='#47fff0'>Needles of Death</font></b>
A wave of ice falls onto the target area dealing <b><font color='#47fff0'>Magic Damage and a brief Root.</font></b> <br><br> <b><font color='#47fff0'>A second wave will fall</font></b> shortly after the first, causing the same effect. <br><br> Each wave can add stacks of <b><font color='#95EEF1'>Endless Wounds.</font></b>
|Behaviour|Damage Type|Target Team|Target Unit|
|---|---|---|---|
|Point Target|Magical|Enemies|Heroes/Basic/Buildings|

- RADIUS: 275
- DAMAGE: 70/95/120/145
- WAVE DELAY: 1.2
- STUN DURATION: 1.0
- ENDLESS WOUNDS STACKS: 10
### <b><font color='#C0EEFF'>Demonic Speed</font></b>
Haku <b><font color='#C0EEFF'>dashes to a target point</font></b> at a high speed while sending a <b><font color='#C0EEFF'>Basic Attack</font></b> at the nearest enemy unit. <br><br> Basic Attack will prioritize Heroes.
|Behaviour|Damage Type|Target Team|Target Unit|
|---|---|---|---|
|Point Target|Physical|Enemies|Heroes/Basic|

- ATTACK SEARCH RANGE:900
### <b><font color='#88C3F7'>Mirror Shard</font></b>
Haku enters a single <b><font color='#9DCBF7'>Ice Mirror</font></b> while maintaining the ability to cast spells and deal full <b>Basic Attack</b> damage.<br><br>Casting <b><font color='#9DCBF7'>Crystal Ice Mirrors</font></b> or <b><font color='#C0EEFF'>Demonic Speed</font></b> will cause this effect to end.
|Behaviour|Damage Type|Target Team|Target Unit|
|---|---|---|---|
|No Target|Physical|Enemies|Heroes/Basic|

- MIRROR HP:4
- DURATION:4
### <b><font color='#88C3F7'>Mirror Shard</font> - <font color='tomato'>Cancel</font></b>
Destroys the <b><font color='#88C3F7'>Mirror Shard</font></b> and causes Haku to reappear.
|Behaviour|
|---|
|No Target|

### <b><font color='#9DCBF7'>Crystal Ice Mirrors</font></b>
Seperates Haku into a <b><font color='#9DCBF7'>circle of Ice Mirrors</font></b>. <br><br> <b><font color='#9DCBF7'>Ice Mirrors</font></b> possess a <b><font color='#9DCBF7'>Ranged Attack</font></b> and inflict stacks of <b><font color='#89BBCE'>Endless Wounds.</font></b> <br><br> <b><font color='#9DCBF7'>Ice Mirrors</font></b> are impassable but can be <b><font color='#9784FF'>destroyed by</font></b> <b><font color='#FFFFFF'>3</font></b> <b><font color='#9784FF'>Basic Attacks.</font></b> <br><br> Haku can manually end the <b><font color='#9DCBF7'>Ice Mirrors</font></b> duration with the <b><font color='#FFFFFF'>Cancel Ability</font></b> possessed by all Ice Mirrors.
|Behaviour|Damage Type|Target Team|Target Unit|
|---|---|---|---|
|No Target|Physical|Enemies|Heroes/Basic|

- RADIUS: 425
- DURATION: 4
- MIRROR DAMAGE: 11/18/25
- MIRROR HP: 3
- MIRROR ATTACK RANGE: 600
### <b><font color='#95EEF1'>Endless Wounds</font></b>
Causes Haku's <b>Basic Attacks</b> and <b>Abilities</b> to apply stacks of <b><font color='#95EEF1'>Crippling Wounds</font></b> up to a maximum limit. <b><font color='#F7F7F7'>(+2)</font></b> <br><br> Each stack deals <b><font color='#95EEF1'>Magic Damage</font></b> per second and applies a <b><font color='#95EEF1'>Movement Speed Slow.</font></b>
|Behaviour|Damage Type|
|---|---|
|Passive|Magical|

- BASIC ATTACK STACKS: 4
- DAMAGE PER STACK: 1
- %MOVE SPEED SLOW PER STACK: -1
- MAX STACKS: 15
- DURATION: 5
## Talents
| | Talents | |
| :---: | :---: | :---: |
| +3 Ice Mirror Max HP | 25 | Ice Mirrors deal +12% of your Attack Damage |
| --2s Crippling Senbon Cooldown | 20 | 1% Heal Reduction per Endless Wounds Stack |
| Crystal Ice Mirrors Leashes | 15 | +100 Attack Range |
| +12 Agility | 10 | -1 Demonic Speed Cooldown |
