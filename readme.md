![SCOPE Logo Splash](https://alexonyourscreen.com/app/img/scope_logo.png)

![](https://alexonyourscreen.com/app/img/scope_space.png)

The SCOPE CS:GO Observer System has been designed from the ground up to give any individual the tools to observe with the modern standards of todays E-sports world. Major TOs such as ESL, PGL, and Blast not only have multiple observers for their events; but also have software that modifies the game itself, as well as custom designed HUDs that directly sync in with their overall broadcast package.

The typical observer at a local LAN or online event will not have access to these vast resources, so SCOPE tries to bring as much of that production value to the vanilla game as possible. One person is now able to switch between first person player views and overhead shots of the map on the fly, and easily trigger cinematic flyover cameras around the map for when the action on the server comes to a pause.

All of these camera views are grouped in an intuitive way that is identical across the entire map pool, so once you know one map, you know them all. Installation (and uninstallation) is simple, and executing the config only requires a single command.

Thanks for looking through the SCOPE, happy observing!

![](https://alexonyourscreen.com/app/img/scope_space.png)

## Installation

Extract the **_contents_** of the downloaded .zip into `[game_install_dir] /csgo/cfg`.

After extracting, copy the **_contents_** of `[game_install_dir] /csgo/cfg/cameras` and paste into `[game_install_dir] /csgo/maps`. Be sure to replace existing files.

To uninstall, remove `aoys_scope.cfg` and the `/aoys_scope` folder within `[game_install_dir] /csgo/cfg`, and verify the game installation within Steam.

![](https://alexonyourscreen.com/app/img/scope_space.png)

## Important Notice

Ensure the following bind is in your **autoexec.cfg**:

    bind "`" "toggleconsole";
    
IF THIS LINE IS NOT INCLUDED YOU CAN LOSE ACCESS TO THE CS:GO CONSOLE.

It is highly recommended to set **ALL** of your in-game keybinds and settings in your **autoexec.cfg**.

![](https://alexonyourscreen.com/app/img/scope_space.png)

## Getting Started

After loading into the game server or demo you are going to be observing, open the console and enter the following command using the common name of the map you are on, for example:

    exec aoys_scope/inferno

![](https://alexonyourscreen.com/app/img/scope_space.png)

## Supported Maps

All of the official competitive maps are included, with 40+ camera presets on each.

`Ancient` `Anubis` `Cache` `Dust2` `Inferno` `Mirage` `Nuke` `Overpass` `Train` `Vertigo`

![](https://alexonyourscreen.com/app/img/scope_space.png)

## Return To Gameplay

To remove all of the configuration changes made by SCOPE and return to your personal **autoexec.cfg** configuration, enter this command in the console:

    exec aoys_scope/exit

![](https://alexonyourscreen.com/app/img/scope_space.png)

## Notes

This system is designed to require no additional configuration beyond the initial installation, and be a fully 'in-the-box' solution for observing CS:GO. As long as you have a fully configured **autoexec.cfg** with all of your personal settings, switching in and out of SCOPE should be as s1mple as entering the commands listed above.

Feel free to drop by my stream on Twitch any time you see me live if you have any questions, or just want to say hello!

> <https://twitch.tv/ALEXonyourscreen>

![](https://alexonyourscreen.com/app/img/scope_space.png)

## Toggles

There are a few toggle keybinds set by SCOPE that are not shown the the console reference in game. Most importantly the command to open the console has moved to the **backslash** key to prevent accidentally opening the console during a broadcast.

![](https://alexonyourscreen.com/app/img/scope_space.png)

> ` \ `  - Open Console

![](https://alexonyourscreen.com/app/img/scope_space.png)

> ` Z `  - Switch to Free Cam
> 
> ` X `  - Toggle X-ray Mode
> 
> ` C `  - Crosshair Display (static/player)
> 
> ` V `  - Grenade Cam (hold)

![](https://alexonyourscreen.com/app/img/scope_space.png)

> ` H `  - Toggle HUD  

![](https://alexonyourscreen.com/app/img/scope_space.png)

## Player Cams

The number keys are assigned to each player in the game's **Player Cam**, and the row underneath is for assigning those players to their respective team's **Star Player** slot. The **Star Player** slot is designed as a failsafe type of situation, where if things are heating up in game and you dont know how to best show the action, you always know you have a key assigned to the one player that has been lighting up the server since pistol round. For example, to assign *Player 3* from *Team 2* to the **Star Player** slot, press ` I `.

![](https://alexonyourscreen.com/app/img/scope_space.png)

> `` ` `` - T1 Star Player
>
> ` 1 ` - T1 Player 1 / Assign - ` Q `
> 
> ` 2 ` - T1 Player 2 / Assign - ` W `
> 
> ` 3 ` - T1 Player 3 / Assign - ` E `
> 
> ` 4 ` - T1 Player 4 / Assign - ` R `
> 
> ` 5 ` - T1 Player 5 / Assign - ` T `

![](https://alexonyourscreen.com/app/img/scope_space.png)

> ` 6 ` - T2 Player 1 / Assign - ` Y `
> 
> ` 7 ` - T2 Player 2 / Assign - ` U `
> 
> ` 8 ` - T2 Player 3 / Assign - ` I `
> 
> ` 9 ` - T2 Player 4 / Assign - ` O `
> 
> ` 0 ` - T2 Player 5 / Assign - ` P `
>
> ` - ` - T2 Star Player

![](https://alexonyourscreen.com/app/img/scope_space.png)

For hectic trading situations, the `spacebar` will quickly switch to the next living player. This can also be useful in 1v1 situations to quickly switch between the two remaining players in the server.

Holding `shift` while pressing any of the **Player Cams** will move to the nearest **Action Cam** relative to that player.

![](https://alexonyourscreen.com/app/img/scope_space.png)

> ` spacebar ` - Quick Switch
> 
> ` shift ` - Relative **Action Cam**

![](https://alexonyourscreen.com/app/img/scope_space.png)

## Action Cams

The Function Keys are assigned to **Action Cams**, grouped by areas on the map. These are nearly static overviews of key areas used to display team formations or various strategy around the map. Player X-rays are shown on all of these cameras.

![](https://alexonyourscreen.com/app/img/scope_space.png)

> ` F1 ` - A Site
> 
> ` F2 ` - A Main
> 
> ` F3 ` - A Short
> 
> ` F4 ` - A Long

![](https://alexonyourscreen.com/app/img/scope_space.png)

> ` F5 ` - B Site
> 
> ` F6 ` - B Main
> 
> ` F7 ` - B Short
> 
> ` F8 ` - B Long

![](https://alexonyourscreen.com/app/img/scope_space.png)

> ` F9  ` - Middle
> 
> ` F10 ` - Alt Middle
> 
> ` F11 ` - Middle to CT
> 
> ` F12 ` - Middle to T

![](https://alexonyourscreen.com/app/img/scope_space.png)

## Spawn Cams

These are the only cameras expected to be used in a specific order during a broadcast. The **Spawn Cams** are grouped by which team is to be viewed. These cameras are best utilized in-between rounds, and at the very beginning of a round. The order is set as **Spawn Cams** > **Exit Cam 1** > **Exit Cam 2**. The player X-rays will be hidden for the spawn cams, and shown for the exit cams.

![](https://alexonyourscreen.com/app/img/scope_space.png)

> ` ins ` - CT Spawn Cams
> 
> ` home ` - CT Exit Cam 1
> 
> ` pgup ` - CT Exit Cam 2

![](https://alexonyourscreen.com/app/img/scope_space.png)

> ` del  ` - T Spawn Cams
> 
> ` end  ` - T Exit Cam 1
> 
> ` pgdn ` - T Exit Cam 2

![](https://alexonyourscreen.com/app/img/scope_space.png)

## Cinematic Cams

These cameras are expected to be used at the end of rounds (during a save, or when the bomb is about to detonate and players are evacuating the site) and during timeouts. These binds are grouped horizontally across the Numpad. The player X-rays will be hidden for these cameras.

![](https://alexonyourscreen.com/app/img/scope_space.png)

> `num` - A Site Overviews
> 
> ` / ` - A Site Short
> 
> ` * ` - A Site Long
> 
> ` - ` - A Site AWP Hold

![](https://alexonyourscreen.com/app/img/scope_space.png)

> ` 7 ` - B Site Overviews
> 
> ` 8 ` - B Site Short
> 
> ` 9 ` - B Site Long
> 
> ` + ` - B Site AWP Hold

![](https://alexonyourscreen.com/app/img/scope_space.png)

> ` 4 ` - Middle Overview
> 
> ` 5 ` - Middle to A
> 
> ` 6 ` - Middle to B

![](https://alexonyourscreen.com/app/img/scope_space.png)

> ` 1 ` - Gameplay Point 1
> 
> ` 2 ` - Gameplay Point 2
> 
> ` 3 ` - Gameplay Point 3

![](https://alexonyourscreen.com/app/img/scope_space.png)

> ` 0 ` - Map Landmark 1
> 
> ` . ` - Map Landmark  2
> 
> `ent` - Map Landmark  3

![](https://alexonyourscreen.com/app/img/scope_space.png)

## Console Output

A visual representation of all of the camera keybinds used by SCOPE will appear in your console after running the command. If it appears as a jumbled mess of lines and characters, resize the console window to be larger and the display will appear as shown:



       T1-Star      T1-P1       T1-P2       T1-P3       T1-P4       T1-P5     |     T3-P1       T2-P2       T2-P3       T2-P4       T2-P5      T2-Star   
      ---------   ---------   ---------   ---------   ---------   ---------   |   ---------   ---------   ---------   ---------   ---------   ---------  
     |         | |         | |         | |         | |         | |         |  |  |         | |         | |         | |         | |         | |         | 
     |    `    | |    1    | |    2    | |    3    | |    4    | |    5    |  |  |    6    | |    7    | |    8    | |    9    | |    0    | |    -    | 
     |         | |         | |         | |         | |         | |         |  |  |         | |         | |         | |         | |         | |         | 
      ---------   ---------   ---------   ---------   ---------   ---------   |   ---------   ---------   ---------   ---------   ---------   ---------  
          ^         ---------   ---------   ---------   ---------   ---------  \    ---------   ---------   ---------   ---------   ---------      ^     
         / \       |         | |         | |         | |         | |         |  |  |         | |         | |         | |         | |         |    / \    
          |        |    Q    | |    W    | |    E    | |    R    | |    T    |  |  |    Y    | |    U    | |    I    | |    O    | |    P    |     |     
          |_____   |         | |         | |         | |         | |         |  |  |         | |         | |         | |         | |         | ____|     
                    ---------   ---------   ---------   ---------   ---------   |   ---------   ---------   ---------   ---------   ---------            
                                     Team 1 - Set Star Player                   |                    Team 2 - Set Star Player            


                               ACTION CAMS                             |                             CINEMATIC CAMS                                      
               --------------------------------------------------      |      --------------------------------------------------------------             
              |                |                |                |     |     |                |              |              |               |            
              |                |                |                |     |     |                |              |              |               |            
              |   CT Overview  |    CT Exit 1   |    CT Exit 2   |     |     |   A Overview   |    A Long    |    A Short   |   AWP Hold A  |            
              |      (ins)     |     (home)     |     (pgup)     |     |     |    (numlock)   |     (/)      |     (*)      |      (-)      |            
              |                |                |                |     |     |                |              |              |               |            
              |                |                |                |     |     |                |              |              |               |            
               --------------------------------------------------      |      ----------------------------------------------|---------------             
              |                |                |                |     |     |                |              |              |               |            
              |                |                |                |     |     |                |              |              |               |            
              |   T Overview   |    T Exit 1    |    T Exit 2    |     |     |   B Overview   |    B Long    |    B Short   |   AWP Hold B  |            
              |      (del)     |      (end)     |     (pgdn)     |     |     |       (7)      |     (8)      |     (9)      |      (+)      |            
              |                |                |                |     |     |                |              |              |               |            
              |                |                |                |     |     |                |              |              |               |            
               --------------------------------------------------      |      ==============================================                |            
                                                                       |     |                |              |              ║               |            
               ---------   ---------   ---------   ---------           |     |                |              |              ║               |            
              |         | |         | |         | |         |          |     |  Mid Overview  |    Mid > A   |    Mid > B   ║               |            
              |   F1    | |   F2    | |   F3    | |   F4    |          |     |       (4)      |     (5)      |     (6)      ║               |            
              |         | |         | |         | |         |          |     |                |              |              ║               |            
               ---------   ---------   ---------   ---------           |     |                |              |              ║               |            
                A Over      A Main      A Short      A Long            |      --------------------------------------------- ║ ==============             
                                                                       |     |                |              |              ║               |            
               ---------   ---------   ---------   ---------           |     |                |              |              ║               |            
              |         | |         | |         | |         |          |     |  Chokepoint 1  | Chokepoint 2 | Chokepoint 3 ║               |            
              |   F5    | |   F6    | |   F7    | |   F8    |          |     |       (1)      |     (2)      |     (3)      ║               |            
              |         | |         | |         | |         |          |     |                |              |              ║               |            
               ---------   ---------   ---------   ---------           |     |                |              |              ║               |            
                B Over      B Main      B Short      B Long            |      ==============================================                |            
                                                                       |     |                               |              |               |            
               ---------   ---------   ---------   ---------           |     |                               |              |               |            
              |         | |         | |         | |         |          |     |           Landmark 1          |  Landmark 2  |   Landmark 3  |            
              |   F9    | |   F10   | |   F11   | |   F12   |          |     |              (0)              |      (.)     |    (enter)    |            
              |         | |         | |         | |         |          |     |                               |              |               |            
               ---------   ---------   ---------   ---------           |     |                               |              |               |            
                  Mid       Alt Mid     Mid > CT    Mid > T            |      --------------------------------------------------------------            

![](https://alexonyourscreen.com/app/img/scope_space.png)
