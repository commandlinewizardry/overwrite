# overwrite
Utility for overwriting the source file of a Linux command pipeline.

Usage: [some commands...] | ow [FILENAME]

Takes in a stream and outputs it to FILENAME. Designed to
redirect the output of a command pipeline and overwrite 
the original source file.

Usage Example:
cut -f2 inputfile.txt | ow inputfile.txt

Command Line Wizardry
https://www.commandlinewizardry.com