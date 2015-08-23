#########################################
Keyboard Shortcuts for ARKOpack Interface
version 1.0.1 (SWMH)
for ARKOpack Interface version 2015-08-15
and SWMH v2.9 - 2015-08-15

Keyboard Shortcuts submod thread: https://forum.paradoxplaza.com/forum/index.php?threads/submod-keyboard-shortcuts-for-arkopack-interface.850867/
ARKOpack thread: https://forum.paradoxplaza.com/forum/index.php?threads/mod-arkopack-armoiries-interface.603251/
original Keyboard Shortcuts for vanilla CK2: https://forum.paradoxplaza.com/forum/index.php?threads/couple-minor-mods-keyboard-shortcuts-and-interface-adjust.672542/
http://www.arumba.tv/mods/

This submod contains no original content. It consists of versions of some
ARKOpack Interface files with Arumba’s keyboard shortcuts integrated into them.
The “Interface Adjust” portion of Arumba’s mod is also included. This submod is
not compatible with vanilla CK2 or with any HIP installation that lacks
ARKOpack Interface. For those, use Arumba’s original mod.

INSTALLATION INSTRUCTIONS:
1. Locate a HIP installation that includes a copy of the correct version of
   ARKOpack Interface. Check the version.txt file to verify the ARKOpack
   Interface version.
2. Ensure the correct version of SWMH is installed.
3. The .zip archive contains one folder, named “arko-shortcuts-<version>”.
   Extract the contents of that folder into HIP’s install folder (e.g.
   “mod/Historical Immersion Project”), overwriting all conflicting files.

USAGE:
See below for an updated version of Arumba’s readme explaining the various
keyboard shortcuts. Most of those shortcuts have been added to vanilla in 2.4.
But Arumba’s mod is still necessary for these items:

z will 'cancel' or 'go to' on event windows (such as disband troops, or after a siege/battle has completed)
z will go to the previous holding in demesne
c Confirms diplomacy interactions, and will 'ok' event windows (such as disband troops)
v will create a new vassal from the holding screen of minor owned baronies
b will go to the next holding in demesne
s is bound to the 'split navy' button if you have a single navy selected
/ opens the find title interface

Note that n no longer merges or splits units, and z and b no longer rebalance
them.

TROUBLESHOOTING:
If you have problems using this submod, delete your HIP folder and reinstall
HIP (with ARKOpack Interface). Then, reinstall this submod on top. If problems
persist, post in the submod’s thread.

CHANGELOG:
v1.0.1: Compatch for ARKOpack Interface version 2015-08-15 and
        Keyboard Shortcuts + Interface Adjust version 2015-08-13.
v1.0.0: Initial version for ARKOpack Interface version 2015-02-07 and
        Keyboard Shortcuts + Interface Adjust version 2014-12-16.

ARKOpack Interface, part of the Historical Immersion Project, is developed by
Arko. The original Keyboard Shortcuts + Interface Adjust mod is developed by
Arumba. This submod is maintained by IoannesBarbarus.

#########################################

Interface Adjust:  Adjusts the character selection GUI so that it does not overlap with the character interface.

Keyboard Shortcuts:

z raises levy directly from any county you have control over
z also toggles siege interface while selecting a province or army in an enemy province.
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
b will go to the next holding in demesne
b is also back button for the main interfaces

g merges selected levies or ships if you have multiple armies selected, so long as they are in the same zone or province (naturally.)

s is bound to the 'split army/navy' button if you have a single army or navy selected

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
