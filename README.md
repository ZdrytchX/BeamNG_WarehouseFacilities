# Warehouse Facilities

### A quick BeamNG*.Drive* mod

This mod is made by **ZdrytchX** on a whim because of how impractical it is to own a semi-trailer truck in BeamNG's Career mode.
___

## INSTALLATION
Read the official documentation: https://documentation.beamng.com/tutorials/mods/installing-mods/

Feel free to fork and change without permission (but some credit would be nice). No warranty provided. I'll probably put this on the official repo in the future though.

## BUGS

Yes I know this is kinda buggy at the current state. Refer to releases for snapshots and read the description of releases to make sure you're getting a stable version. As this mod expands and the game updates over time some stuff will inevitably break, and my computer is dead slow right now so nothing I can do about that. Sorry ;(

## Changes

### V2:

Added a bunch new locations. A lot of stuff broke, but hopefully I'll smash them out before moving onto V3 completely. Also testing fuel tanker customised loadouts. Future plans to support passenger seats too. Maybe in the long future I may have to edit lua scripts to randomise the appearance of pickup points to simulate crazy taxi/rideshare style service.    
**WARNING: NOT ALL LOCATIONS ARE ACCESSIBLE BY ALL VEHICLES.** I ADVISE THAT YOU DO NOT ATTEMPT TO USE YOUR ROAD TRAIN ONTO A ROOFTOP HELIPAD OR CHINA TOWN BACK ALLEYWAY DELIVERY.

###V1:

In short this mod adds extra content and uses the built-in (by the devs themselves) locations for warehouse pickup locations.
It gets a bit crazy with using all of them as delivery locations when you're in a rush so I kept that to a minimum.
Balance-wise it's not too crazy, but best avoid the truck-destroying tungsten loadouts because lmao, they literally destroy your truck if you don't load them correctly.
I blame BeamNG's devs for not giving us a visual representitive at this time (0.31) of the cargo load layout and without the ability to view nodes using debug controls in Career mode by default, you can't which cargo box is what.

Some other note: The "worth" parameter doesnt actually do anything right now. Official beamng devs have removed such a function from... well functioning. I'd rather not touch lua scripts because they are much harder to merge changes as the game changes compared to json tables, which are done in patchwork-like fashion (meaning the game can update and the likelihood of it breaking even in like 5 years times is well, unlikely, unless I somehow do something horrible like with v2)