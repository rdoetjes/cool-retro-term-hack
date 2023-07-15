# Patching to get the baudrate simulation

Download the source code from:

1) git clone --recursive https://github.com/Swordfish90/cool-retro-term.git

2) Install the dependencies (check on) https://github.com/Swordfish90/cool-retro-term/wiki/Build-Instructions-(Linux)

3) Replace the two files in the just checked out repository, with the two patched files

4) open kptyprocess.cpp and look for #define BAUDRATE 60000 and change 60000 with your preferred BAUDRATE. 

5) cd cool-retro-term

6) qmake && make

7) ./cool-retro-term 



