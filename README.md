PureFusionLLVM Manifest
===========

Release: Current Latest UnReleased:
===============

Sync Sources by using the following commands

    $ repo init -u https://github.com/PureFusionLLVM/manifest.git -b master-crosscompile
	
	Then:

    $ repo sync -f -j8 --force-sync --no-clone-bundle --no-tags

    ./build.sh [opt]

	
NOTE: master-crosscompile creates a chain thats geared towards crosscompiling to Android Only: