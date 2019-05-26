
## Overview

Shield Tracker is a World of Warcraft addon to track shields on yourself, NPCs, players, or pets.

## What's New

* Updated for 7.0.
* Added configurable labels for bars.
* Vengeance was removed. You should delete any bars with Vengeance tracking.

## Description

Shield Tracker allows you to create highly-configurable bars to track shields / absorbs on:

* You
* Your target
* Your focus
* Your mouseover
* Your pet
* Named players in your group.

There are three modes for each bar. Select which one you prefer under the "Absorbs Tracked" tab.

* **All** uses Blizzard's API call that provides the total of every absorb on the unit.
* **Selected** only adds up the shields that you select.
* **Excluding** will get the total absorbs on that unit via Blizzard's API and then subtract the selected absorb types.

You will need to create the bars in the settings. You can access them by typing ```/shieldtracker``` or ```/stracker```. You can also access them via the game menu. Press Esc to bring up the game menu, select Interface, select the AddOns tab, then select Shield Tracker. Once you have Shield Tracker's options up, select Bar. Enter a name in the Create Bar field and press Ok. You can then configure that bar.

There is a default font but you can configure the font per bar.

## Known Issues

Tracking the shields on a named player only works properly if you are in a group with that player. It's a limitation of the game client.
It is best to reload the UI after renaming a bar.

If you find any bugs or issues, please file a ticket or send me a PM.

The ticket tracker is at: http:www.wowace.com/addons/shield-tracker/tickets/
