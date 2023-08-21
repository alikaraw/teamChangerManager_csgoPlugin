# Team Changer Manager | CS:GO Plugin
The plugin helps you manage the change team function in the game. Originally posted [here](https://forums.alliedmods.net/showthread.php?t=317424).

## Features 
* Disable the join message for each team separately
* Disable the ability to join each team separately 
* Add cooldown to team changing

## ConVars
|Name| Description|
|---------|--------|
|tjm_t_disable| Disable the ability to join the T team|
|tjm_ct_disable| Disable the ability to join the CT team|
|tjm_spec_disable| Disable the ability to join the Spectators team|
|tjm_t_message| Disable the message when joining the T team|
|tjm_ct_message| Disable the message when joining the CT team|
|tjm_spec_message| Disable the message when joining the Spectatos team|
|tjm_cooldown| Set the cooldown between the team switches, when set to -1 you can't change a team once your in one|

## Commands
|Name|Description|Flag|
|----|----|----|
|sm_tjm| Shows a menu with all the convars and the values of them|  ```CONVARS``` |

## Config
Config file is found in ```cfg\sourcemod\Team Join Manager.cfg```
