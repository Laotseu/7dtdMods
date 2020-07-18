Modlet Installation
===================

The installation instructions are slightly different whether you use **Stand-alone PC** or **Dedicated Server**.

Stand-alone PC
--------------

### Installation

All my mods are packaged the same way. You download a zip file that has a `Release Notes.md`, `Modlet Installation.md` (the file you are reading right now), and a `Mods` folder. To install the mdelet, simply copy the `Mods` folder into your 7 Days to Die game folder. The `Mods` folder needs to be copied in 7 Days to Die root directory.

Here are some links if you need more help:
* [How to locate Steam Game Files](https://youtu.be/6_a_yU2nc3Y)
* [More information on how to install modlets](https://7daystodie.gamepedia.com/How_to_Install_Modlets)

### Verifying that the mod is installed properly

To verify that everything worked as intended, start *7 Days to Die* to load the game menu, press `F1` to open the console, and type `version`. You should get an output similar to this one.

    > version
    2020-05-02T09:41:50 135866.647 INF Executing command 'version'
    Game version: Alpha 18.4 (b4) Compatibility Version: Alpha 18.4
    Mod Castle Spartan: 3.0
    Mod Eric's Goods: 1.0
    Mod Logan's Bar: 1.2
    Mod MoreBlocks: 1.03
    Mod PaintJob: 1.0
    Mod PG13: 1.0
    Mod SpartanBlocks: 1.4
    Mod StorageSize: 1.03

If the mod you are trying to install is not there, the installation didn't work. Press `ESC` to close the console window.

Dedicated Server
----------------

### Installation

The installation is pretty much the same as the stand-alone PC installation, you copy the `Mods` folder into the game folder on your server. Most hosting services provide FTP access that will allow you to upload the files to the right folder.

After the mod is uploaded to the server, restart the server and it's done.

For most of my mods, the players do not need to install the mod on their PC, the server installation is the only thing required. For some of them, however, a PC installation is required. In those cases, each player must download the mod and follow the Stand-alone PC instruction. 

**Pro Tip:** always install the Stand-alone PC first. 

The Modlet release notes will explicitly tell you if it needs to be installed the payers PC.

### Verifying that the mod is installed properly

The procedure to verify if the mod is installed properly on your server is similar then one for the Stand-alone PC, but the version command need to execute on the game server console that you access either through a web application or a Telnet connection.

Alternatively, you can start 7 Days to Die, join a game on the server using an account with admin rights, and then use `F1` + `version` from the client.

