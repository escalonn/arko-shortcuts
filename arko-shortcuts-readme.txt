#########################################
Keyboard Shortcuts for ARKOpack Interface
version 1.0
for ARKOpack Interface version 2015-02-07

Keyboard Shortcuts submod thread: https://forum.paradoxplaza.com/forum/index.php?threads/submod-keyboard-shortcuts-for-arkopack-interface.850867/
ARKOpack thread: https://forum.paradoxplaza.com/forum/index.php?threads/mod-arkopack-armoiries-interface.603251/
original Keyboard Shortcuts for vanilla CK2: https://forum.paradoxplaza.com/forum/index.php?threads/couple-minor-mods-keyboard-shortcuts-and-interface-adjust.672542/
http://www.arumba.tv/mods/

This submod contains no original content. It consists of versions of some
ARKOpack Interface files with Arumba’s keyboard shortcuts integrated into them.
The “Interface Adjust” portion of Arumba’s mod is also included. This submod is
not compatible with vanilla CK2 or with any HIP installation that lacks ARKOpack
Interface. For those, use Arumba’s original mod.

INSTALLATION INSTRUCTIONS:
1. Locate a HIP installation that includes a copy of the correct version of
   ARKOpack Interface. Check the version.txt file to verify the ARKOpack
   Interface version.
2. Extract archive into the HIP folder, overwriting all conflicting files.

USAGE:
See below for Arumba’s readme explaining the various keyboard shortcuts. (It is
more up-to-date than the readme currently distributed with the original mod.)

TROUBLESHOOTING:
If you have problems using this submod, delete your HIP folder and reinstall HIP
(with ARKOpack Interface). Then, reinstall this submod on top. If problems
persist, post in the submod’s thread.

CHANGELOG:
v1.0: Initial version for ARKOpack Interface version 2015-02-07 and
      Keyboard Shortcuts + Interface Adjust version 2014-12-16.

ARKOpack Interface, part of the Historical Immersion Project, is developed by
Arko. The original Keyboard Shortcuts + Interface Adjust mod is developed by
Arumba. This submod is maintained by IoannesBarbarus.

#########################################

Keyboard Shortcuts + Interface Adjust:
	Interface Adjust:  Adjusts the character selection GUI so that it does not overlap with the character interface.

	Keyboard Shortcuts: This adds 10 shortcuts to the game: "z","x","c","v","b","n",",",".","/","l"

z raises levy directly from any county you have control over
z also toggles siege interface while selecting a province or army in an enemy province.
z also sends units to the left side of an army or ship balancing screen, each press sends the bottom listed unit left. press and hold for rapid rebalancing
z will 'cancel' or 'go to' on event windows (such as disband troops, or after a siege/battle has completed)
z will go to the previous holding in demesne

x dismisses the currently selected levy (army or ship), *capital* "x" will dismiss ALL selected levies or ships

c raises ships directly from any county you have control over
c assaults holdings when you have an army/county is selected that allows for assaulting
c Confirms diplomacy interactions, and will 'ok' event windows (such as disband troops)

v embarks the currently selected levy into a ship that is IN port in that province
v also selects all armies inside boats if a ship is selected
v also will close one army at a time while having multiple armies selected. The two previously mentioned shortcuts take priorty. This shortcut is ideal for raiding with multiple armies as a viking. (v selects armies, right click all onto a county, press v, right click onto another county, repeat.)
v will create a new vassal from the holding screen of minor owned baronies

If you have a single army/shipgroup the "b" key will open the new unit interface (ship/army rebalancing)
b also sends units to the right side of an army or ship balancing screen, each press sends the bottom listed unit right. press and hold for rapid rebalancing
b will go to the next holding in demesne
b is also back button for the main interfaces

n merges selected levies or ships if you have multiple armies selected, so long as they are in the same zone or province (naturally.) 
n is bound to the 'split army/navy' button if you have a single army or navy selected

l toggles looter status for pagan armies

, opens the ledger, and closes the ledger

. opens the find characters interface, and also closes it

/ opens the find title interface

################################################################################
To manually alter keybindings, download notepad++ from www.ninite.com and install
use notepad++ to 'search in files', select the mod folder as the directory
search for: Shortcut = "
(leave the quotations open)
this will pull up all the shortcuts listed in the mod files.
doubleclick on the bottom of the screen through each of the results until you see the "guiButtonType =	{" that looks like what you want.
you can alter or remove any of the options that say "shortcut = "x"" to your liking
There is some trial and error to this if you are not experienced with the layout of the game files.  Just play with it, you'll figure it out.
################################################################################
