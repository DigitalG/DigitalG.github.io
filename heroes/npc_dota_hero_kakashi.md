# Kakashi
## Stats
- STR: 21 + 2.0
- AGI: 21 + 2.0
- INT: 21 + 2.0
- Attack Rate: 1.7
- Attack Range: 128 (Melee)
- Attack Damage: 10 - 14
- Armor: 2
- Health: 200 + 0.3
- Mana: 75 + 0.9
- Vision: 1800 | 800
## Abilities
### <b><font color='#85baff'>Raikiri</font></b>
After a short cast time, Kakashi <b><font color='#85baff'>charges a target enemy.</font></b> <br><br> Upon reaching the target, Raikiri deals <b><font color='#85baff'>Magic Damage</font></b> and <b><font color='#85baff'>Stuns</font></b> the enemy unit.
|Behaviour|Damage Type|Target Team|Target Unit|
|---|---|---|---|
|Unit Target|Magical|Enemies|Heroes/Basic|

- CAST TIME:0.8
- DAMAGE:80/160/240/320
- STUN DURATION:0.9/1.1/1.3/1.5
### <b><font color='#ff0000'>Sharingan</font></b>
Allows Kakashi to <b><font color='#ff0000'>copy the last non-Ultimate spell</font></b> from an enemy hero. <br><br> The stolen spell can be used for a short period of time and will possess the <b><font color='#ff0000'>same level as Sharingan.</font></b>
|Behaviour|Target Team|Target Unit|
|---|---|---|
|Unit Target|Enemies|Heroes|

- DURATION:60
- STOLEN SPELL BONUS CAST RANGE:0 ([Scepter] 200.0)
- %STOLEN SPELL DAMAGE AMP:0 ([Scepter] 25.0)
### <b><font color='#A5E3FF'>Lightning Clone</font></b>
While active, <b><font color='#A5E3FF'>negates the next source of damage</font></b> dealt by a hero. <br><br> If triggered, Kakashi receives a <b>Basic Dispel</b> and <b><font color='#A5E3FF'>becomes invisible.</font></b> <br><br> Additionally, all enemies around Kakashi are <b><font color='#A5E3FF'>Rooted</font></b> and take <b><font color='#A5E3FF'>Magic Damage.</font></b>
|Behaviour|Damage Type|Target Team|Target Unit|
|---|---|---|---|
|No Target|Magical|Enemies|Heroes|

- DAMAGE:60/120/180/240
- TRIGGER WINDOW:2
- ROOT DURATION:0.8/1.2/1.6/2.0
- INVISIBILITY DURATION:2/3/4/5
### <b><font color='#ababab'>Copied Spell Slot</font></b>
Spells acquired with <b><font color='#ff0000'>Sharingan</font></b> will replace this slot.
|Behaviour|
|---|
|Passive|

### <b><font color='#9c7951'>Earth Release: Mud Wall</font></b>
<b><font color='#FFFFFF'>VECTOR TARGETTED</font></b> - <b><font color='#9c7951'>Creates a wall</font></b> of impassable terrain based on the drawn vector. <br><br> Enemies near the wall upon creation take <b><font color='#9c7951'>Magic Damage</font></b> and are <b><font color='#9c7951'>Stunned.</font></b>
|Behaviour|Damage Type|
|---|---|
|Point Target|Magical|

- WALL LENGTH:600
- DAMAGE:275
- STUN DURATION:1.2
- WALL DURATION:6
### <b><font color='#b30000'>Kamui</font></b>
<b><font color='#FFFFFF'>CHANNELED</font></b> - Inflicts a <b><font color='#b30000'>rapidly increasing Movement Speed Slow</font></b> on a target enemy while granting vision of them as long as they are within <b>Focus Range</b>. <br><br> If completed, the target is banished purging all buffs and <b><font color='#b30000'>removing them from the battlefield.</font></b> <br><br> Upon return, the target is <b><font color='#b30000'>dealt Pure Damage</font></b> based on their maximum health and is Revealed while applying Break.
|Behaviour|Damage Type|Target Team|Target Unit|
|---|---|---|---|
|Unit Target/Channeled|Pure|Enemies|Heroes|

- FOCUS RANGE:4000
- %MAX HEALTH AS DAMAGE:20/23/26
- BANISH DURATION:3
- BREAK DURATION:4/5/6
### <b><font color='#daf1f2'>Combat Experience</font></b>
Kakashi gains <b><font color='#daf1f2'>additional bonuses</font></b> for each <b><font color='#F7F7F7'>1</font></b> Attribute Point: <br><br> <b><font color='#e52406'>Strength</font></b> - <b><font color='#F7F7F7'>0.1% </font></b> <b>Status Resistance</b> <br><br> <b><font color='#0cc224'>Agility</font></b> - <b><font color='#F7F7F7'>%move_speed_per_agi%% </font></b> <b>Movement Speed</b> <br><br> <b><font color='#12b5de'>Intelligence</font></b> - <b><font color='#F7F7F7'>%spell_amp_per_int%% </font></b> <b>Spell Amplification</b> <br><br> Additionally, the attribute with the highest value grants <b><font color='#daf1f2'>double it's unique bonus.</font></b>
|Behaviour|
|---|
|Passive|

## Talents
| | Talents | |
| :---: | :---: | :---: |
| +15 All Stats | 25 | +320 Raikiri Damage |
| +60s Sharingan Copy Duration | 20 | +20% Critical Strike (1.5x) |
| -0.5s Raikiri Cast Time | 15 | +16% Evasion |
| +0.5s Lightning Clone Root | 10 | +3s Lightning Clone Invisiblity |
