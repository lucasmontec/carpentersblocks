---
layout: default
title: Changelog
---

<h3><a name="designer-templates" class="anchor" href="#designer-templates"><span class="octicon octicon-link"></span></a>Complete Changelog</h3>

<span id="label-stable">3.2.0</span>
<span id="label-generic">06/22/2014</span>
<ul id="changelog-full">
   <li>Design system refactored; existing chisel patterns and designs excluding Tiles will be wiped from blocks.</li>
   <li>Resource cache is now created at runtime and stored in mods folder under "/<MCVersion>/carpentersblocks".</li>
   <li>Bed designs now have simplified template, and no longer require expensive rendering techniques.</li>
   <li>Collapsible block rendering modified to allow seamless connections. [elpocko]</li>
   <li>Collapsible block auto-sloping is now more aware of surroundings. [elpocko]</li>
   <li>Proper ambient occlusion support added for Collapsible block.</li>
   <li>Fixed bed frame dye and grass coloring issues.</li>
   <li>Migration support added for moving 1.6.4 worlds to 1.7.2. (See new section below for instructions)</li>
</ul>

<span id="label-stable">3.1.6</span>
<span id="label-generic">06/13/2014</span>
<ul id="changelog-full">
   <li>Fixed dye crash introduced in Forge build 1113.  Must use build 1118 to get correct dye coloration.</li>
   <li>Removed tile entity restriction for covers (some blocks may look unusual as covers).</li>
   <li>Added config option to add cover exceptions with Thaumcraft planks added by default.</li>
   <li>Fixed block sounds playing incorrectly, and sound-related errors in console.</li>
   <li>Cleaned up configuration and made custom overlay items easier to add.</li>
   <li>NOTE: I advise deleting your existing config and starting fresh.</li>
</ul>

<span id="label-stable">3.1.5</span>
<span id="label-generic">05/31/2014</span>
<ul id="changelog-full">
   <li>Fixed a bug causing some covers to crash when removed from block.</li>
   <li>Tweaked a lot of code to help prevent door crashes, render crashes, and more.</li>
   <li>Refactored here and there.</li>
</ul>


<span id="label-stable">3.1.4</span>
<span id="label-generic">04/25/2014</span>
<ul id="changelog-full">
   <li>Added protection against MoC-related crashes.</li>
   <li>Fixed door and bed permission problems in survival.</li>
   <li>Fixed safe inventory rendering bug.</li>
   <li>Further tweaks to sneak right-click behavior.</li>
</ul>

<span id="label-stable">3.1.3</span>
<span id="label-generic">04/23/2014</span>
<ul id="changelog-full">
   <li>Fixed vine and mycelium overlays not working.</li>
   <li>Cover block sounds reimplemented (Forge build 1060 now required).</li>
   <li>Door and bed permissions issues resolved.</li>
   <li>Cover restrictions adjusted to only accept full blocks (no panes or slabs).</li>
   <li>Tool-block interaction sounds improved.</li>
   <li>Wrinkles in sneak right-click system ironed out.</li>
   <li>Fix hammer and chisel damaging blocks.</li>
   <li>Tile no longer ejects with hammer if clicked by non-owners.</li>
</ul>

<span id="label-stable">3.1.2</span>
<span id="label-generic">04/10/2014</span>
<ul id="changelog-full">
   <li>Added some missing protection against crashes when removing blocks.</li>
   <li>Block texture loading refactored; should hopefully eliminate invisible blocks.</li>
   <li>Tiles can now only be dyed if the player is sneaking (like blocks).</li>
   <li>Tiles no longer play dye sound if not changing color attribute.</li>
</ul>

<span id="label-stable">3.1.1</span>
<span id="label-generic">04/08/2014</span>
<ul id="changelog-full">
   <li>Fixed dye crash.</li>
</ul>

<span id="label-stable">3.1.0</span>
<span id="label-generic">04/04/2014</span>
<ul id="changelog-full">
   <li>Added Carpenters Tile (inspired by Kaevators Wallpaper Mod).</li>
   <li>Kaevator wallpaper textures made available as add-on pack.</li>
   <li>Fixed pick block on bed returning vanilla bed.</li>
   <li>Removed MCPatcher compatibility, as it appears to no longer be needed.</li>
</ul>

<span id="label-stable">3.0.4</span>
<span id="label-generic">03/27/2014</span>
<ul id="changelog-full">
   <li>Fixed a dupe bug.</li>
</ul>

<span id="label-stable">3.0.3</span>
<span id="label-generic">03/25/2014</span>
<ul id="changelog-full">
   <li>Fixed rendering problems when using Optifine.</li>
   <li>Player now must be sneaking to apply overlays and dyes.</li>
   <li>Fixed chisel patterns above 127 crashing client.</li>
   <li>Fixed dark glass insets on doors and hatches (for good).</li>
   <li>Fixed stairs and slopes improperly rotating or switching types when using hammer.</li>
   <li>Fixed chisel patterns rendering green on top.</li>
</ul>

<span id="label-stable">3.0.2</span>
<span id="label-generic">03/22/2014</span>
<ul id="changelog-full">
   <li>Fixed server crash when producing block particles.</li>
   <li>Fixed block slipperiness bug.</li>
   <li>Cleaned up overlay code.</li>
</ul>

<span id="label-stable">3.0.1</span>
<span id="label-generic">03/22/2014</span>
<ul id="changelog-full">
   <li>Fixed pressure plate activation problems.</li>
</ul>

<span id="label-stable">3.0.0</span>
<span id="label-generic">03/22/2014</span>
<ul id="changelog-full">
   <li>First for MC 1.7.2, significant changes made (no backwards compatibility).</li>
   <li>Block dye system now uses OreDictionary, should support mod dyes.</li>
   <li>Both vanilla mushrooms can now be used for mycelium overlay.</li>
   <li>Flower pot support added for all new vanilla plants, sunflower can face any direction.</li>
   <li>Flower pot biome-coloring override is now enforced by using bonemeal on plant.</li>
   <li>Alpha pass rendering is disabled for the time being.</li>
   <li>Cover sounds are disabled for the time being.</li>
   <li>Overlay items can now be specified in the config file.</li>
</ul>

<span id="label-stable">2.1.2</span>
<span id="label-generic">06/22/2014</span>
<ul id="changelog-full">
   <li>Now properly converts slopes and stairs when migrating to 1.7.2.</li>
</ul>

<span id="label-stable">2.1.1</span>
<span id="label-generic">06/21/2014</span>
<ul id="changelog-full">
   <li>Added migration code to assist in converting 1.6.4 worlds to 1.7.2.</li>
</ul>

<span id="label-stable">2.1.0</span>
<span id="label-generic">05/21/2014</span>
<ul id="changelog-full">
   <li>Added config option to allow blocks with tile entities as covers.</li>
</ul>

<span id="label-stable">2.0.9</span>
<span id="label-generic">05/20/2014</span>
<ul id="changelog-full">
   <li>Fixed MoC-related crashes.</li>
</ul>

<span id="label-stable">2.0.8</span>
<span id="label-generic">03/21/2014</span>
<ul id="changelog-full">
   <li>Fixed visual anomalies when changing block properties.</li>
</ul>

<span id="label-stable">2.0.7</span>
<span id="label-generic">03/19/2014</span>
<ul id="changelog-full">
   <li>Attempt to fix BoP crash issue and food + block interaction issues.</li>
</ul>

<span id="label-stable">2.0.6</span>
<span id="label-generic">03/14/2014</span>
<ul id="changelog-full">
   <li>[PATCH 3/15] Fixed adventure mode preventing block left-click actions.</li>
   <li>Fixed slope brightness problems.</li>
   <li>Fixed oblique slope uncovered face textures not connecting.</li>
   <li>Fixed faces sometimes rendering when they should not.</li>
</ul>

<span id="label-stable">2.0.5</span>
<span id="label-generic">03/12/2014</span>
<ul id="changelog-full">
   <li>Fixed BoP-related block right-click crashes.</li>
   <li>Fixed slopes becoming unusually dark and/or lighting strangely.</li>
   <li>Fixed possible ItemStack crash with slopes.</li>
   <li>Safe will no longer be destroyed by explosions.</li>
   <li>Fixed chisel patterns not rendering on a few blocks.</li>
</ul>

<span id="label-stable">2.0.4</span>
<span id="label-generic">02/27/2014</span>
<ul id="changelog-full">
   <li>Corrected flower pot not dropping when it should.</li>
   <li>Corrected weird click behaviors, including double messages.</li>
   <li>Fixed some more crashes when neighbor blocks change their light properties.</li>
</ul>

<span id="label-stable">2.0.3</span>
<span id="label-generic">02/21/2014</span>
<ul id="changelog-full">
   <li>Removed some vanilla ambient occlusion lighting code to fix lighting anomalies.</li>
   <li>Added dynamic partial depth ambient occlusion (defaulted with smooth lighting).</li>
   <li>Added BlockRotatedPillar as rotatable block (hay bale, and maybe others).</li>
   <li>Removed opaque cover requirement for chiseling blocks.</li>
   <li>Slope recipe altered.</li>
   <li>Barrier recipe altered.</li>
   <li>Slope selection is now possible when slope is held; hold sneak and use scroll wheel.</li>
   <li>Prism slopes now automatically connect to each other.</li>
   <li>Pyramid slope renamed to prism slope; is now base prism form.</li>
   <li>Fixed flower pot placement crashes.</li>
   <li>Fixed bug causing Ars Magica 2 ores to drop incorrect blocks.</li>
   <li>Cleaned up and tweaked slope and stair placement code.</li>
   <li>Fixed possible getLightValue crash.</li>
   <li>Fixed possible Carpenters Block client-side crash.</li>
</ul>

<span id="label-stable">2.0.2</span>
<span id="label-generic">01/31/2014</span>
<ul id="changelog-full">
   <li>Fixed ladder placement related crashes.</li>
   <li>Fixed tile entity update conditions throwing warnings in log.</li>
   <li>Fixed daylight sensor inventory rendering sometimes crashing client.</li>
   <li>Added location-sensitive light opacity to full Carpenters Blocks, should hopefully prevent lightning from striking through blocks.</li>
</ul>

<span id="label-stable">2.0.1</span>
<span id="label-generic">01/30/2014</span>
<ul id="changelog-full">
   <li>Fixed gate crash.</li>
</ul>

<span id="label-stable">2.0.0</span>
<span id="label-generic">01/26/2014</span>
<ul id="changelog-full">
   <li>Cleaned up and fixed smooth lighting being wrong or incomplete for top and bottom faces.</li>
   <li>Cleaned up smooth brightness on collapsible top face.</li>
   <li>Cleaned up slope lighting issues from recent changes.</li>
   <li>Block break speed now takes into account item strength versus the cover block.</li>
   <li>Safe will no longer visually begin cracking if being destroyed by player that does not have edit permission.</li>
   <li>Darkness with block breaking texture brightness on slopes and collapsible block corrected.</li>
   <li>Adjusted default block IDs to be FTB-friendly.</li>
   <li>Torch can now be crafted with charcoal.</li>
   <li>Torch will no longer extinguish in dry biomes.</li>
   <li>Possible fix for getEnableAO() crash.</li>
   <li>Door and bed (multiblock) placement should no longer cause crashes under any circumstances.</li>
   <li>Icon-related inventory rendering crashes should no longer occur.</li>
   <li>Revised general edit permissions.</li>
   <li>Revised Safe edit permissions.</li>
   <li>Safe render updates should now only occur once per second, at most.</li>
   <li>Cover rotation data now resets before block ejection.</li>
   <li>Oblique sloped faces now have aligned textures. Uncovered texture unified.</li>
   <li>Refactored and bug-fixed texture rotation code.</li>
   <li>Fixed bug where pointing at block prevents food right-click behavior.</li>
   <li>Fixed various rendering problems when z-fighting fix is enabled.</li>
   <li>Fixed players in adventure mode being unable to activate blocks.</li>
   <li>Fixed collision boxes for North and West facing wedge roof prisms.</li>
   <li>Fixed safe rotation discrepancy in code; rotate your existing safes with hammer left-click.</li>
   <li>Base blocks now inherit slipperiness from covers.</li>
</ul>

<span id="label-stable">1.9.9</span>
<span id="label-generic">01/01/2014</span>
<ul id="changelog-full">
   <li>[PATCH] Uncovered blocks can now catch fire.</li>
   <li>[PATCH] Bed designs can now be cleared with hammer sneak right-click.</li>
   <li>[HOTFIX] Corrected flower pot plant rendering for a couple Biomes O Plenty plants.</li>
   <li>[HOTFIX] Fixed flower pot not decrementing itemstack when plant is placed.</li>
   <li>Added Carpenters Flower Pot (formerly Painters Flower Pot).</li>
   <li>Flower pot components can now be altered independently.</li>
   <li>You can now add your own flower pot designs.</li>
   <li>Dye colors now use RGB from vanilla dyes.</li>
   <li>Side covers now do depth checks before popping off.</li>
   <li>Collapsible block given proper shading and slope creation.</li>
   <li>Collapsible block hammer behavior improved. Left-click raises corner, right-click lowers corner.</li>
   <li>Fixed possible crashes in the way block solidity checks are performed.</li>
   <li>Added hammer right-click sensitivity setting to daylight sensor.</li>
</ul>

<span id="label-stable">1.9.8</span>
<span id="label-generic">12/21/2013</span>
<ul id="changelog-full">
   <li>Slope rendering and lighting overhauled, again.</li>
   <li>Added 5 more slope types with 19 new pieces.</li>
   <li>Tool stack size set to 1.</li>
   <li>Fixed MC 1.5+ version being broken on server, and not playing some sounds client-side.</li>
   <li>Cover blocks that have icon issues will now use missing icon texture.</li>
   <li>Configuration file has a new setting to correct MCPatcher texture problems.</li>
   <li>Slope raytracing no longer broken by setting block bounds (breaks all the time).</li>
   <li>Fixed sprint particle handling causing massive lag spikes.</li>
   <li>Cover particles now side- and overlay-sensitive.</li>
   <li>Fixed torches not being placable on certain blocks.</li>
   <li>Fixed collapsible block top face solidity check not working.</li>
</ul>

<span id="label-stable">1.9.7</span>
<span id="label-generic">12/10/2013</span>
<ul id="changelog-full">
   <li>[PATCH] Added new language files and fixed gray vine overlays.</li>
   <li>[HOTFIX] Fixed safe automation bugs.</li>
   <li>[HOTFIX] Added null protection to sound event handler.</li>
   <li>Added config option to disable hammer in case a different hammer is enforced through API.</li>
   <li>Daylight Sensor now has a unique look and recipe.</li>
   <li>Fixed side covers not using correct texture on stairs (v1.9.6 bug).</li>
   <li>Added Carpenters Safe.</li>
   <li>Added block ownership config setting (set to true by default).</li>
   <li>Fixed long-standing chat message bugs.</li>
   <li>Moved all block click methods server-side to improve accuracy.</li>
   <li>Cover sounds now mostly working.</li>
   <li>Inventory rendering changes to hatch.</li>
   <li>Fixed configuration comments not being created.</li>
   <li>Added missing Carpenters Block disabling code.</li>
   <li>Bed special rendering checks separated from the other blocks, may improve performance.</li>
   <li>Fixed torch sides sometimes being very dark.</li>
</ul>

<span id="label-stable">1.9.6</span>
<span id="label-generic">12/07/2013</span>
<ul id="changelog-full">
   <li>Added torch config option to disable weather effects (enforced server-side only).</li>
   <li>Corrected door (and possibly bed) blocks from appearing in mods like NEI. [Tarig]</li>
   <li>Hidden hatch dimensions reduced and can now be climbed when opening downward.</li>
   <li>Torch recipe quantity reduced to 4 torches.</li>
   <li>Corrected incorrect torch side lighting.</li>
   <li>Corrected incorrect lever side lighting.</li>
   <li>Directional blocks (logs, pumpkins, quartz) now set direction based on player facing.</li>
   <li>Sprinting particle and sound support added for covers. [Eurymachus, Tarig]</li>
   <li>Some cover sound code added for block interaction with tools.</li>
   <li>Added simple API for adding your own hammer or chisel. [LordMau5]</li>
   <li>Rendering code decoupled, a lot.</li>
   <li>Added code to prevent most of the NPEs reported.</li>
   <li>Fixed slopes and stairs not auto-cornering in 75% of cases.</li>
</ul>

<span id="label-stable">1.9.5</span>
<span id="label-generic">11/10/2013</span>
<ul id="changelog-full">
   <li>Added Carpenters Torch.</li>
   <li>[HOTFIX] Corrected crash when clicking door without item in hand.</li>
   <li>[HOTFIX] Fixed some torch particles not showing up.</li>
</ul>

<span id="label-stable">1.9.4</span>
<span id="label-generic">11/08/2013</span>
<ul id="changelog-full">
   <li>Added chance to damage Hammer for Collapsible Block.</li>
   <li>Fixed abnormal pressure plate behavior and cleaned up code.</li>
   <li>Button code refactored, some bugs fixed.</li>
   <li>Lever code refactored, some bugs fixed.</li>
   <li>Fixed textures not rotating (bugged in v1.9.2).</li>
</ul>

<span id="label-stable">1.9.3</span>
<span id="label-generic">10/25/2013</span>
<ul id="changelog-full">
   <li>Added Collapsible Block.</li>
   <li>Improved bounding box for pyramid slopes.</li>
   <li>Fixed directional blocks facing opposite of side clicked.</li>
</ul>

<span id="label-stable">1.92</span>
<span id="label-generic">10/20/2013</span>
<ul id="changelog-full">
   <li>Interactions with covered blocks no longer risks throwing crash.</li>
   <li>Corrected miscellaneous crashes.</li>
   <li>Beds and ladders decoupled from metadata - further reduces likelihood of crashes.</li>
   <li>Block cover hit particles added.</li>
</ul>

<span id="label-stable">1.91</span>
<span id="label-generic">09/28/2013</span>
<ul id="changelog-full">
   <li>[HOTFIX] Fixed array out of bounds crash.</li>
   <li>All blocks and most slopes now support directional metadata.</li>
   <li>Side cover directional blocks determine direction based on player pitch and yaw.</li>
   <li>Improved side click detection for sloped faces (thanks Tarig).</li>
</ul>

<span id="label-stable">1.9</span>
<span id="label-generic">09/24/2013</span>
<ul id="changelog-full">
   <li>Slopes code, rendering and lighting system rewritten.</li>
   <li>Side render checking improved across the board.</li>
   <li>Stairs code rewritten.</li>
   <li>Fixed hay side overlay not adjusting height with block.</li>
   <li>Interior oblique slopes now use a mix of other slope hitboxes to closely match shape.</li>
   <li>Removed pointless cover collision detection, was culprit of some crashes.</li>
</ul>

<span id="label-stable">1.87</span>
<span id="label-generic">09/17/2013</span>
<ul id="changelog-full">
   <li>Fixed hammer messages not appearing when left clicking.</li>
   <li>Fixed long unnoticed slope hitbox ray tracing bug.</li>
   <li>Updated zh_CN.lang.</li>
   <li>Added ru_RU.lang localization.</li>
</ul>

<span id="label-stable">1.86</span>
<span id="label-generic">09/13/2013</span>
<ul id="changelog-full">
   <li>Blocks now correctly output redstone signal according to cover properties.</li>
   <li>Added Carpenters Ladder.</li>
   <li>Fixed chisel left click cycling pattern twice.</li>
   <li>[HOTFIX] Fixed Carpenters Hammer left click server-side code mishap.</li>
   <li>[HOTFIX] Updated de_DE.lang localization.</li>
</ul>

<span id="label-stable">1.85</span>
<span id="label-generic">09/11/2013</span>
<ul id="changelog-full">
   <li>Corrected high tick latency caused by ineffectual update code. [bstramke, demon012]</li>
   <li>Minor adjustments here and there.</li>
   <li>[PRIOR HOTFIX] Fixed bed designs being broken in MC 1.6+.</li>
   <li>[PRIOR HOTFIX] Fixed overly aggressive fail-safe code in a couple handlers (Plants, Optifine).</li>
</ul>

<span id="label-stable">1.84</span>
<span id="label-generic">09/08/2013</span>
<ul id="changelog-full">
   <li>Tweaked barrier post generation some more to correct some missing posts.</li>
   <li>Minor bug fixes, optimizations, code clean-up.</li>
   <li>Added language support.</li>
   <li>Added de_DE localization.</li>
   <li>Added block placement sound for Carpenters Bed and Door.</li>
   <li>Fixed corner slopes forming obliques when they should form regular corners.</li>
   <li>Fixed some z-fighting on beds.</li>
   <li>Newly placed doors now copy rigidity of neighboring, connected doors.</li>
</ul>

<span id="label-stable">1.83</span>
<span id="label-generic">08/30/2013</span>
<ul id="changelog-full">
   <li>Fixed casting crash fix causing blanket on bed to not raise in some cases.</li>
   <li>Improved rendering code to better handle offset face AO lighting.</li>
   <li>Replaced sticks in chisel and hammer recipes with Carpenters Blocks to eliminate conflicts.</li>
   <li>Vanilla icon rotation code rewritten to correct texture alignment bugs (a better implementation).</li>
   <li>Carpenters Bed switched to fast lighting like vanilla bed to stop ugly shading.</li>
   <li>Customization added for Carpenters Bed - use the hammer. Add your own designs!</li>
   <li>Cleaned up chisel pattern handling code and corrected a bug when cycling through patterns.</li>
   <li>Corrected NPE when placing wrath lamps near block, I think.</li>
</ul>

<span id="label-stable">1.82</span>
<span id="label-generic">08/25/2013</span>
<ul id="changelog-full">
   <li>Added Carpenters Bed with dyeable blanket.</li>
   <li>Fixed barrier above another barrier creating post on bottom barrier.</li>
</ul>

<span id="label-stable">1.81</span>
<span id="label-generic">08/22/2013</span>
<ul id="changelog-full">
   <li>Carpenters Door and Lever given their own icons.</li>
   <li>Fixed z-FightingFix config option causing glass and screen in doors/hatches to render twice.</li>
   <li>Fixed blocks throwing crash when destroyed with a tool.</li>
   <li>Fixed plants being plantable on non-solid surfaces.</li>
   <li>[HOTFIX] Cleaned up and fixed some bugs in barrier post generation code.</li>
</ul>

<span id="label-stable">1.8</span>
<span id="label-generic">08/21/2013</span>
<ul id="changelog-full">
   <li>Applying covers now plays accompanying block placement sound.</li>
   <li>Most plants should now be plantable on Carpenters Blocks (still no mushrooms, though).</li>
   <li>Side covers are now unique - can be customized independent from base block.</li>
   <li>Dye colors no longer alter color on patterns or overlays.</li>
   <li>Top covers no longer use height adjustment to conceal pressure plates (just cover both the same).</li>
   <li>Carpenters Doors and Hatches now have configurable redstone behavior (sneak right click with hammer).</li>
   <li>Optimized, bug-fixed and cleaned up door code.</li>
   <li>Chisel left/right click now cycles forwards or backwards through patterns. Sneak left click with chisel clears pattern.</li>
   <li>Shifted code execution for covers, overlays, dye colors and patterns between client and server to resolve problematic behavior.</li>
   <li>Converted console output to FML logging system.</li>
   <li>Fixed hatch handles inadvertently using custom renderer.</li>
   <li>Grass blocks used as covers now pre-render grass overlays to correct rendering conflicts with other overlays.</li>
   <li>Hammer behavior altered when interacting with gates and fences. Test it out, and try sneak-right-click.</li>
   <li>Vanilla gate and barrier type with thickest plank sub-type now render a single plank instead of many smaller ones.</li>
   <li>Forcing a fence post on barriers now prevents connections to solid faces.</li>
   <li>Fixed a bug in side render checks causing invisible sides.</li>
   <li>Fixed bug causing side covers on slopes to sometimes have invisible sides.</li>
   <li>Fixed barriers making non-valid connections to neighboring blocks.</li>
</ul>

<span id="label-stable">1.77</span>
<span id="label-generic">08/10/2013</span>
<ul id="changelog-full">
   <li>Reverted some code for Carpenters Hatch to prevent unintended state changes.</li>
   <li>Corrected covers, overlays and patterns covering the top of Carpenters Daylight Sensor.</li>
   <li>Corrected slope sides not rendering when they should.</li>
   <li>Solid sides of slopes now support side covers (sloped and partial faces are never considered solid).</li>
   <li>Miscellaneous code clean-up.</li>
</ul>

<span id="label-stable">1.76</span>
<span id="label-generic">08/07/2013</span>
<ul id="changelog-full">
   <li>Overlays now will always render on both passes to resolve layering problems.</li>
   <li>Added support for up to 256 custom chisel patterns (look at README in pattern image folder).</li>
   <li>Added optional z-fighting fix for chiseled patterns in config file.</li>
   <li>Side render checking system cleaned up and working 100%, I think.</li>
   <li>Miscellaneous code clean-up.</li>
</ul>

<span id="label-stable">1.75</span>
<span id="label-generic">08/05/2013</span>
<ul id="changelog-full">
   <li>Corrected item IDs being shifted from settings in config file.</li>
   <li>Tweaked side render checks to handle matching non-opaque covers.</li>
   <li>Tweaked cover checks to allow more blocks as covers.</li>
   <li>Overlays no longer render on unrendered sides.</li>
   <li>Patterns can now only be applied to opaque, covered blocks.</li>
</ul>

<span id="label-stable">1.74</span>
<span id="label-generic">08/02/2013</span>
<ul id="changelog-full">
   <li>Pressure plates now use their reduced collision area for activation.</li>
   <li>Fixed unexpected behavior when double doors were placed in a row.</li>
   <li>Double doors now behave like a single entity regarding activation sound and redstone state change.</li>
   <li>If any part of a door or double door set is iron material, it will now require redstone current for activation.</li>
</ul>

<span id="label-stable">1.73</span>
<span id="label-generic">07/31/2013</span>
<ul id="changelog-full">
   <li>Carpenters Doors covered with iron material now require redstone activation.</li>
   <li>Added max smooth lighting support for top and bottom block faces.</li>
   <li>Fixed some box overlap in french doors.</li>
   <li>Ambient occlusion support added for all doors and hatches.</li>
</ul>

<span id="label-stable">1.72</span>
<span id="label-generic">07/30/2013</span>
<ul id="changelog-full">
   <li>[PRIOR HOTFIX] Corrected serverside crash.</li>
   <li>Added Carpenters Door with six door types.</li>
   <li>Added four new matching hatch types.</li>
   <li>Made half slabs a valid cover once again.</li>
   <li>Made hatches always placeable against Carpenters Block.</li>
   <li>Chiseled patterns will now continue patterns from any neighboring Carpenters block.</li>
</ul>

<span id="label-stable">1.71</span>
<span id="label-generic">07/27/2013</span>
<ul id="changelog-full">
   <li>[PRIOR HOTFIX] Dyed blocks now eject the dye when breaking blocks.</li>
   <li>Fixed Carpenters Block auto-orientation sneak override missing.</li>
   <li>Block restriction config option removed - using a better default checking system.</li>
   <li>Fixed bugs that caused block and side covers to potentially render in incorrect pass.</li>
   <li>Added configuration option to disable tool damage.</li>
   <li>Rewrote icon handling to fix 3D switching and related texture bugs.</li>
   <li>Fixed solid block side render checks not working.</li>
   <li>Made buttons, levers and pressure plates silent if covered with cloth.</li>
</ul>

<span id="label-stable">1.7</span>
<span id="label-generic">07/22/2013</span>
<ul id="changelog-full">
   <li>Added Carpenters Chisel - used to carve patterns into Carpenters Blocks.</li>
   <li>Added mycelium overlay using a brown mushroom; however, cannot plant mushrooms on overlay (no control over this).</li>
   <li>Fixed bug in auto-cornering code for slopes and stairs.</li>
   <li>Added config option to loosen cover block restrictions - enabled by default.</li>
   <li>Wall gates and barriers will now extend to solid faces above them.</li>
   <li>Overlays now render during alpha pass to enable shading support.</li>
   <li>Configuration options added to control rendering overlays, patterns and dye colors on side covers.</li>
   <li>Textures tweaked.</li>
   <li>Block no longer needs to be covered to support plants - it only needs a grass overlay (thought I already did this...).</li>
   <li>Carpenters Hammer and Carpenters Chisel have 200 uses each, and are repairable.</li>
   <li>Top side cover depth adjusted slightly to eliminate z-fighting with pressures plates.</li>
   <li>Fancy fluids tweaked to correct fluid heights - TE restriction for fluids also put in place.</li>
   <li>Fixed Carpenters Hatch incorrectly determining solid sides of blocks.</li>
   <li>Fixed Carpenters Daylight Sensor collision bug.</li>
</ul>

<span id="label-stable">1.64</span>
<span id="label-generic">07/20/2013</span>
<ul id="changelog-full">
   <li>Sorted out Forge liquid dependency issues for MC 1.5+.</li>
   <li>Fixed block breaking animation being bugged for most blocks.</li>
   <li>Improved fluid side detection, and restricted Fancy Fluids to fancy graphics only.</li>
   <li>Fixed lighting anomalies with fancy fluids.</li>
   <li>Carpenters Block and Carpenters Stairs given more in-depth side render checks.</li>
</ul>

<span id="label-stable">1.63</span>
<span id="label-generic">07/18/2013</span>
<ul id="changelog-full">
   <li>[PRIOR HOTFIX] Side cover application moved server-side to prevent dupe bug.</li>
   <li>[PRIOR HOTFIX] Recipes made ore dictionary compatible.</li>
   <li>Block covers will now render separately in their respective render passes.</li>
   <li>Fancy fluids support added. Will only look correct if adjacent fluids are still (non-flowing).</li>
   <li>Fixed posts randomly generating while standing by a barrier.</li>
   <li>Barrier rendering code cleaned up and optimized.</li>
</ul>

<span id="label-stable">1.62</span>
<span id="label-generic">07/15/2013</span>
<ul id="changelog-full">
   <li>Fixed Carpenters Hatch throwing casting errors on placement.</li>
   <li>Altered slope recipe and quantity.</li>
   <li>Removed Carpenters Block recipe that used all sticks.</li>
   <li>Added adjustable recipe quantities in config file.</li>
   <li>Connecting redstone wire fix on Carpenters Block reverted. Fixes lighting issue with slabs.</li>
   <li>Fixed old bug affecting grass covers and coloration in fast lighting.</li>
</ul>

<span id="label-stable">1.61</span>
<span id="label-generic">07/14/2013</span>
<ul id="changelog-full">
   <li>Side covers now output their full light level.</li>
   <li>Fixed collision glitches with Carpenters Block when formed into vertical slabs.</li>
   <li>Cleaned up some unnecessary code.</li>
   <li>Fixed block not updating lighting when ejecting covers and side covers.</li>
</ul>

<span id="label-stable">1.6</span>
<span id="label-generic">07/13/2013</span>
<ul id="changelog-full">
   <li>Side covers added - full support on Carpenters Block and Stairs.</li>
   <li>Redstone now properly propagates through a full Carpenters Block.</li>
   <li>Redstone wires now connect properly on and around a full Carpenters Block.</li>
   <li>Added ability to dye and retrieve dye powders back from Carpenters Blocks.</li>
   <li>Right-click behavior on activatable blocks fixed 100%... I think.</li>
   <li>TE data extended, will automatically convert old data for you.</li>
   <li>Reverted fix for Railcraft-related casting crashes - was preventing blocks from ejecting on breakBlock.</li>
   <li>Added alternate recipe for Carpenters Block and adjusted quantities.</li>
   <li>Added Carpenters Hatch.</li>
   <li>Fixed bug where stairs would sometimes become invalid when cycling through types with the hammer.</li>
   <li>Z-fighting fix once again reverted. Will return eventually.</li>
   <li>More configuration options added to config file.</li>
   <li>Minor texture tweaks.</li>
</ul>

<span id="label-stable">1.53</span>
<span id="label-generic">07/04/2013</span>
<ul id="changelog-full">
   <li>Fixed Carpenters Block collision issues.</li>
   <li>Made Carpenters Daylight Sensor top texture use vanilla texture when uncovered.</li>
</ul>

<span id="label-stable">1.52</span>
<span id="label-generic">07/02/2013</span>
<ul id="changelog-full">
   <li>Added Carpenters Daylight Sensor block with adjustable polarity.</li>
   <li>Fixed item rendering appearance of buttons and pressure plates.</li>
   <li>Reorganized block initialization in config file to prevent self-blockID-conflicts with old configs.</li>
   <li>Altered many of the recipes and quantities.</li>
   <li>[HOTFIXED] Corrected some slope and stairs auto-transformation bugs.</li>
</ul>

<span id="label-stable">1.51</span>
<span id="label-generic">07/02/2013</span>
<ul id="changelog-full">
   <li>Pressure plates, levers and buttons now properly update neighboring blocks when changing polarity.</li>
   <li>Pressure plates no longer cycle on/off when entity remains on block.</li>
</ul>

<span id="label-stable">1.5</span>
<span id="label-generic">07/01/2013</span>
<ul id="changelog-full">
   <li>Added adjustable vanilla gate planks.</li>
   <li>Added picket fence gate.</li>
   <li>Added vertical plank fence gate.</li>
   <li>Added wall gate.</li>
   <li>Added Carpenters Lever with adjustable polarity.</li>
   <li>Added Carpenters Button with adjustable polarity.</li>
   <li>Added Carpenters Pressure Plate with adjustable polarity and trigger type.</li>
   <li>Fix for z-fighting tweaked and reimplemented, but still not 100%.</li>
   <li>Config file reorganized and cleaned up.</li>
   <li>Added hay overlay (vanilla MC 1.6 top texture included for MC 1.5 version).</li>
   <li>Barrier posts now only form at corners and intersections. Right click with hammer to force a post.</li>
</ul>

<span id="label-stable">1.44</span>
<span id="label-generic">06/22/2013</span>
<ul id="changelog-full">
   <li>Fixed broken stair transformation code.</li>
</ul>

<span id="label-stable">1.43</span>
<span id="label-generic">06/21/2013</span>
<ul id="changelog-full">
   <li>Added side-facing stairs (existing stairs will likely change).</li>
   <li>Fixed overlays and covers not ejecting from destroyed blocks under some circumstances.</li>
   <li>Improved ambient occlusion lighting for slopes.</li>
   <li>Reverted z-fighting fix, for now - was not working 100%.</li>
   <li>Fixed adjoining slope sides not rendering under certain circumstances.</li>
</ul>

<span id="label-stable">1.42</span>
<span id="label-generic">06/18/2013</span>
<ul id="changelog-full">
   <li>Fixed some more TE related crashes.</li>
   <li>Fixed gate incorrectly activating under certain conditions.</li>
</ul>

<span id="label-stable">1.41</span>
<span id="label-generic">06/17/2013</span>
<ul id="changelog-full">
   <li>Fixed collision bug with Carpenters Block in full and slab forms.</li>
   <li>Fixed sloped sides using wrong texture.</li>
   <li>Removed some forgotten debug messages.</li>
   <li>Fixed reported casting crashes.</li>
   <li>Ejected overlays and covers tweaked to work more like Jukebox when ejecting records.</li>
</ul>

<span id="label-stable">1.4</span>
<span id="label-generic">06/13/2013</span>
<ul id="changelog-full">
   <li>Grass sides now render on all block pieces, regardless of block size or max height.</li>
   <li>Stairs rewritten; will auto-corner and retain shape in the same manner as slopes.</li>
   <li>Overlays added. Cover any Carpenters Block with snow, grass, web, or vine.</li>
   <li>Fixed vanilla lighting bug for this mods blocks.</li>
   <li>Fixed vanilla texture offset/rotation bug for this mods blocks.</li>
   <li>Fixed casting crash and right click crash with gates.</li>
   <li>Rendering code cleaned up and optimized.</li>
   <li>Z-fighting fixed for all blocks.</li>
   <li>Added Carpenters Block (can be clicked with hammer to form slab).</li>
   <li>Blocks now inherit power output of cover block.</li>
   <li>Picket fence now extends to connect with solid block above.</li>
   <li>Gate right click behavior improved.</li>
   <li>Blocks support plants if soil cover can sustain them. Grass overlays are treated as grass.</li>
</ul>

<span id="label-stable">1.3</span>
<span id="label-generic">06/05/2013</span>
<ul id="changelog-full">
   <li>Mod name changed to Carpenters Blocks.</li>
   <li>All parts of mod made modular, cleaned up, and made more robust.</li>
   <li>Missing covers will no longer crash client; instead will discard cover data.</li>
   <li>Blocks now inherit cover explosion resistance, and other miscellaneous properties I ran across.</li>
   <li>Carpenters Stairs added.</li>
   <li>Carpenters Barrier added (fence, wall, etc).</li>
   <li>Carpenters Gate added.</li>
   <li>Added picket fence.</li>
   <li>Added vertical plank fence.</li>
   <li>Added adjustable vanilla fence planks.</li>
   <li>Light value of cover no longer saved in tile entity (minor memory savings).</li>
   <li>Creative tab added.</li>
   <li>Fixed slope sides not rendering under certain side-render checks.</li>
   <li>Fixed interior oblique corner slope collision boxes not generating fully.</li>
   <li>Added exterior oblique corner slope transformation code.</li>
</ul>

<span id="label-stable">1.25</span>
<span id="label-generic">05/26/2013</span>
<ul id="changelog-full">
   <li>Carpenters Hammer logic rewritten. See hammer image above or read "How To."</li>
   <li>Potential lighting bug on slope replacement or removal corrected.</li>
   <li>Double hit sound when left clicking a block with the Carpenters Hammer while in creative mode fixed.</li>
   <li>Slope hitbox precision is now configurable (to make slopes smoother). Oblique interiors are excluded.</li>
   <li>Slope placement logic has top/bottom bias to reduce accidental placement of side slopes.</li>
   <li>Compatibility with Optifine Custom Colors added.</li>
   <li>Slope will now inherit solidness from cover block (semi-works).</li>
   <li>Some more transform code added to easily build a stack of side slopes.</li>
   <li>Wedge shaped sides of slopes now do render checking (only visible faces will render).</li>
   <li>Fixed uncovered slopes becoming invisible behind ice blocks.</li>
</ul>

<span id="label-stable">1.24</span>
<span id="label-generic">05/17/2013</span>
<ul id="changelog-full">
   <li>More natural quadrant-based algorithm in place to determine what slope to create when right-clicking on a side face of a block.</li>
   <li>Render code clean-up.</li>
   <li>Auto-cornering rewritten and behaves much better overall.</li>
   <li>Carpenters Hammer now works in creative mode as intended.</li>
</ul>

<span id="label-stable">1.23</span>
<span id="label-generic">05/15/2013</span>
<ul id="changelog-full">
   <li>Slope auto-cornering altered to prevent accidental cornering when constructing rooftops.</li>
   <li>Slope light bug fixed. Was present in multiplayer when a client besides you covered a slope in glowstone or other light-emitting block.</li>
   <li>Four new slope recipes added, and old recipe removed; it now mimics the shape of the slope piece.</li>
</ul>

<span id="label-stable">1.22</span>
<span id="label-generic">05/10/2013</span>
<ul id="changelog-full">
   <li>Slope now inherits hardness, explosion resistance, flammability and fire spread speed from cover block.</li>
   <li>Hammer logic improved.</li>
   <li>Ambient occlusion for exterior oblique corners tweaked.</li>
   <li>Slope now renders as a slope in the inventory and player hand.</li>
   <li>Auto-assign ID feature removed. Better safe than sorry if problems occur.</li>
   <li>Ice added as a valid cover.</li>
   <li>Block breaking animation fixed.</li>
   <li>Full solid faces of slopes now support torches, redstone wire, etc (but not vine).</li>
   <li>Using Forge runtime deobfuscation now to support MC version 1.5+.</li>
</ul>

<span id="label-stable">1.21</span>
<span id="label-generic">05/08/2013</span>
<ul id="changelog-full">
   <li>Added item Carpenters Hammer. It replaces shift-click function to cycle through slope types.</li>
   <li>Added 18 new oblique corners. Make them by left-clicking a normal corner with the Carpenters Hammer.</li>
   <li>Added two pyramid pieces.</li>
   <li>Slope texturing hard coded to side texture except for positive slopes when covered with grass-type blocks.</li>
   <li>Removed log side texture config option.</li>
</ul>

<span id="label-stable">1.2</span>
<span id="label-generic">05/02/2013</span>
<ul id="changelog-full">
   <li>Updated for Minecraft 1.5.2.</li>
</ul>

<span id="label-stable">1.1</span>
<span id="label-generic">05/01/2013</span>
<ul id="changelog-full">
   <li>Render code rewritten to correct stretched textures on certain hardware.</li>
   <li>Bug in grass coloring on fast lighting fixed.</li>
</ul>

<span id="label-stable">1.0</span>
<span id="label-generic">04/29/2013</span>
<ul id="changelog-full">
   <li>Initial release.</li>
</ul>