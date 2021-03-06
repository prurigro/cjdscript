# cjdscript #

## ABOUT ##

A script to deploy and run the collection of working tools included with [cjdns](https://github.com/cjdelisle/cjdns).

## REQUIREMENTS ##

### Needed ###

* `Bash`: Required to execute the **cjdscript** script
* `Git`: Required to clone the **cjdns** repo

### Recommended ###

* `GCC`: Required to compile binaries
* `Python 2`: Required to setup/run **Python 2** scripts and compile binaries
* `Ncurses`: Required to pretty-print the list of active scripts
* `Node.js`: Required to setup/run **Node.js** scripts and compile binaries
* `Wget`: Required to download **Python 2** libraries
* `CMake`: Required to build the **Python 2** library **PySide**
* `QT4`: Required for the **Python 2** library **PySide**
* `PyGTK`: Required for the **Python 2** library **matplotlib**

## USAGE ##

* `-u` | `--update`: update the configuration
* `-v` | `--verbose`: update with verbose output
* `-l` | `--list`: display a list of available scripts
* `-h` | `--help`: show the help dialog

**Note**: Issues may be possible to resolve by running `cjdscript -u` or deleting _~/.cjdscript_.

## CREDITS ##

Written by Kevin MacMartin:

* [GitHub Projects](https://github.com/prurigro)
* [Arch Linux AUR Packages](https://aur.archlinux.org/packages/?SeB=m&K=prurigro)

## LICENSE ##

This script is open source and licensed under the [GPLv3](http://www.gnu.org/copyleft/gpl.html).
