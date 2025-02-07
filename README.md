While this repository is named "bash-scripts", they are not all intended to run under bash; they are some bash *or sh-family* scripts I've written over the years. Almost all of these scripts were *not* written for use by the general public in mind; most were developed solely for my personal use. 

Therefore,
**THESE SCRIPTS ARE PROVIDED AS-IS, WITH NO WARRANTY OR MERCHANTABILITY. NO GUARANTEE IS MADE THAT ANY SCRIPT WILL FUNCTION AS INTENDED ON ANY SYSTEM.**

That is to say: they do function as designed *on my own systems*, but they might not on yours; use them at your own risk. While these scripts are executable programs, they consist of human-readable code. You should check *any* script you intend to run before attempting execution.

Obviously, I cannot ensure compatibility with everything that has a sh-family shell — or even particular versions of a specified shell. Similarly, if a script is designed for a particular flavor of sh (e.g. bash), I cannot and do not guarantee compatibility with another (e.g. dash, ash, ksh, csh, zsh, fish, etc.).

Scripts designed to run under the Bourne Shell (i.e. the file begins with the hashbang ``#!/bin/sh``) should have the broadest compatibility, and will have been tested under multiple environments. Still, no guarantees are made that they will properly execute. While compatibility-related bug reports are welcome, please do not complain that a script will not run on the SVR4 box you found whilst dumpster diving, or on your IoT light bulb. With a few exceptions, these scripts are intended to run on modern(-ish) computing devices under modern(-ish) operating systems.

**However unlikely, you are hereby warned that data loss or other unintended consequences may result from *any* script's execution. I take NO RESPONSIBILITY for these scripts doing anything at all, even their intended functionality.** 

Some of these scripts were designed to execute with a particular environment in mind — if so, I will do my best to state which one within a directory or comment. Some scripts will specify a certain interpeter (e.g. ``#!/bin/dash`` or ``#!/bin/ash``) because of this, and it is highly likely that you will encounter errors running those particular scripts under a different shell.

That said, most scripts should work on most systems. **As they were designed for my personal use, most scripts do not check for the availability of dependencies within your ``$PATH``; they therefore may not work as described if the necessary dependencies are not installed or if they are not within your ``$PATH``. It is the user's responsibility to install, maintain and ensure the availability of any dependencies.**

Bug reports, fixes, patches, and general contributions are, of course, welcome.

These scripts are licensed under the GPLv3. **COMMERCIAL USE IS PROHIBITED**.
