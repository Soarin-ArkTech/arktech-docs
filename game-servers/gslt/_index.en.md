+++
title = "Setting the Game Server Login Token"
date =  2021-03-24T22:10:47-04:00
weight = 101
+++

## Game Server Login Token (GSLT)
Within the Commandline Manager is a field for a Game Server Login Token, also known as a GSLT. This token authenticates your game server with Steam upon startup. 

### Creating the token
1. Visit https://steamcommunity.com/dev/managegameservers.
2. Log into Steam.
3. Fill in the AppID of the game your server is running. 
    - Garry's Mod - 4000
    - Team Fortress 2 - 440
    - CS:GO - 730 
4. Set the memo to anything you want, however the server name will do just fine.
5. Create!

### Adding the token to your server
1. Log into the [game panel](https://arktech.host/). 
2. tbd

### Important notice for Garry's Mod server owners:
It is highly recommended to fill in the GSLT field with a valid token, as your server ranking will be significantly dropped if you do not.

Find more information about the GSLT as it pertains to Garry's Mod on the Facepunch Wiki: https://wiki.facepunch.com/gmod/Steam_Game_Server_Accounts

{{% notice note %}}
A Game Server Login Token that goes unused for an extended period of time will expire, but may be regenerated.
{{% /notice %}}

#
![Banner](/images/fishy.gif)