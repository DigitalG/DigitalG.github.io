# Madara
## Stats
- STR: 22 + 2.8
- AGI: 15 + 1.6
- INT: 23 + 3.1
- Attack Rate: 1.700000
- Attack Range: 128 (Melee)
- Attack Damage: 10 - 16
- Armor: 3.000000
- Health: 200 + 0.300000
- Mana: 75 + -0.1
- Vision: 1800 | 800
## Abilities
### <b><font color='#EA2D07'>Great Fire Annihilation</font></b>
<b><font color='#EA2D07'>Sends out a wave of fire</font></b> towards the target point dealing <b>Magic Damage</b> and dragging all enemies along with it. <br><br> Upon reaching maximum distance, the fire wave will <b><font color='#EA2D07'>explode dealing Magic Damage and Stunning</font></b> all enemies within the area. <br><br> Any trees touched by this ability will burn if <b><font color='#23A32C'>Deep Forest Emergence</font></b> is leveled.
|Behaviour|Damage Type|
|---|---|
|Directional/Point Target|Magical|

- RANGE: 625
- WAVE DAMAGE: 70/95/120/145
- EXPLOSION DAMAGE: 90/105/140/165 ([Talent] 250.0/265.0/300.0/325.0)
- STUN DURATION: 0.9/1.1/1.3/1.5
### <b><font color='#23A32C'>Deep Forest Emergence</font></b>
<b><font color='#FFFFFF'>ACTIVE</font></b> - <b><font color='#23A32C'>Creates a ring of trees</font></b> that circle a target area for a short period time. <br><br><b><font color='#FFFFFF'>PASSIVE </font></b>- Trees affected by Madara's other abilities are <b><font color='#EA2D07'>set on fire dealing Magic Damage</font></b> and reducing the <b>Movement Speed</b> of nearby enemies.
|Behaviour|Damage Type|
|---|---|
|Point Target|Magical|

- BURN DAMAGE: 20/30/40/50
- %BURN MOVEMENT SPEED SLOW: -20/-23/-26/-29
- BURN DEBUFF DURATION: 2.0/2.5/3.0/3.5
- TREE DURATION: 3/3.5/4/4.5
- CD REDUCTION (TALENT): 0/0/0/0
### <b><font color='#3D79E5'>Susano'o</font></b>
<b><font color='#FFFFFF'>TOGGLE</font></b> - While active, Madara deals <b><font color='#3D79E5'>Magic Damage to nearby enemies</font></b> while draining his Mana. <br><br> Madara also gains <b><font color='#3D79E5'>increased Magic Resistance</font></b> while active. <br><br> While toggled on, any trees within radius of Madara will burn if <b><font color='#23A32C'>Deep Forest Emergence</font></b> is leveled.
|Behaviour|Damage Type|
|---|---|
|Toggle|Magical|

- RADIUS: 250 ([Talent] 320.0)
- DAMAGE: 35/50/65/80 ([Talent] 105.0/120.0/135.0/150.0)
- %BONUS MAGIC RESISTANCE: 8/12/16/20
- %MAX MANA PER SECOND: 2
- %ENEMY MAX HP AS DAMAGE:10
- BONUS ATTACK RANGE:125
- %ATTACK SPEED LOSS:40
### <b><font color='#1A50AF'>Susanoo: Earth Shatter</font></b>
<b><font color='#ffffff'>VECTOR TARGETTED</font></b> - Madara's Perfect Susano'o unleashes a devastating slash, dealing <b><font color='#1A50AF'>Magic Damage based on Maximum HP</font></b> to any enemy Heroes in the sword's path.<br><br>Instantly kills any creeps affected by this ability.<br><br><i>Only available while <b><font color='#4085ff'>Susano'o</font></b> is active.</i>
|Behaviour|Damage Type|
|---|---|
|Point Target|Magical|

- %MAX HEALTH DAMAGE30
- SLASH WIDTH:150
- SLASH LENGTH:1200
### <b><font color='#E55C02'>Heaven Concealed</font></b>
<b><font color='#E55C02'>Summons a gigantic meteor</font></b> after a short delay that will crash onto a target area dealing <b><font color='#EA2D07'>massive Magic Damage and a Stun</font></b> to all enemies within the area. <br><br> Any trees caught in the explosion will burn if <b><font color='#23A32C'>Deep Forest Emergence</font></b> is leveled.
|Behaviour|Damage Type|Target Team|Target Unit|
|---|---|---|---|
|Point Target/Channeled|Magical|Enemies|Heroes/Basic|

- RADIUS: 400
- DAMAGE: 425/650/875
- STUN DURATION: 1.8/2.1/2.4
### <b><font color='#ffdbac'>Hashirama Cells</font></b>
Madara gains temporary Stacks <b><font color='#F7F7F7'>(+0.25s)</font></b> whenever <b><font color='#ffdbac'>damage is taken</font></b> up to a <b>Maximum Stack Limit.</b> <b><font color='#F7F7F7'>(+1)</font></b> <br><br> Each stack grants increased <b><font color='#ffdbac'>Health Regeneration</font></b> <b><font color='#F7F7F7'>(+0.02)</font></b> and <b><font color='#ffdbac'>Spell Damage Amplification.</font></b>
|Behaviour|Damage Type|
|---|---|
|Passive|Magical|

- MAX STACKS:5
- HEALTH REGEN PER STACK:0.5
- %SPELL AMP PER STACK:1.0
- STACK DURATION:7.0
## Talents
| | Talents | |
| :---: | :---: | :---: |
| +-25% Deep Forest Tree Burn Slow | 25 | +70 Susano’o Damage |
| +160 Damage Fire Annihilation Explosion | 20 | +0.5 Hashirama Cells Health Regen per Stack |
| +12% Spell Amplification | 15 | +2.0 Forest Emergence Duration |
| +70 Susano’o Radius | 10 | +12 Intelligence |
