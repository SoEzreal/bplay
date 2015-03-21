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

**How to install?**

On Windows:
````
git clone https://github.com/simargl/bplay
cd bplay
make win
````
On Linux 64-bit:
````
git clone https://github.com/simargl/bplay
cd bplay
make install
````
On Linux 64-bit:
First rename bplay/lib/libbass32.so to bplay/lib/libbass.so, and then:
````
cd bplay
make install
````
Dependencies:
````
fltk 1.3.x
````

