Baleful plugin
==============
This repository contains a baleful plugins for radare2.

Baleful was a challenge relased in picoctf.

* The asm plugin is completed.

* The anal plugin is in developed status.

Related Documentation
==============
* http://lolcathost.org/b/BalefulRadare_EN_part_1of2.pdf

	English writeup and plugin implementation

* http://lolcathost.org/b/BalefulRadare_ES_parte_1de2.pdf
	
	Spanish writeup and plugin implementation

Directories
===========

* asm/

	Contains the asm plugin

* anal/

	Contains the anal plugin.      

* bin/

	Contains binary un-upx code and vm code.

Building
--------

Just type `make`.

Installation
------------

Running `make install`. will put those shared libraries in your
HOME's directory.
