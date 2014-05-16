CerbAMegaPetier
===============

A repository for me to keep track of my specific configuration for Repetier Firmware for my Cerberus Mega!

Method: Copy contents of "Repetier" folder into "Repetier" folder of Repetier firmware at the same commit previously used as base... ensure there are only differences specific to the Cerberus.

then fetch and merge remotes from Repetier.

Once all conflicts are satisfied, and the firmware has been tested on our mega, bring everything over here and commit it.

If a problem comes up, it's always possible to go back to repetier's repo, and track down the bug that way.

NOTE: the changes to our custom files should not need to be included in each commit.  IOW each commit is related to changes made to the repetier firmware, and the customized file changes should be minimal

However if there are changes to configuration.h, and pins.h, these generally should be checked in separately.  