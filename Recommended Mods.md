## What this is
The intent of this list is to provide recommendations for mods that would be useful to many new users. The full mods list in [CVRMG Discord](https://discord.gg/dndGPM3bxu) or [CVRMelonAssistant](https://github.com/knah/CVRMelonAssistant/releases) has a lot of mods, which can be overwhelming to go through. 

I would still recommend joining the CVRMG discord linked above so you do not miss important announcements. General instructions for installing Melonloader is in the #how-to channel. If you have any issue with mods, please post in #help-and-support and let us know!

*All of these mod download links are through CVRMG's API links. These mods have been reviewed for safety and security. If you download mods from other sources take care to verify their legitimacy.* 
# ------------- Core ------------- 
You should install these core mods and plugin, they are required for other mods to work and ensure the best experience. 
### UI Expansion Kit
>This mod provides a unified mod settings UI (you can't miss it).
>[ReadMe](https://github.com/knah/ChilloutMods#ui-expansion-kit)

https://api.cvrmg.com/v1/mods/download/90
### BTKUILib
> This mod is designed to make it very simple to create functional menus within the ChilloutVR Quick Menu. The whole goal of this library is to provide a simple API to create usable menus properly integrated within the CVR QuickMenu, all without ever having to touch Cohtml! [...]
> [ReadMe](https://github.com/BTK-Development/BTKUILib#readme)

https://api.cvrmg.com/v1/mods/download/113

### CVRModUpdater
**!! This goes in your Plugins folder !!** Everything else in this list is a mod, but CVRModUpdater is a plugin and must go in the plugins folder!
>Automatically update installed mods on game start and checks for broken mods
> [ReadMe](https://github.com/Slaynash/CVRModUpdater#readme)

https://api.cvrmg.com/v1/mods/download/19

*If you do not wish to use an Auto Updater, the mod [UpdateChecker](https://api.cvrmg.com/v1/mods/download/53) is an alternative, although CVRModUpdater will work better.*


# ------------- New Features -------------


### PortableMirrorMod
> This mod allows the user to locally spawn mirrors for themselves in any world.

https://api.cvrmg.com/v1/mods/download/70


### ImmersiveTouch
>ImmersiveTouch provides a satisfying haptic feedback in your VR controllers when your hands interacts with objects (meshes). The vibrations are speed dependent which means stroking hairs/tails etc feels very nice.
>[ReadMe](https://github.com/ImTiara/CVRMods#immersivetouch)

https://api.cvrmg.com/v1/mods/download/4


### WorldPropListMod
>Provides a list of all the props in a world with details such as the player that spawned it, distance and location, tags and more. You can delete + block individual props and highlight or create a line towards their location.
>[ReadMe](https://github.com/Nirv-git/CVRMods-Nirv/tree/main/WorldPropListMod#readme)

https://api.cvrmg.com/v1/mods/download/138


### Stickers

> Stickers! Allows you to place small images on any surface. Requires both users to have the mod installed. Synced over Mod Network.
> Limitations:
>  - Image should be under 256KB in size.
>  - Image dimensions should be a power of 2 (e.g. 512x512, 1024x1024).
>  - If the image exceeds the size limit or is not a power of 2 the mod will automatically resize it.
>  - The automatic resizing may result in loss of quality (or may just fail), so it is recommended to resize the image yourself before placing it in the `UserData/Stickers/` folder
>  More information can be found on the [README](https://github.com/NotAKidoS/NAK_CVR_Mods/blob/main/Stickers/README.md).

https://api.cvrmg.com/v1/mods/download/232


### CCK.Debugger
Very useful for avatar creators. Though may cause lag if your avatar has MANY CCK components. (Never version that fixes that is coming soon)
>The Content Creation Debugger allows you to debug `avatars`, `props` and `misc`. 
>**Menu** - Menu that displays useful information like: - Avatar and Props `synced`/`local` parameter values - Prop Pickups and Attach Info - Avatar & Props Pointers/Triggers detailed info 
>**Visualizers** - Toggleable Component visualizers: - Pointers and Triggers 3D shape - Trigger `OnEnter` (green), `OnExit` (red), `OnStay` (yellow) events - IK bones - FBT Trackers 
>Click [here](https://github.com/kafeijao/Kafe_CVR_Mods/tree/master/CCK.Debugger "here") for a more **in-depth** readme (with pictures).

https://api.cvrmg.com/v1/mods/download/74


### Action Menu
**Must setup SteamVR bindings:** 
![Image](https://github.com/user-attachments/assets/a69c34b9-4c70-4425-8b79-f6104e8fec01)
> Radial menu to quickly control your avatar and game settings with just a few taps of your joystick. By default opens with long-press of the quick menu button. It's been designed with simplicity, customization and modding in mind
> [ReadMe](https://github.com/dakyneko/DakyModsCVR/blob/master/ActionMenu/README.md)

https://api.cvrmg.com/v1/mods/download/102      
Requires you to install **VRBinding** https://api.cvrmg.com/v1/mods/download/174


### ChatBox

> Communicate with other people in the instance using Text and
> **ChatBox**es!
> See [ReadMe](https://github.com/kafeijao/Kafe_CVR_Mods/tree/master/ChatBox)

https://api.cvrmg.com/v1/mods/download/168


### RequestLib

> The Request Lib is a Mod that allows users to receive requests from other players in the same instance via the Mod Network.
> This will enable mods to ask permission for things to players without both having a specific mod. For example if both players have the **RequestLib**, this will allow the `Player 1` with the **TeleportRequest** mod to request to teleport to `Player 2` even if the `Player 2` doesn't have the **TeleportRequest** mod.

https://api.cvrmg.com/v1/mods/download/113

### TeleportRequest

> This mod allows you to request to teleport to other players. You're only able to request/accept if the world allows flight.\n\n__**Features**__\n- Request to teleport to a player.
> Teleport yourself to the previous location before teleporting to a player.

https://api.cvrmg.com/v1/mods/download/170

### IKpresets

> Provides an alternative menu for editing IK settings, includes options for automatically loading IK settings for specific avatars and 16 general slots to store presets.
> You can access the settings using BTKUI with the NirvMisc or default Misc page.

https://api.cvrmg.com/v1/mods/download/137


# ------------- Quality of Life -------------


### NoIntro
> Always skip Chillout's intro when game starts, roughly take 10 seconds.

https://api.cvrmg.com/v1/mods/download/35


### FreedomFingers
*For Index Knuckles controllers*
>This removes the annoying index controller toggle to switch between finger tracking and animation, replacing it with a gesture lock toggle. Where your fingers are tracked **all** the time but you can pick whether you want gestures or not. You can enable notifications in the melon config, to know whether the gestures are enabled or not.
>Check [README.md](https://github.com/kafeijao/Kafe_CVR_Mods/tree/master/FreedomFingers) for more info

https://api.cvrmg.com/v1/mods/download/101


### GestureLock
*For Quest, Vive, or any non-Index controllers*
>Locks GestureLeft & GestureRight on SteamVR binding. Does nothing on Knuckles controllers. Make sure to bind Controller Toggle Gestures in SteamVR.
>[ReadMe](https://github.com/NotAKidOnSteam/NAK_CVR_Mods/tree/main/GestureLock#readme)

https://api.cvrmg.com/v1/mods/download/93


### GestureIndicator
>If you ever used Index controllers, you may know how unreliable the finger tracking can be. This causes all kinds of awkward issues when you try to express yourself in front of someone without looking at a mirror. Gesture Indicator displays on the HUD which gestures you are currently doing. The text colors, transparency \u0026 positions can be customizable to your liking!
>[ReadMe](https://github.com/ImTiara/CVRMods#gestureindicator)
    
https://api.cvrmg.com/v1/mods/download/25


### NoHighlight
I recommend setting it to fade instead of remove completely
>Removes Highlights/Glow from Props (and maybe other things). Optionally just fades it out after 2 seconds

https://api.cvrmg.com/v1/mods/download/24


### Lag Free Screenshots
>Lag-free screenshots, autorotate and more
>[ReadMe](https://github.com/dakyneko/DakyModsCVR#lag-free-screenshots)

https://api.cvrmg.com/v1/mods/download/50


### RelativeSync

> Relative sync for Movement Parent & Chairs. Requires both users to have the mod installed. Synced over Mod Network.
> Provides some Experimental settings to also fix local jitter on movement parents.

https://api.cvrmg.com/v1/mods/download/211






# Unpublished Mods
**!! Use these at your own risk !!**      
These are not officially checked or approved by CVRMG although the mod authors are trusted creators.    
**>> If you experience bugs please try disabling these first <<**    
*These mods will not auto update, you will have the check the linked Github for new versions.*     



