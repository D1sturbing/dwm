# dwm

dwm is an extremely fast, small, and dynamic window manager for X.

# Configuring dwm

The configuration of dwm is done by editing either config.h/config.def.h
and (re)compiling the source code. It is good practice to back up your working build of dwm and apply patches/modifications to a copy before merging the two.
Also, modifying config.def.h instead of config.h is encouraged, as well as removing the generated config.h file before recompiling as leaving it can cause issues that will prevent you from recompiling. But i'm not your dad, so you can do whatever you want.

# D1sturbed's build

Just clone this repo and compile with the following command:
```
  $ make clean install
 ```
dwm should put it's binary in ```/usr/local/bin``` by default, but if it doesn't work, you can run that command as root too, it's what i do.

# Patching in more features 

You can find a treasure trove of excellent patches for dwm over at https://dwm.suckless.org/patches/
Credit for those patches goes to their respective authors.
I did not write any of the patches used in this fork from scratch (Shit's complicated, and i'm not a C wizard like the suckless devs or the people who make patches for suckless software.) But i intend to contribute when i have the skill, time, and the need to.
