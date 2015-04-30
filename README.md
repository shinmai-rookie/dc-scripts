# dc-scripts
My humble attempts at writing scripts for the UNIX dc (desktop calculator).
In each of them there is a description of the algorithm I used (in human-readable form), a list of the registers I needed, the macros I defined as well as the literal strings that are shown to the user.

To try these scripts, first run "dc --version" in a terminal of your choice. If the command was not found, install it. (I used the version "dc (GNU bc 1.06.95) 1.3.95", though I avoided any feature explicitly stated as a GNU extension, so it should work with other implementations.) Then, run "dc $FILE", changing $FILE with the script you want to run, or give that script execution rights and execute it as an ordinary program.
