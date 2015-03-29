to run, have a bookmark to the station you are dropping off in. then syntax is

run haul origin destination
origin is the drop off point, destination is where the miners are.

origin is where you are hauling to, and needs to be a station bookmark.
destination is where you are hauling from, and can be a solar system name.

Same system mining may present issues right now. Don't name your station bookmark the same as the system name you are mining in.

Handy bookmarks to create:

In the station system on outgate - AlignTarget
In the mining system in first gate back toward station - AlignHaul

Currently the most tested format is an Orca with two tractors and a mindlink, hauling to system A from the miners location in system B. There may be issues with some other formats.

Evebot note: Evebot in safe jetcan mode wants you to be within 20000 m. Set it to 60000 m on line 620, 1174, and 1384, of

InnerSpace\Scripts\EVEBot\Branches\Stable\Behaviors\obj\_Miner.iss

This haul bot is glad to be outside of 20km and sit there, so you don't want miners stopping for no reason.