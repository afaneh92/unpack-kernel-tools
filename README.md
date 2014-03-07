This is an update version of the script found at 
http://forum.xda-developers.com/wiki/index.php?title=Extract_initramfs_from_zImage

The problem with that script is that the gzip magic number occasionally occur 
naturally, meaning that some non-compressed files get uncompressed.

#If your had lzma and un unlzma issue just do thius steps
-In terminal type gksu nautilus.
-If gksu not installed just type sudo apt-get install gksu, then back to step above.
-copy "xz" and "lzmainfo" them to /usr/bin/ don't forget to rename your original "xz" and "lzmainfo" first (for backup).
