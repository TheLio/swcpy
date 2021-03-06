---
title: Death Trooper (HeroDeathTrooper)
category: unit
---

# Death Trooper (HeroDeathTrooper)

You can read an [explanation  of the various unit stats](unitexplained.md).

## Main stats

### Unit stats

  * Armor type: infantry
  * Side: Empire
  * Buildable unit: Yes
  * Role: Destroyer
  * Shield cooldown: 0s
  * Shield health: 0
  * Shield range: 0
  * Unit capacity: 1
  * Type: hero

|Level |1    |2    |3    |4    |5    |6    |7    |8    |9    |10   |
|------|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
|Health|16000|17330|18660|20000|21330|22660|24000|25330|27330|30000|


|Level |11   |
|------|-----|
|Health|31602|


### Training stats

|Level        |1                                           |2                                      |3                                      |4                                      |5                                      |6                                      |7                                      |8                                      |9                                      |10                                      |
|-------------|--------------------------------------------|---------------------------------------|---------------------------------------|---------------------------------------|---------------------------------------|---------------------------------------|---------------------------------------|---------------------------------------|---------------------------------------|----------------------------------------|
|Training time|3m30s                                       |3m40s                                  |3m50s                                  |4m                                     |4m10s                                  |4m20s                                  |4m30s                                  |9m20s                                  |9m40s                                  |10m                                     |
|Training cost|1000$                                       |1400$                                  |1800$                                  |2200$                                  |2600$                                  |3000$                                  |3400$                                  |4000$                                  |4200$                                  |4600$                                   |
|Building     |[Hero Command 2](empireTacticalCommand.html)|[Research Lab 2](empireOffenseLab.html)|[Research Lab 3](empireOffenseLab.html)|[Research Lab 4](empireOffenseLab.html)|[Research Lab 5](empireOffenseLab.html)|[Research Lab 6](empireOffenseLab.html)|[Research Lab 7](empireOffenseLab.html)|[Research Lab 8](empireOffenseLab.html)|[Research Lab 9](empireOffenseLab.html)|[Research Lab 10](empireOffenseLab.html)|


|Level        |11                                      |
|-------------|----------------------------------------|
|Training time|10m20s                                  |
|Training cost|5000$                                   |
|Building     |[Research Lab 11](empireOffenseLab.html)|


### Upgrading stats

  * Upgrade time: 5s
  * Upgrade requirements: 32 data fragments

### Movement stats

  * Acceleration: 0
  * Crushes walls: No
  * Flying unit: No
  * Max speed: 20
  * Propensity to go around obstacles: 15
  * Rotation speed: 7.854
  * Run speed: 0
  * Run threshold: 0
  * Unit size on map: 1x1

## Main attack : HeroHanSolo

### Targeting

  * Attack shield border: No
  * Max attack range: 7
  * Min attack range: 0
  * New rotation speed: 7854
  * Target preference strength: 90
  * Target preferences: **Trap (80)**, **Turret (80)**, _Shield (60)_, _Shield generator (60)_, Droideka (50), Flying infantry (50), Flying vehicle (50), Headquarters (50), Heavy infantry (50), Heavy vehicle (50), Infantry (50), Light vehicle (50), Other building (50), Ressource generator (50), Storage (50), Support troop (50), Heavy infantry hero (1), Heavy vehicule hero (1), Infantry hero (1), Vehicule hero (1), Wall (1)
  * View range: 8

### Shooting

  * Animation delay: 0
  * Charge time: 50ms
  * Clip retargeting: No
  * Gun shooting sequence: 1
  * Impact delay: 250ms
  * Can shoot over walls: No
  * Reload time: 1s
  * Retargeting offset: 14
  * Self-centered targeting: No
  * Shot count: 2
  * Shot delay: 400ms
  * Target locking: No

|Level          |1   |2   |3   |4   |5   |6   |7   |8   |9   |10  |
|---------------|----|----|----|----|----|----|----|----|----|----|
|Damage per shot|2630|2810|3040|3320|3590|3830|4010|4190|4520|4980|


|Level          |11  |
|---------------|----|
|Damage per shot|5256|


### Projectile

|Level                       |1   |2   |3   |4   |5   |6   |7   |8   |9   |10  |
|----------------------------|----|----|----|----|----|----|----|----|----|----|
|Displayed damage per second |2840|3040|3290|3590|3880|4140|4340|4530|4890|5380|
|Calculated damage per second|3627|3875|4193|4579|4951|5282|5531|5779|6234|6868|
|Calculated damage per cycle |5260|5620|6080|6640|7180|7660|8020|8380|9040|9960|


|Level                       |11   |
|----------------------------|-----|
|Displayed damage per second |5680 |
|Calculated damage per second|7249 |
|Calculated damage per cycle |10512|


  * Cannons per sequence: 1
  * Shooting cycle duration: 1.450s
  * Directional: Yes
  * Is deflectable: Yes
  * Max speed: 18
  * Damage multipliers: **(400)**: Shield, Shield generator, **(200)**: Trap, **(100)**: Droideka, Flying infantry, Flying vehicle, Headquarters, Heavy infantry, Heavy infantry hero, Heavy vehicle, Heavy vehicule hero, Infantry, Infantry hero, Light vehicle, Other building, Ressource generator, Storage, Support troop, Turret, Vehicule hero, **(80)**: Wall
  * Pass through shield: No
  * Salvos: 2

## Internal stats

These stats internal to the system link different parts of data together.

  * Unit ID: HeroDeathTrooper
  * Upgrade shard uid: shrd_troopHeroDeathTrooper

|Level    |1    |2    |3    |4    |5    |6    |7    |8    |9    |10-11 |
|---------|-----|-----|-----|-----|-----|-----|-----|-----|-----|------|
|Hero data|hero1|hero2|hero3|hero4|hero5|hero6|hero7|hero8|hero9|hero10|


## Presentation stats

These are all sorts of user interface settings, that should not interfere with gameplay.

  * Arcs: No
  * Asset name: deathtrooper_emp-ani
  * Audio attack: "sfx_attack_hero_deathtrooper_01":33,"sfx_attack_hero_deathtrooper_02":33,"sfx_attack_hero_deathtrooper_03":33
  * Audio death: "sfx_death_hero_deathtrooper_01":50,"sfx_death_hero_deathtrooper_02":50
  * Audio placement: "sfx_placement_hero_deathtrooper_01":33,"sfx_placement_hero_deathtrooper_02":33,"sfx_placement_hero_deathtrooper_03":34
  * Audio train: "sfx_ui_unitcomplete_deathtrooper_01":50,"sfx_ui_unitcomplete_deathtrooper_02":50
  * Bullet: fx_blaster_beam_r_med
  * Bundle name: deathtrooper_emp-ani
  * Decal asset name: tac_hero_emp
  * Decal bundle name: tac_hero_emp
  * Decal size: 160
  * Event button action: galaxy
  * Event button data: planet1 planet3 planet6 planet8 planet21 planet23
  * Event button string: hn_open_galaxy
  * Event features string: fragment_obtain_gen
  * Factory rotation: 0
  * Factory scale factor: 1
  * Favorite target type: turret
  * Gun position: soldier_rbl_rig_MASTER_MOVER/soldier_rbl_rig_locator_gun:1
  * Hit spark: fx_blaster_hit_r_med
  * Hologram uid: HeroHologramDeathtrooper
  * Icon camera position: 6.12,13,15.36
  * Icon closeup camera position: 3.94,6.77,11.83
  * Icon closeup lookat position: -0.34,2.08,-1.07
  * Icon lookat position: -0.34,1.19,-0.78
  * Max scale: 100
  * Muzzle flash: fx_blaster_flash_r_med
  * Name: HeroHanSolo
  * Spin speed: 0
  * Targeted type: ENEMIES
  * Unlocked by event: true

|Level                      |1          |2          |3          |4          |5          |6          |7          |8          |9          |10         |
|---------------------------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|
|Deploy vfx                 |(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|
|Displayed damage per second|2840       |3040       |3290       |3590       |3880       |4140       |4340       |4530       |4890       |5380       |
|Icon unlock scale          |1.2,1.2,1.2|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|
|Prestige                   |(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|


|Level                      |11                           |
|---------------------------|-----------------------------|
|Deploy vfx                 |vfx_prestige_deploy_small_emp|
|Displayed damage per second|5680                         |
|Icon unlock scale          |(not found)                  |
|Prestige                   |true                         |


## Uninterpreted stats

Seriously, we don't really know what to do with these.

  * Arming delay: 0
  * Auto spawn rate scale: 1
  * Auto spawn spreading scale: 1
  * Max scale: No
  * Seeks target: Yes
  * Splash: 0
  * Streams: no
  * Strict cool down: No
  * Target in range modifier: 1
  * Xp: 0

|Level      |1  |2  |3  |4  |5  |6  |7  |8  |9  |10 |
|-----------|---|---|---|---|---|---|---|---|---|---|
|Order      |701|702|703|704|705|706|707|708|709|710|
|Point value|20 |24 |28 |32 |36 |40 |44 |48 |52 |60 |


|Level      |11 |
|-----------|---|
|Order      |711|
|Point value|60 |


