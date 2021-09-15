Modlet Installation
===================

These instructions will tell you how to add **Eric's Goods** to the game POIs and have it spawn in your randomly created world.

Included Files
--------------

The following files and directories are included in the .ZIP package
- `Modlet readme.md` (The file you are reading right now)
- `Mods\EricsGoods` (Contains everything you need to copy to your game or server Mods directory)  
  - `ModInfo.xml` (Allow the mod to load, contain version information)
  - `Config` (Files that modify the game XML)
  - `Prefabs` (The actual POI files)

For the latest version of the modlet, visit my [7dtdMods GitHub repository](https://github.com/Laotseu/7dtdMods)

For stand-alone PC installation
-------------------------------

Copy the **EricsGoods** folder into your 7 Days do Die `Mods` folder.

Optional: copy the `Mods\EricsGoods\Prefabs` files into your game `Data\Prefabs`. This will allow you to see the POI using the in game POI editor.


For dedicated server installation
---------------------------------

It's pretty much the same thing then the stand-alone PC installation, you copy the **EricsGoods** folder into the server `Mods` folder on your server. Most hosting services provide FTP access that will allow you to upload the files to the right folder.

The players do not need to install the mod, it only has to be installed on the server.

* [More information on how to install modlets](https://7daystodie.gamepedia.com/How_to_Install_Modlets)

How to use the mod
==================

Once the mod is installed, randomly generated worlds will have a chance to spawn Eric's Goods. In fact, all instance of the vanilla POI Eric's Stuff will instead be spawn as Eric's Goods. You just have to generate a new world and the PIO should be in there somewhere. There should be multiple instances in your new world.

As you may guess, this will only work with newly generated worlds. Any world that was generated before you installed the mod will not spawn the new POI. You will also need to start a new game in order to use that new world.

How to see if the POI actually spawned in my generated world
============================================================

Once the world is generated, you will find a folder with the world name near where the save games are located. On my PC, the folder for the generated worlds is `%APPDATA%\7DaysToDie\GeneratedWorlds`. (I'm using a Windows 10 box.) For dedicated servers, you might find the folder by looking at the **UserDataFolder** in the **serverconfig.xml** file. You will need to find where that folder is on your PC or Server. 

Once you found the folder named for your world (something like _South Pidimo County_ or _West Wikeno Territory_), you will find a file named `prefabs.xml` inside. If you open that file with any text editor like Notepad, you can search for `EricsGoods`. If you find it, you know that your random world has spawned the POI.