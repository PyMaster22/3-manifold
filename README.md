# 3-manifold


https://www.youtube.com/watch?v=CBPTcUxIISQ

i made this around 2016



to run, execute 3_less.c

if your not using windows you probably have to change the compiler flags at the top

the level is defined in roomgen.py starting at https://github.com/en-GB/3-manifold/blob/c2d73fb0486ba64046243ac694ae94e6bbf586b4/3_roomgen.py#L421

# windows build instructions:

- install this: https://www.msys2.org/ (make sure you follow steps 5-7 aswell)
- open mingw64 (c:/msys64/mingw64 is the default install location)
- to install clang type in ``pacman -S mingw-w64-x86_64-clang`` and press enter 
- to install glfw type in ``pacman -S mingw-w64-x86_64-glfw`` and press enter
- then drag 3_less.c into the window and press enter
