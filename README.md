This is a dumping ground for Akaros-compatible devices and other files that do
not belong in the Akaros tree, usually for license reasons.

Many of the files in this repo are incompatible with the GPL.  If you link any
of these files with the Akaros kernel, you may not redistribute the resulting
binary.

You can build and link these devices with Akaros by exporting the location of
this directory and running make from the main repo.

	$ export AKAROS_EXTERNAL_DIRS="/path/to/this/repo"
	$ make

If this repo does not build with the latest Akaros kernel, please let us know
in either #akaros on freenode, or the mailing list:
	https://www.google.com/search?q=akaros+mailing+list
