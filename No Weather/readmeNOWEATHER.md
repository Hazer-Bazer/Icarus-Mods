
Hazers No Weather
A clean and lightweight modification for Icarus that restores peace to the surface. This mod is designed for players and server hosts who prefer a focused building or survival experience without the constant interruption of harsh weather events.

Features
Total Silence: Disables all weather events in the HarshArctic weather pool.

Biome Wide Support: Affects multiple biomes across Olympus, Styx, and Prometheus (including Arctic, Desert, Swamp, and Volcanic regions).

Server Compatible: Works perfectly on dedicated servers to ensure a consistent experience for all players.

Performance Friendly: By setting event weights to zero, the engine no longer calculates or triggers complex storm transitions.

What is changed?
The mod modifies the D_WeatherPools data table. It sets the generation weight of all storm tiers (T0 to T6) to 0. This includes:

Standard Snow, Rain, and Sandstorms.

Severe Whiteouts and Heatwaves.

Special events like Volcanic Ash and Acid Rain.

Installation
Dedicated Server
Navigate to your server's Icarus/Content/Paks folder.

Drop the Hazers_No_Weather_P.pak file into the folder.

Restart the server.

Singleplayer / Client
Go to your local Icarus installation: SteamLibrary\steamapps\common\Icarus\Icarus\Content\Paks.

Place the .pak file inside the directory.

Launch the game.

Compatibility
Compatible with most mods that do not modify D_WeatherPools.json.

Can be added or removed from existing prospects without corrupting save files.

Author: Hazer

Version: 1.0

Style: Icarus Modding Integration