# ExlnProject
Work is currently underway to create a large monolithic project for the multi-user game Minecraft.
The project consists of a modification part that adds a graphical component, as well as communication with the server side of the modification. The server side of the modification is used for injection into the runtime of the Java machine and work with the API of the plugin of the same name, which allows you to get full functionality (both the functionality of the bukkit component and Forge), as well as to isolate transactions. The player only receives response data that is processed by openGL(LWJGL) graphics. Also, this separation allows you to abandon the graphical component for servers on the Spigot/Bukkit core.

The project's capabilities are extensive:

Opening cases with animations
Receiving and previewing kits
A logging system that allows you to track a player’s multi-accounts (ONLY WITH HIS PERMISSION) to prevent bypassing bans
Notification system in Discord, as well as executing console commands using a bot or outputting messages to the game chat and vice versa (using ConsoleLoggerHandler)
Warp system, public/private, icon, (descr in dev), checked by administrator
In-game store
Custom nbt to json serialization
Packet system prevent "fake packets". Client send only requests, with no info, requests contains only an operation code

Cases with animation
![2024-03-2901-57-26-ezgif com-apng-to-gif-converter](https://github.com/Laytin/ExlnProject/assets/70861524/a13d06fa-cf56-40e6-be07-142f5c606a52)

KitList:
![image](https://github.com/Laytin/ExlnProject/assets/70861524/4d9ae476-711e-404c-8531-ed25243a28bc)
