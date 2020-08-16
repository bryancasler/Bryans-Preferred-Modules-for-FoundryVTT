<!-- + Bryan's Preferred FoundryVTT Modules + -->


<img src="https://raw.githubusercontent.com/bryancasler/Bryans-Preferred-Modules-For-FoundryVTT/master/assets/Bryan's%20Preferred%20Modules%20for%20Foundry%20VTT%20-%20Full%20-%20Social%20-%20On%20Dark.png" width="0" height="0">

![Bryan's Preferred FoundryVTT Modules](https://raw.githubusercontent.com/bryancasler/Bryans-Preferred-Modules-For-FoundryVTT/master/assets/Bryan's%20Preferred%20Modules%20for%20Foundry%20VTT%20-%20Title%20-%20On%20White.png)

My personally cultivated list of FoundryVTT Modules that play nicely together without creating an overwhelming amount of UI options or causing noticeable FPS drops; not everyone has a new computer. Collectively they set up a solid foundation for any D&D 5e and Pathfinder 2e campaign.

## Core Settings
- Configure Audio / Video > Audio / Video Conference Mode: Disabled
  - Even having this enabled and not using it will cause idle FPS to drop 30-50%. Use Discord for now.

## Quality of Life Improvements For Everyone
- [Chat Images](https://github.com/bmarian/chat-images) - Copy and Paste, Drag and Drop images into chat.
  - Need to check to see if this Module inserts images as base64 encoded data. If so, this could cause large base64 encoded images to be inserted (e.g. 24mb) every time a chat message is posted. Whereas normal images will be resized, compressed, and cached by the browser. It's possible this behavior could have been resolved or caused by another Module. - Flagged by an Anonymous user on The Forge Discord
- [Cursor Zoom](https://gitlab.com/foundry-azzurite/cursor-hider) - Mouse scroll zooming will center around the cursor instead of around the center of the screen.
- [Deselection](https://github.com/Sky-Captain-13/foundry/tree/master/deselection) - Allows you to deselect a token or tokens by clicking any empty spot on the map.
- [Dice So Nice](https://gitlab.com/riccisi/foundryvtt-dice-so-nice) - Adds the ability to show a 3D dice simulation when a roll is made.
  - Hide FX: None
  - Sound Effects: Off
  - Shadows Quality: Off
  - Advanced Lighting: Off
  - Animation Speed: 2x
- [Dice Tray](https://gitlab.com/asacolips-projects/foundry-mods/foundry-vtt-dice-calculator) - Adds a Dice Tray below the chat.
- [Health Estimate](https://gitlab.com/tsuki.no.mai/healthestimate) - Shows estimated health level of an enemy on mouseover.
  - GM Only: On
- [Less Fog](https://github.com/trdischat/lessfog) - Tweaks fog of war visibility for GM and Players.
- [PopOut!](https://github.com/kakaroto/fvtt-module-popout) - Lets you pop out actor sheets and journal entries into their own windows.
- [Popout Resizer](https://github.com/Cardagon/popout-resizer) - Give the users the ability to resize their pop-out windows from the side toolbar.
- [Search Anywhere](https://gitlab.com/riccisi/foundryvtt-search-anywhere) - Press CTRL+Space to quickly search for any entity by name via a handy auto-complete widget.
- [Show Drag Distance](https://github.com/wsaunders1014/showdragdistance) - Shows distance you've dragged the token as if you used the Ruler tool.
- [Vance's Sidebar Resizer](https://github.com/VanceCole/vance-sidebar-resizer) - Allows the sidebar to be resized.
  - Aug 15th: Broken until [this issue](https://github.com/VanceCole/vance-sidebar-resizer/pull/1) is resolved.

## Quality of Life Improvements For GameMasters
- [Actually Private Rolls](https://github.com/syl3r86/Actually-Private-Rolls) - Hides Private GM Rolls completely rather than just obfuscating the result. This can be toggled on or off in the Settings Menu.
- [Easy Target](https://bitbucket.org/Fyorl/easy-target/) - Toggles the targeting tool while holding alt. Also allows for alt+clicking inside an AoE to target all tokens within that AoE. Holding alt while placing a template will also target all tokens within that template when placed.
- [Follow Me](https://github.com/Brunhine/FollowMe) - Allows tokens to follow other tokens.
- [GM Scene Background](https://github.com/death-save/gm-bg) - Allows GMs to set a GM-only background image.
- [GM Token-Drag Visibility](https://github.com/SteffanPoulsen/token-drag-visibility) - Module that disables the vision limitation when dragging a token as a GM. Useful for moving players between floors on the same map.
- [Group Roll Checks and Saves](https://github.com/trdischat/grouproll) - Facilitates D&D 5e and Pathfinder 2e Group Rolls.
- [The Furnace](https://github.com/kakaroto/fvtt-module-furnace) - Provides a number of enhancements.
  - Advanced Macros: Off
  - Advanced Drawing Tools: Off
  - Improve the Playlists UI: Off
- [Tidy UI - Game Settings](https://github.com/sdenec/tidy-ui_game-settings) - A module to make the game settings menu a bit more comfortable to use.
- [Token Info Icons](https://github.com/jopeek/fvtt-token-info-icons) - Displays Speed, AC, and Passive Perception on Tokens for the GM.
- [Virtual Tabletop Assets - Iconizer](https://www.vttassets.com/assets/vtta-iconizer) - Whenever an item is created or updated, Iconizer looks up its name in its dictionaries. If it finds an entry, he will use the icon references there to update the image of that item.
- [Virtual Tabletop Assets - Party Overview](https://www.vttassets.com/assets/vtta-party) - Adds a party overview window, granting you information about some vital stats quickly and without hassle.
  - Grant Players access to the overview?: Off
  - Enable tooltips?: Off
- [Virtual Tabletop Assets - Tokenizer](https://www.vttassets.com/assets/vtta-tokenizer) - A tool to help generate token “token” images and their avatars.

## General Ambiance
- [Ambient Doors](https://github.com/EndlesNights/ambientdoors) - Customized sounds effects that trigger for all users when interacting with doors.
- [Dancing Lights](https://github.com/BlitzKraig/fvtt-DancingLights) - Ambient Light & Token Light toolkit
- [Maestro](https://github.com/death-save/maestro) - Adds player hype tracks, item tracks, combat tracks, and more.
  - Enable Hype Track: On
  - Enable Combat Track: On
  - Create Combat Tracks Playlist: On
  - Disable Dice Sounds: On
  - Enable Critical Success / Failure Tracks
- [Music Assistant](https://github.com/temportalflux/MusicAssist) - Adds support for youtube tracks in audio playlists.

## Combat
- [Combat Enhancements](https://gitlab.com/asacolips-projects/foundry-mods/combat-enhancements) - Improved initiatives tab with health tracking and drag and drop reordering.
- [Combat Ready!](https://github.com/smilligan93/combatready) - Shows a graphic + sound for players a round just before a player's turn (Next Up) and during their turn.
  - Disable ‘Next Up’ notification: Off
  - Disable Timer: On
  - Show End Turn Dialog: On
  - Ticking Sound: Off
  
## Dungeon and Dragons 5e (D&D 5e) Specific
- TBD

## Pathfinder 2e (P2E) Specific
- [Pathfinder 2e Quick Rolls](https://gitlab.com/mcarthur.alford/pf2qr) - Adds features to speed up rolling in chat.
- [Pathfinder Ui](https://gitlab.com/sasmira/pathfinder-ui) - Theme for Pathfinder 1e and 2e.
- [PF2e GM Screen](https://gitlab.com/atakanaltiner6/pf2e-gm-screen/) - A GM Screen for PF2e Game System.



## Under Consideration
- [Token Bar](https://github.com/Kekilla0/TokenBar) - D&D 5e Only. It populates an action bar for the token you have selected.
- [Better Rolls for 5e](https://foundryvtt.com/packages/betterrolls5e/) - Overhauls most rolls on the 5th edition character sheet, and provides a way to customize roll messages per-item.
- [Community Tables](https://foundryvtt.com/packages/foundry_community_tables/) - A collection of Tables added by the FoundryVTT Community.
- [Encounter Builder for 5e](https://foundryvtt.com/packages/encounter-builder-5e/) - D&D 5e Only. Aid in building D&D5E combat encounters.
- [Easy Target](https://foundryvtt.com/packages/easy-target/) - Target tokens while on any layer with Alt+Click. Target all tokens in an AoE while on any layer by Alt+Clicking inside its area. Clear all targets with Alt+Shift+C.
- [Mess - Moerills enhancing super-suit(e)](https://github.com/Moerill/mess) - Many features, possible compatibility issues.
- [Chat Portrait](https://foundryvtt.com/packages/ChatPortrait/) - Show Actor’s portrait in chat.
- [Tidy 5e Sheet](https://github.com/sdenec/tidy5e-sheet) - D&D 5e Only. An alternative Character Sheet
- [Compendium Browser](https://foundryvtt.com/packages/compendium-browser/) - Easily browse and filter spells as well as NPCs loaded from the compendium.
- [GM Notes](https://foundryvtt.com/packages/gm-notes/) - Add GM-Only notes to entities (Actor, Items (including owned items), RollTable, and JournalEntry).
- [Trigger Happy](https://foundryvtt.com/packages/trigger-happy/) - Create triggers for your players to spring traps or anything you can think of.
- [FXMaster](https://gitlab.com/mesfoliesludiques/foundryvtt-fxmaster) - Adds various special effects.
- [Grid Scaler](https://github.com/UberV/scaleGrid) - Adds tool to help to set the Foundry grid on the background image
- [Expander](https://github.com/Sky-Captain-13/foundry/tree/master/expander) - Expands the chat window when you click on the chat icon instead of only by clicking on the arrow at the bottom
- Darker Vision for 5e - Suggested by LorduFreeman on The Foundry Discord
- Group Initiative - Suggested by LorduFreeman on The Foundry Discord
- Quick Insert - Suggested by LorduFreeman on The Foundry Discord
- Permission Viewer - Suggested by KaKaRoTo on The Forge Discord
- [DNDBeyond Character Sheet](https://foundryvtt.com/packages/dndbeyond-character-sheet/) - Replacement of a character sheet with a version more similar in style to that of D&D Beyond's.
- [Token Health](https://github.com/tonifisler/foundry-token-health) - Apply damage/healing to all selected tokens.
- [Loot Sheet NPC 5E](https://github.com/jopeek/fvtt-loot-sheet-npc-5e) - Adds an additional NPC sheet which can be used for loot containers such as chests.
- [Foundry VTT Macros Repository](https://github.com/foundry-vtt-community/macros) - Foundry community-contributed macros.
- [Foundry VTT Tables Repository](https://github.com/foundry-vtt-community/tables) - Foundry community-contributed tables.
- [Forien's Unidentified Items](https://github.com/Forien/foundryvtt-forien-unidentified-items) - Handle unidentified items and their identification.

## Retired Modules
These modules are no longer used as they’ve become redundant to features provided by other modules, or they caused other issues (e.g. lag).
- [Turn Alert](https://github.com/schultzcole/FVTT-Turn-Alert) - Set alerts to trigger on a particular round of combat or on a particular token's turn. - Retired 2020 Aug 09 - Turn altering is handled by Combat Ready
- [Turn Marker](https://github.com/Brunhine/TurnMarker) - Adds an image under a token who is currently active in the combat tracker. - Retired 2020 Aug 09 - Turn marking is handled by Combat Ready
- [Token Mold](https://github.com/Moerill/token-mold) - For minting tokens that auto append a counter or descriptor to the tokens name. Also can handle automatic token scaling. - Retired 2020 Aug 09 - Great concept but limited utility at the moment. Retiring to reduce UI clutter, will revisit in the future.

## Free Map-Pack Resources
Not tested, shared for ease of reference.
- [Forgotten Adventures](https://www.forgotten-adventures.net/live-gallery/)
- [Fantastic Maps](http://www.fantasticmaps.com/free-stuff/)

## Free Tokens Resources
Not tested, shared for ease of reference.
- [Forgotten Adventures](https://www.forgotten-adventures.net/live-gallery/)
- [Devin Nights Token Packs 1-20](https://immortalnights.com/tokensite/?product=all-free-tokens-in-one-file)

## Free Sound and Music Resources
Not tested, shared for ease of reference.
- [Gameaudio GDC Bundle](https://foundry-vtt-community.github.io/wiki/Community-Media/#gameaudiogdc-bundle)

## Free Icon Resources
Not tested, shared for ease of reference.
- [Game-icons.net](https://foundry-vtt-community.github.io/wiki/Community-Media/#game-iconsnet)
- [Bundle WOW-Icons](https://foundry-vtt-community.github.io/wiki/Community-Media/#bundle-wow-icons)

## Creators
Not endoring, shared for ease of reference.
- [2-Minute Tabletop - Patreon](https://www.patreon.com/2minutetabletop)
- [Afternoonmaps - Patreon](https://www.patreon.com/afternoonmaps/posts)
- [Caeora - Patreon](https://www.patreon.com/caeora)
- [Cze and Peku - Patreon](https://www.patreon.com/czepeku/posts)
- [Dungeon Mapster - Patreon](https://www.patreon.com/dungeonmapster/posts)
- [Eightfold - Patreon](https://www.patreon.com/EightfoldPaper/posts)
- [Forgotten Adventures - Patreon](https://www.patreon.com/forgottenadventures)
- [Gabriel Pickard - Roll20](https://marketplace.roll20.net/browse/publisher/64/gabriel-pickard)
- [Heroic Maps - Patreon](https://www.patreon.com/heroicmaps/posts)
- [Jesper Nilsson Cyren - Patreon](https://www.patreon.com/CyrensMaps/posts)
- [Maphammer - Patreon](https://www.patreon.com/maphammer/posts)
- [Neutral Party - Patreon](https://www.patreon.com/neutralparty/posts)
- [PogS Props - Patreon](https://www.patreon.com/PogS_Props)
- [The Drafting Table - Patreon](https://www.patreon.com/draftingtable)
- [Animated Dungeon Maps - Patreon](https://www.patreon.com/animatedmaps/posts)
- [Dynamic Dungeons - Patreon](https://www.patreon.com/dynamicdungeons/overview)
- [Living Realms - Patreon](https://www.patreon.com/LivingRealms/posts)
- [Adventure Music - Patreon](https://www.patreon.com/adventuremusicjr)
- [Michael Ghelfi - Patreon](https://www.patreon.com/MichaelGhelfi)
- [Music d20 - Patreon](https://www.patreon.com/musicd20)
- [Sword Coast Soundscapes - Patreon](https://www.patreon.com/swordcoastsoundscapes)
- [Vindsvept - Patreon](https://www.patreon.com/Vindsvept)

## Miscellaneous Resources
- [Module usage statistics from The Forge - July 2020](https://i.imgur.com/xRVVed1.png)
- [Official FoundryVTT Sub-Reddit Module Wiki](https://www.reddit.com/r/FoundryVTT/wiki/index/modules)
- [Foundry VTT Community](https://foundry-vtt-community.github.io/)
