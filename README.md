Extended US Keyboard Layout
===========================

Copyright (c) 2019, Luis Quesada Torres - https://github.com/lquesada | www.luisquesada.com

This keyboard layout is mostly US layout but allows using Alt GR to type
characters used in Spanish, German, French, and other languages.

It also replaces, by default, the Menu key with a second (right-hand-side)
Super key, and the Caps Lock key with a second (left-hand-side) Alt GR key.
Scroll all the way down for full information and config on overrides.

Set by running
$ xmodmap extus
Add it to the .xsession file or similar for it to take effect at startup.

If xmodmap halts your desktop manager for minutes after running and you're using the "us" layout already, try setting the diffonly version, which sets only the diff against the "us" layout:
$ xmodmap extusdiffonly
