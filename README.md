ElggVersChkUpgrader
===================

ElggVersionCheckerAndPlugInAutoUpgrader

Jusr preparing to fixup all my Elgg Version Checker code to :-

*    Allow verison compamtibility checking of PlugIns for particular Elgg versions
*    (Maybe) auto-upgrade PlugIns' code to an Elgg version.

Elgg currently doe =s not define 'derecated' code is a manner that can be easily 
used quick version in-compatibility or for auto-upgrades.. but there's always 
grammar parsing technilogy that can be used to analyse exisiting PHP code, 
highlight Elgg`ish APIcalls and such constructsand then --> do something about it..
hopefully *automatically. I expect some level of POHP grammar parsing, 
maybe some heavy usage of PHP's get tokens and Reflectins classes 
to help in the code analysis for the inevitable conclusions - 
easier PlugIns' code maintenance.. for Elgg -- the 2nd Love in My Life ;-oO

And with some crossed fingers, routines developed here will become useful 
also for my 'Easy PlugIn Development' ECML-styled Elgg code generator
which I have been blabbing about at my Blog' (Page) on the @E:Community ->
    http://community.elgg.org/pages/view/1077799/nextgen-theming-for-elgg

