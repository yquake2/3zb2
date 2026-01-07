# 3rd Zigock Bot II for Yamagi Quake II

This is a best effort port of the  3rd Zigock Bot II to Yamagi Quake II. 
The code is nearly unchanged from the original, just some scary compiler
warning were fixes and some hard coded pathes were changed to make use
of Yamagi Quake IIs enhanced, unix compatible VFS.

## Installation

* Copy *misc/pak10.pak* to the 3zb2/ dir.
* Build the game.so by calling `make` and copy it to the 3zb2/ dir.

## Run the game
* Example command: ./quake2 +set game 3zb2 +map q2dm1
* Open the console (the ~ key) and type: sv spb x. Where x is the number of bots you want to spawn.

For more informations refer to the user guide in *misc/User Guide*.

