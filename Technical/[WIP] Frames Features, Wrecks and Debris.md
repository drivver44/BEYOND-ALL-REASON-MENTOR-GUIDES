# Nanoframes, Features, Wrecks and debris
<sup><sup>(Author: Rippsy)</sup></sup>

## Nanoframes
Nanoframes are the in progress part of building before a unit is completed, they have specific behaviours with regards to resources and income
* Do not decay while they are being built or reclaimed
* Start to decay after 9 seconds of no worker activity (build or reclaim)
* Give metal back per second while they decay
* When being reclaimed by a unit, what removes the final HP determines determins if you get the metal or not
  * Last HP by reclaim - you get 100% of the metal
  * Last HP by dmg - you lose all metal remaining in it
* Partially damaged nanoframes which then decay will not return all the metal which remains in them before they fade
* Features (Wrecks, Debris, Trees, Rocks etc) all give resources per second during reclaim

## Wrecks & Debris
Based on units max hp and dmg caused across recent ticks with a [RecentDamage=RecentDamage\*0.9](https://github.com/beyond-all-reason/spring/blob/1d05355add2cf38a035fd7da0835da93eb61d221/rts/Sim/Units/Unit.cpp#L664) decay

Breakpoints can be found defined in [unit bos](https://github.com/beyond-all-reason/Beyond-All-Reason/blob/83166b4b0e34fd368f311f07da00e13bcb158c9c/scripts/Units/armah.bos#L199) files
* <=25 Wreck
* <=50 Debris
* <=99 Nothing

### Example 1
A Thug is shot at by other Thugs, over 15 gameticks, its hit with 8 Thug shots at tick 2, then 3 more at tick 15 - killing it. When it dies the RecentDamage value is checked vs the units maximum HP, in this case, it above 25%, below 50% and leaves only debris
![Example 1](https://github.com/user-attachments/assets/509b6e8a-9ce7-4e7e-a1b2-073c84c77135)

### Example 2
A Thug is shot 9 times on gametick 1, then not damaged again until gametick 18, where it takes 1 more hit, and dies.
![Example 2](https://github.com/user-attachments/assets/45c3e155-d4f7-4a4f-839c-84315a28d957)

### Metal values
* Wrecks = 60% of unit metal cost
* Debris = 25% of unit metal cost

## Exceptions
* Cortex T2 bot Fiend never leaves a wreck but its debris is worth 60%
* Cortex T2 bot Commando never leaves a wreck or debis
* Commanders always leave a wreck
* Decoy Commanders never any wreck or debris (explode into confetti)

