---
title: AT-AP Walker (ATAP)
category: unit
---

# AT-AP Walker (ATAP)

You can read an [explanation  of the various unit stats](unitexplained.md).

## Main stats

### Unit stats

  * Armor type: vehicle
  * Side: Rebellion
  * Buildable unit: Yes
  * Role: Destroyer
  * Shield cooldown: 0s
  * Shield health: 0
  * Shield range: 0
  * Unit capacity: 10
  * Type: vehicle

|Level |1   |2   |3   |4   |5   |6   |7    |8    |9    |10   |
|------|----|----|----|----|----|----|-----|-----|-----|-----|
|Health|7200|7610|8050|8510|9000|9530|10090|10680|11320|12000|


|Level |11   |
|------|-----|
|Health|12408|


### Training stats

|Level        |1                             |2                                     |3                                     |4                                     |5                                     |6                                     |7                                     |8                                     |9                                     |10                                     |
|-------------|------------------------------|--------------------------------------|--------------------------------------|--------------------------------------|--------------------------------------|--------------------------------------|--------------------------------------|--------------------------------------|--------------------------------------|---------------------------------------|
|Training time|4m                            |4m2s                                  |4m4s                                  |4m7s                                  |4m10s                                 |4m20s                                 |4m30s                                 |4m40s                                 |4m50s                                 |5m                                     |
|Training cost|1100$                         |1150$                                 |1200$                                 |1250$                                 |1300$                                 |1500$                                 |1700$                                 |2000$                                 |2100$                                 |2300$                                  |
|Building     |[Factory 4](rebelFactory.html)|[Research Lab 2](rebelOffenseLab.html)|[Research Lab 3](rebelOffenseLab.html)|[Research Lab 4](rebelOffenseLab.html)|[Research Lab 5](rebelOffenseLab.html)|[Research Lab 6](rebelOffenseLab.html)|[Research Lab 7](rebelOffenseLab.html)|[Research Lab 8](rebelOffenseLab.html)|[Research Lab 9](rebelOffenseLab.html)|[Research Lab 10](rebelOffenseLab.html)|


|Level        |11                                     |
|-------------|---------------------------------------|
|Training time|5m10s                                  |
|Training cost|2500$                                  |
|Building     |[Research Lab 11](rebelOffenseLab.html)|


### Upgrading stats

|Level               |1    |2    |3    |4     |5     |6      |7      |8      |9       |10      |
|--------------------|-----|-----|-----|------|------|-------|-------|-------|--------|--------|
|Upgrade time        |0s   |1h   |2h30m|7h    |20h   |2d12h  |4d     |6d     |1w1d    |1w5d    |
|Upgrade requirements|6500$|3000$|6000$|15000$|35000$|115000$|200000$|385000$|1250000$|2250000$|


|Level               |11      |
|--------------------|--------|
|Upgrade time        |2w      |
|Upgrade requirements|4250000$|


### Movement stats

  * Acceleration: 0
  * Crushes walls: No
  * Flying unit: No
  * Max speed: 20
  * Propensity to go around obstacles: 15
  * Rotation speed: 3.927
  * Run speed: 0
  * Run threshold: 0
  * Unit size on map: 2x1

## Main attack : ATAP

### Targeting

  * Attack shield border: Yes
  * Max attack range: 8
  * Min attack range: 0
  * New rotation speed: 3927
  * Target preference strength: 90
  * Target preferences: **Shield (70)**, **Shield generator (70)**, Droideka (50), Flying infantry (50), Flying vehicle (50), Headquarters (50), Heavy infantry (50), Heavy vehicle (50), Infantry (50), Light vehicle (50), Other building (50), Ressource generator (50), Storage (50), Support troop (50), Turret (50), Heavy infantry hero (1), Heavy vehicule hero (1), Infantry hero (1), Vehicule hero (1), Wall (1), Trap (0)
  * View range: 8

### Shooting

  * Animation delay: 0
  * Charge time: 250ms
  * Clip retargeting: No
  * Gun shooting sequence: 1,2
  * Impact delay: 1s
  * Can shoot over walls: No
  * Reload time: 2s
  * Retargeting offset: 16
  * Self-centered targeting: No
  * Shot count: 4
  * Shot delay: 200ms
  * Target locking: No

|Level          |1   |2   |3   |4   |5   |6   |7   |8   |9   |10  |
|---------------|----|----|----|----|----|----|----|----|----|----|
|Damage per shot|1540|1630|1720|1820|1920|2040|2160|2280|2420|2570|


|Level          |11  |
|---------------|----|
|Damage per shot|2660|


### Projectile

|Level                       |1   |2   |3   |4   |5   |6   |7   |8   |9   |10   |
|----------------------------|----|----|----|----|----|----|----|----|----|-----|
|Displayed damage per second |2160|2290|2410|2550|2690|2860|3030|3200|3400|3610 |
|Calculated damage per second|2161|2287|2414|2554|2694|2863|3031|3200|3396|3607 |
|Calculated damage per cycle |6160|6520|6880|7280|7680|8160|8640|9120|9680|10280|


|Level                       |11   |
|----------------------------|-----|
|Displayed damage per second |3736 |
|Calculated damage per second|3733 |
|Calculated damage per cycle |10640|


  * Cannons per sequence: 2
  * Shooting cycle duration: 2.850s
  * Directional: Yes
  * Is deflectable: Yes
  * Max speed: 12
  * Damage multipliers: **(400)**: Shield, Shield generator, **(200)**: Heavy infantry hero, Heavy vehicule hero, **(100)**: Droideka, Flying infantry, Flying vehicle, Heavy infantry, Heavy vehicle, Infantry, Infantry hero, Light vehicle, Support troop, Vehicule hero, **(75)**: Headquarters, Other building, Ressource generator, Storage, Trap, Turret, **(60)**: Wall
  * Pass through shield: No
  * Salvos: 4

## Internal stats

These stats internal to the system link different parts of data together.

  * Unit ID: ATAP

## Presentation stats

These are all sorts of user interface settings, that should not interfere with gameplay.

  * Arcs: No
  * Asset name: atap_rbl-ani
  * Audio attack: "sfx_attack_rebel_atap_1":30,"sfx_attack_rebel_atap_2":35,"sfx_attack_rebel_atap_3":35
  * Audio death: "sfx_death_rebel_atap_1":100
  * Audio placement: "sfx_placement_walker_1":50,"sfx_placement_walker_2":50
  * Buff asset offset: 0.00,1.94,0.00
  * Bullet: fx_blaster_beam_b_sm
  * Bundle name: atap_rbl-ani
  * Factory rotation: 0
  * Factory scale factor: 0.85199999999999997957189634689711965620517730712890625
  * Favorite target type: shieldGenerator
  * Gun position: "atap_rbl_rig_locator_gun1":1,"atap_rbl_rig_locator_gun2":2
  * Hit spark: fx_blaster_hit_b_sm
  * Icon camera position: 20.98,26.07,34.08
  * Icon lookat position: -0.59,2.38,-0.99
  * Max scale: 100
  * Muzzle flash: fx_blaster_flash_b_sm
  * Name: ATAP
  * Spin speed: 0
  * Targeted type: ENEMIES

|Level                      |1          |2          |3          |4          |5          |6          |7          |8          |9          |10         |
|---------------------------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|
|Deploy vfx                 |(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|
|Displayed damage per second|2160       |2290       |2410       |2550       |2690       |2860       |3030       |3200       |3400       |3610       |
|Prestige                   |(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|


|Level                      |11                           |
|---------------------------|-----------------------------|
|Deploy vfx                 |vfx_prestige_deploy_large_reb|
|Displayed damage per second|3736                         |
|Prestige                   |true                         |


## Uninterpreted stats

Seriously, we don't really know what to do with these.

  * Arming delay: 0
  * Auto spawn rate scale: 2
  * Auto spawn spreading scale: 2
  * Max scale: No
  * Seeks target: Yes
  * Splash: 0
  * Streams: no
  * Strict cool down: No
  * Target in range modifier: 1
  * Xp: 0

|Level      |1     |2     |3     |4     |5     |6     |7     |8     |9     |10    |
|-----------|------|------|------|------|------|------|------|------|------|------|
|Order      |280401|280402|280403|280404|280405|280406|280407|280408|280409|280410|
|Point value|10    |12    |14    |16    |18    |20    |22    |24    |26    |30    |


|Level      |11    |
|-----------|------|
|Order      |280411|
|Point value|30    |


