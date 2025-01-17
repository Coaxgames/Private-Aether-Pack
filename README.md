# NEW NOTES/UPDATES #
~Java runtime args are now recommened (im finding a mod that applies them from config right at startup), for now check changlogs for changes with the runtime stuff
~AutoModUpdater Now installed in tandem with Mod Update Checker, this ensures single player doesnt get forgotten. Joining the server will install the current latest version of the modpack
~More mods removed causing spikes: Slender stuff, From the fog, LittleTiles, Doppel(no configs!) and the deer mod (Over spawning bc its based on max cap, servercore pushes that limit already)

~Formatting change to updates:
  ~Fresh: A fresh install of forge 1.20.1, ther is no mods other than the modupdater. Joining the server is how you install the mods, Otherwise the serveconfigs are availible for both
  ~Client: A DIRECT Upload of the latest modpack verison, Comes with preset options, Configs, ect. Need no setup other than joining the server to update every so often (No server files yet!)
  

# FOR SINGLE PLAYER OR LOWER END SYSTEMS README!! #
i Updated the GC (Memory Cleaner) to run quicker with a lower pause time (@40), seems to never crawl up too high now. this may be different for some, im running 14gb. this pack is using at MOST 70$ of that, though the GC is set to reserve 30/40% memory of total MC allocated memory, this results in the gc running more frequent, but i have limited its max tick time to 40ms roughly, this should mean the client can never crash with enough memory given to MC (Though DO NOT apply more than 70% of your MAX ram to MC and never apply less than 4~6gb, this can cause runaway style lockups, or MC crashing due to some mod, when its infact ram)

for context im running a i7-9700 with a 1070ti, 28gb of ram running @ 2666mhz. i have only allowed 14gb out of the 28gb bc MC will try to take too much and run down memory speeds. so keeping the memory lower is better in this situation.

GC Runtime arg link:
https://github.com/Coaxgames/Private-Aether-Pack/blob/CurseForge/ReleaseVersions/versions/3.2.5/changelog.txt
