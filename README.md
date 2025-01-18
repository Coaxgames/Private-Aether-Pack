# NEW NOTES/UPDATES #
~Java runtime args are now recommened (im finding a mod that applies them from config right at startup), for now check changlogs for changes with the runtime stuff
~AutoModUpdater Now installed in tandem with Mod Update Checker, this ensures single player doesnt get forgotten. Joining the server will install the current latest version of the modpack
~More mods removed causing spikes: Slender stuff, From the fog, LittleTiles, Doppel(no configs!) and the deer mod (Over spawning bc its based on max cap, servercore pushes that limit already)

~Formatting change to updates:
  ~Fresh: A fresh install of forge 1.20.1, ther is no mods other than the modupdater. Joining the server is how you install the mods, Otherwise the serveconfigs are availible for both
  ~Client: A DIRECT Upload of the latest modpack verison, Comes with preset options, Configs, ect. Need no setup other than joining the server to update every so often (No server files yet!)
  

# ----New Install Guide's---- #
Barebones/Client install:
~Download 3.2.6 ClientOnly!
~Import to CurseForge (or whatever)
~Open folder for new and Old version
~Move anything you need over (options and Optionsof, any Xearos folder, Mod data, Saves and configs, ect)
~Run Game and connect to the built-in server (You wont connect, but it will install all de mods)
~Restart after download finished and play!

Update/SinglePlayer approach:
~Download the 3.2.6 FullBuild
~Import to CurseForge (or whatever)
~Open folder for new and Old version
~Move anything you need over (options and Optionsof, any Xearos folder, Mod data, Saves and configs, ect)
~Run game and play!

Download and play approach (Not ready Yet!):
~Download the 3.2.6 ReleaseBuild from -InsertmodpackHTMLhere-
~Thats it, once loaded you can enabled updates from the launcher you use. No moving file required!


# FOR SINGLE PLAYER OR LOWER END SYSTEMS README!! #
Please use these JVM arguments, This will help prevent Embed & Oculus from using too much memory
Under testing these are the minimal to prevent crashing:
-XX:+UnlockExperimentalVMOptions -XX:+UseG1GC -XX:+DisableExplicitGC -XX:G1NewSizePercent=30 -XX:InitiatingHeapOccupancyPercent=15 -XX:G1ReservePercent=25 -XX:MaxGCPauseMillis=40 -XX:G1RSetUpdatingPauseTimePercent=5 -XX:G1MixedGCCountTarget=4 -XX:G1MixedGCLiveThresholdPercent=90 -XX:G1HeapRegionSize=16M -XX:+PerfDisableSharedMem -XX:MaxTenuringThreshold=1 -XX:G1MaxNewSizePercent=40



# ----Discord Server---- # (Get the MC role and open a ticket for help!):
https://discord.gg/aYFXyABmmT








Todo for Modpack managment:
~Get the modpack JAR file, upload to Curse or modrinth, but make sure to swap all jar files and verify there not local files!
If there local mods, the Curse/Modrinth will deny the upload, Ofc this can happen normally but still needs to be checked

~When making an update, also make the next version and hook the html for it, this way its always on the newest version link OR set the HTML link to always go to the homepage, this will ensure no confusion over correction