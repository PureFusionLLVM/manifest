PureFusionLLVM Manifest
===========

Release: Current Latest UnReleased:
===============
[Current Beta is V7.x]

Note:

No mater what manifest release version you synce up with:
you can use ./build.sh [arg1] [arg2]

[arg1] Can be 5, 6 ,7 or master if left blank
[arg2] can be left empty but that assigns version to final Directory Name:


Sync Sources by using the following commands

    $ repo init -u https://github.com/PureFusionLLVM/manifest.git -b master
	
	Then:

    $ repo sync -f -j8 --force-sync --no-clone-bundle --no-tags

    ./build.sh master [opt]
    ./build.sh 7 7 [opt] # Will build from master at this time
    ./build.sh 6 6 [opt] # Will build version 6
    ./build.sh 5 5 [opt] # Will build version 5
