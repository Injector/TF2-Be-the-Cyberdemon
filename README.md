# [TF2] (Doom) Be the Cyberdemon from Doom

Allows admins to play as Cyberdemon from the Doom 1993

## Commands:

`sm_cyberdemon` - Admin flag: Ban - Turn yourself into the Cyberdemon

`sm_cyberdemon <target>` - Uses sm_cyberdemon_others override access to turn target into the Cyberdemon


## Overrides:

`sm_cyberdemon_others` - Admin flag: Cheats - Who can target it on other players.

## ConVars:

`sm_cyberdemon_version` - Plugin version

`sm_cyberdemon_no_dominations` 0 - Allow cyberdemon to dominate on players? 0 - Allow, 1 - Allow, but clear on cyberdemon death, 2 - Disallow

`sm_cyberdemon_melee_push` 1 - Push away victims after cyberdemon's punch? 0 - No, 1 - Yes

`sm_cyberdemon_default_rocket` 0 - Use default 3D soldier rocket instead of sprites? 0 - No, 1 - Yes

`sm_cyberdemon_max_cyberdemons` 8 - Max cyberdemons to have to avoid edict overflow: 0 - No limit

`sm_cyberdemon_no_heal` 0 - Disallow medics to heal cyberdemon? 0 - Allow, 1 - Disallow


## Showcase video: 
Maybe later

## Showcase screenshots: 
[imgur](https://imgur.com/a/gmAUq80)

## Statistics:

Cyberdemon rocket speed: 1500 hammer units

Cyberdemon rocket damage: 180

Health: 4000

Melee attack damage: 97.5 + optional push velocity 500 hammer units

Rocket shoot cooldown 0.65 seconds


If victim's health above 700 (assuming victim is a boss), then Cyberdemon's damage will raise to (victim health + 5) instead of 180


## Controls:

Right Mouse - Shoot the rocket

Aim on enemy - Play Cyberdemon's roar


## Features:

* Fully 8 directional sprites, depends on cyberdemon angle and player angle (individual per player)
* * For example: if player 1 behind cyberdemon's spine, he will see back sprite. If player 2 in front of cyberdemon, he will see front sprite
* Cyberdemon shoot 8 directional sprite rocket from Doom instead of regular soldier rocket
* Sounds from Doom (Walk, roar, attack)
* Pyros and heavies with deflector can't deflect cyberdemon's rockets
* Engineers with short curcuit can't destroy cyberdemon's rockets
* Like in the Doom, Cyberdemon is immune to blast damage from rockets, only direct rocket hit damages him
* Cyberdemon is impossible to stun with uber saw, gunslinger, etc
* Heavies with equipped Holiday punch, can't force Cyberdemon to laugh (lack of humor)
* Option to disable dominations on victims, or disable dominations on victims after cyberdemon death

## Requirements:

* FastDL server for assets
* TF2Attributes

## Installation:

* Install TF2Attributes
* Place .smx file in sourcemod/plugins/. Don't click on "Get Plugin"
* Place tf2.cyberdemon.txt in sourcemod/gamedata/
* Upload assets (materials, sound) to your FastDL web server
* Load the plugin via sm plugins load bethecyberdemon

## TODO List:

* Explosion effect from Doom?
* Update sprites resolution 64x128 to 256x256 or even higher
* Doom 64 sprites
* Musical boss theme
* monster_resource health bar to display current Cyberdemon's health
* Tyrant version of Cyberdemon (mini-cyberdemon from Legacy of Rust)

## Credits:

caxanga334 - CTFPlayer::CanBeForcedToLaugh signature 
