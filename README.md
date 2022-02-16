# DSJ24 Cup Planner
## _The First Discord supported DSJ2 tournament_

DSJ24 Cup Planner is the first tournament for mobile versions of legendary DSJ2 game! 

Join DSJ24.pl Discord now and play against other DSJ2 players!

## Features

- simple replay sending mechanism
- fully-automated verification system
- scoreboard right after tournament finish
- tournament schedulling via Discord command


## User Manual

DSJ24 Cup Planner is user-friendly system, where the only thing you have to do is just sharing your DSJ2 replay to current channel. The rest is in our charge.

- Your DSJ2 replay has to be in format: https://replay.dsj2.com/ <unique replay's ID>
![](https://i.imgur.com/Nn0x4mk.png)
- Jump in World Cup mode only
- if scheduled tournament has Code, you have to put it in player's name
![](https://i.imgur.com/F2ro3Cv.png)
![](https://i.imgur.com/F5TbsZi.png)

## Administrator commands
As Discord Administrator use following commands to setup tournament
1. `!schedule [hill name] [finish hour] [unique code]`
 - Creates tournament (eg. `!schedule Finland K105 23:59 dsj`)
 - If you don't want use unique code, set it to 'none': `!schedule Finland K105 23:59 none`
 - Unique code has to be max. 3 letters long
 - Available hill names are listed below
2. `!unschedule [finish hour]`
 - Removes tournament (eg. `!unschedule 23:59`)
3. `!getReport [finish date]`
 - Displays results from specific date (eg. `!getReport 2022-02-16 19:55`) 
4. `!setup`
 - Adjusts database schemas 

## Available hill's names
`Finland K105`

`Switzerland K170`

`Czech Republic K135`

`Belarus K220`

`Austria K70`

`USA K130`

`Latvia K165`

`Poland K80`

`Japan K210`

`Belgium K95`

`Iceland K190`

`England K50`

`Germany K120`

`Estonia K155`

`Norway K90`

`Australia K240`

`Ireland K125`

`Ukraine K60`

`Hungary K180`

`Sweden K140`

`Italy K230`

`Denmark K75`

`Slovakia K110`

`Canada K185`

`Lithuania K145`

`Kazakhstan K85`

`China K205`

`France K160`

`Holland K100`

`Russia K200`

`Korea K150`

`Slovenia K250`

## Changelog
##### DSJ24CP v1.1.0 - 10.02.2022
- Added command for generating results from given time period
 
##### DSJ24CP v1.0.1 - 12.02.2022
- Preparing scoreboard more flexible for discord's chat message system

##### DSJ24CP v1.0.0 - 10.02.2022
- Generating tournaments
- Sending DSJ2 replays
- Replays validation
- Removing tournaments
- Preparing reports in database and truncating it after tournament's finish
- Discord commands
- Discord Bot responses
- Generating Discord Notification with tournament's country flag and DSJ2 screenshot into thumbnail
- minor addons
- Documentation prepared

DSJ24 Cup Planner © fyv, Mensix for DSJ24, 2022

thx wa_, Arumasze for contribution and testing 
