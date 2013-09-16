cjdscript
========

About: This script maintains and executes the collection of (working) scripts included with cjdns

Requirements: This script requires git and the collection of coreutils, and the scripts you can run using it require a running copy of cjdns

Usage:
    1. Install the dependancies required for the desired scripts (currently 'bash' and 'python2' scripts are included)
    2. Run cjdscript without any arguments to run some initial setup functions
    3. Run 'cjdscript -h' for a list of available commands and scripts you can now run
    4. Run 'cjdscript -u' to update the scripts and recheck them against local deps

Note: The default directory for cjdscript is ~/.cjdscript; feel free to blow this directory away and start over if you run into issues
