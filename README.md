ElggVersChkUpgrader
===================

ElggVersionCheckerAndPlugInAutoUpgrader

Jusr preparing to fix-up for all my Elgg Version Checker code to :-

*    Allow version (in)compatibility checking of PlugIns @ particular Elgg versions
*    (Maybe) auto-upgrade PlugIns' code to an Elgg version.

Elgg currently does not define 'deprecated' code in a manner that can be easily 
used quickly for version (in)compatibilities or for auto-code-upgrades.. 
but there's always grammar parsing technilogy that can be used to analyse 
existing PHP code, highlight Elgg`ish APIcalls and such constructs and then
--> do something about it.. hopefully *automatically. 

I expect some level of PHP grammar parsing, maybe some heavy usage of PHP's 
get tokens and Reflections classes to help in the code analysis for the 
inevitable conclusions - 
.. easier PlugIns' code maintenance.. for Elgg - #2 TrueLove @My Life ;-oO

And with a few fingers crossed, routines developed here will also become
useful for my 'Easy PlugIn Development' ECML-styled Elgg code generator
which I have been blabbing about at my Blog' (Page) on the @E`Community ->
    http://community.elgg.org/pages/view/1077799/nextgen-theming-for-elgg

