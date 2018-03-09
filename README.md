
Scprint = scp + lpr
===================

_A simple Bash script for remote printing_

The script saves the file(s) to be printed on the server via `scp` 
and runs printing from there using `lpr`.

Works best with passwordless authentication (e.g. `ssh-agent`).

Installation
------------

1. Save the [scprint](https://raw.githubusercontent.com/tuetschek/scprint/master/scprint) file to your `~/bin/` (or anywhere in your `PATH`).

2. Edit the file to update your server, preferred printer name, user name etc.

3. Make it executable (`chmod +x ~/bin/scprint`).


Usage
-----

The default is just `scprint file.pdf`. Run `scprint` without parameters to see all options.
