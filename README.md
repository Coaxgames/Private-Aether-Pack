# NEW NOTES/UPDATES #  
~Moved To Versions For better Changelog tracking  
https://github.com/Coaxgames/Xaons-Exploration-n-Adventure-Pack/tree/CurseForge/ReleaseVersions/versions
# ----New Install Guide's---- #  
Barebones/Client install:  
1. Download 3.2.6 ClientOnly!  
2. Import to CurseForge (or whatever)  
3. Open folder for new and Old version  
4. Move anything you need over (options and Optionsof, any Xearos folder, Mod data, Saves and configs, ect)  
5. Run Game and connect to the built-in server (You wont connect, but it will install all de mods)  
6. Restart after download finished and play!  

Update/SinglePlayer approach:
1. Download the 3.2.6 FullBuild
2. Import to CurseForge (or whatever)
3. Open folder for new and Old version
4. Move anything you need over (options and Optionsof, any Xearos folder, Mod data, Saves and configs, ect)
5. Run game and play!

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
