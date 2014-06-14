# cjdscript #

## About ##

This script maintains and executes the collection of (working) tools included in the [cjdns repo](https://github.com/cjdelisle/cjdns).

## Requirements ##

### Needed ###

* Bash
* Unix core utils (grep, sed, etc.)

### Optional (Required for some scripts) ###

* The ~/.cjdnsadmin file configured (for scripts that access certain admin features)
* GCC (to compile binaries)
* Python 2 (for python scripts and to compile binaries)
* Node.js (for node.js scripts and to compile binaries)

## Usage ##

1. Install the dependancies required for the desired scripts (currently 'bash' and 'python2' scripts are included)
2. Run cjdscript without any arguments to run some initial setup functions
3. Run `cjdscript -h` for a list of available commands and scripts you can now run
4. Run `cjdscript -u` to update the scripts and recheck them against local deps

**Note**: The default directory for cjdscript is ~/.cjdscript; feel free to blow this directory away and start over if you run into issues.

## Credits ##

Written by Kevin MacMartin: [GitHub Projects](https://github.com/prurigro?tab=repositories) | [Arch Linux AUR Packages](https://aur.archlinux.org/packages/?SeB=m&K=prurigro)

## License ##

This script is open source and licensed under the [GPLv3](http://www.gnu.org/copyleft/gpl.html).
