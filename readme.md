BPlay
======= 

Cross-platform internet radio player

Copyright © 2015

<https://github.org/simargl>

**Credits**

BASS - Audio library (free for non-commercial use) 
http://www.un4seen.com/bass.html

FLTK - Cross-platform C++ GUI toolkit (LGPL v2) 
http://www.fltk.org/index.php

RadioSure - Used stations database 
http://www.radiosure.com/stations/

![Screenshot]
(https://github.com/simargl/bplay/blob/master/data/screenshot.png "Screenshot")

**Download**

[Windows 32-bit](https://github.com/simargl/bplay/raw/master/releases/bplay-1.0.5-win32.tar.xz)

[Linux 64-bit (Compiled in Slackware with static FLTK libraries)](https://github.com/simargl/bplay/raw/master/releases/bplay-1.0.5-linux64.tar.xz)

**How to install from source?**
````
git clone https://github.com/simargl/bplay
cd bplay
````
On Windows:
````
make win
````
On Linux 64-bit:
````
make install
````
On Linux 32-bit:

1. rename bplay/lib/libbass32.so to bplay/lib/libbass.so, then:
````
make install
````
Dependencies:
````
fltk >= 1.3.0
````

