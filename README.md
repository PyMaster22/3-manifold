# 3-manifold


https://www.youtube.com/watch?v=CBPTcUxIISQ

i made this around 2016



to run, execute 3_less.c

if your not using windows you probably have to change the compiler flags at the top

the level is defined in roomgen.py starting on line 421

# apt-based linux instructions:
- If not installed install g++ with ``sudo apt install gcc``
- If python3 is not installed install it with ``sudo apt install python3``
- Open your cloned repo and run ``bash compile+run.sh``
- To stop the program I have had to press the shutdown button on my PC and keyboard inturupt the terminal.
- (this can be used as a super user or a regular user.)

# ~windows build instructions:~

- ~install this: https://www.msys2.org/ (make sure you follow steps 5-7 aswell)~
- ~open mingw64 (c:/msys64/mingw64 is the default install location)~
- ~to install clang type in ``pacman -S mingw-w64-x86_64-clang`` and press enter ~
- ~to install glfw type in ``pacman -S mingw-w64-x86_64-glfw`` and press enter~
- ~then drag 3_less.c into the window and press enter~
