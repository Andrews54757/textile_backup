# Textile Backup
>Finally, a backup mod for fabric!

[![Downloads](http://cf.way2muchnoise.eu/full_359893_downloads.svg)
![Available for](http://cf.way2muchnoise.eu/versions/359893.svg)](https://www.curseforge.com/minecraft/mc-mods/textile-backup)

Small, configurable, fully server-side backup mod for Fabric  

Commands look like that: /backup 'operation'

Available operations are: 

 * start - just starts backup. You can add comment* to file by just typing it after command. For example: /backup start FabricIsGreat
 * cleanup - forces cleanup procedure (deletes old backups according to config)
 * whitelist - here you can add, remove and list player that are allowed to run any operation within this mod despite not having high enough permission level*
 * whitelist - here you can add, remove and list player that are not allowed to run any operation within this mod despite having high enough permission level*
 
All of the above can only be done by server admins(permission level 4 - configurable*) or player on a single player.

Feel free to use this mod in your modpack or on a server!

### Important

* Time format defaultly used by this mod is: dd.MM.yyyy_HH-mm-ss although it is configurable*.
* _This mod contains **Cotton Config** and its dependencies as jars in a jar, which are property of **CottonMC**_.

\* - feature available since 1.1.0

If you have any suggestions or found a problem please report it on [Github](https://github.com/Szum123321/textile_backup).