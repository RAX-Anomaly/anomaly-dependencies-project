# anomaly-dependencies-project
A curated list of common modding dependencies to be downloaded by the Anomaly Mod Configuration Menu

## Purpose
	Developing shared scripting resources for anomaly is hampered by the fact that each addon carries its own version of the files.
There is no way to insure that every addon is using the latest version and a zombie version of a shared script can easily break an addon requiring the latest.
This issue became most apparent with trader_auto_inect.
As a way to remedy this issue Anomaly MCM now includes a downloader that checks these scripts against the ones here and downloads the version here if they do not match.
Because RavenAscendant doesn't expect anyone to trust him blindly the files AMCM downloads will only come from here, where they may be reviewed by any one.
Additions and changes to this repository will be reviewed and approved by a group of mod makers listed below.
**However this project, its curators, RavenAscendant and the individual creators (unless stated elsewhere) make no guarantees of the safety or fitness of purpose of the contents of this repository, use at your own risk.**

##License/Copyright/Usage
*The files included here are included with the consent of their creators.
*All rights are retained by the individual creators.
*Inclusion in this project does not constitute permission to include these files in any addon, mod, modpack or other derived work. That permission must be obtained from the individual creators.

##Curators
*RavenAscendant -repository owner
*Artifax -repository admin
*Demonized -repository admin
*HarukaSai
*Aoldri


##Contributors
*RavenAscendant [github](https://github.com/RAX-Anomaly) [modDB](https://www.moddb.com/members/ravenascendant/addons)
 *rax_persistant_highlights - inventory cell background coloring
 *rax_icon_layers - inventory cell icon indicator icons
 *rax_icon_override - override inventory item icons without using dltx, and ultra wide screen fixes for the inventory UI
 *rax_icon_tint - apply a tint to inventory cells
*Artifax [github](https://github.com/ahuyn)
 *arti_speed -adjust player move speed
 *trader_autoinject -modify trader inventory
 *encyclopedia_autoinject -addon defined encyclopedia entries
*Demonized [github](https://github.com/themrdemonized) [modDB](https://www.moddb.com/members/themrdemonized/addons)
 *custom_functor_autoinject -Allows to add/remove item functors (inventory right click menu) dynamically from script
 *demonized_time_events -Optimized time events
 *jump_script -modify player jump
 *new_game_loadout_injector add items to the new game loadouts
 *weight_script modify player carry weight
*Aoldri [github](https://github.com/Aoldri ) [modDB](https://www.moddb.com/members/aoldri/addons)
 *universal_animation_scripts -improved animation system [wiki](https://github.com/Aoldri/anomaly-addon-deps/wiki/Universal-Animation-Scripts)
 
## Guidelines for inclusion
* Names of dependencies and their component files should be self descriptive.
* Dependency scripts should be self documented.
* Dependencies built on monkey patches should be as targeted as possible (rax_icon_layers and rax_persistant_highlights should be separate dependencies not grouped into rax_inventory_tools).
* Dependencies should be substantially unique. 
* Dependencies included here should not interfere with one another.
