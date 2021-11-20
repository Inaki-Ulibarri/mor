#mor, a shitty more copy

##Warnings!
* This program is to _never_ be used by _anyone_ under _any circumstance_
* If the program is exited using ^C or ^Z, you're at risk of leaving your terminal in Canonical mode with no echo set , that will be fun to fix.
* A patch for this is on the way

##Usage
mor [options] <files>
	h	show this text
	l	# of lines to show at a time,
	        default is 25
Commands
	q	quit
	
* This is a copy of more from the linux-utils
* The program will print a set number of lines form a text file into stdout
	- The default is 25 lines, but this can be changed by the user using the -l option