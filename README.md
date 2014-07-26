This is an update version of the script found at 
http://forum.xda-developers.com/wiki/index.php?title=Extract_initramfs_from_zImage

The problem with that script is that the gzip magic number occasionally occur 
naturally, meaning that some non-compressed files get uncompressed.

#If your had lzma and un unlzma issue just do this steps

-In terminal type "sudo gksu nautilus".

-If gksu not installed just type "sudo apt-get install gksu", then back to step above.

-in folder /usr/bin/ don't forget to rename your original "xz" (for backup).

-copy "xz" to /usr/bin/ .


#how to use

-just type ./unpack.sh boot.img or ./unpack.sh zImage
