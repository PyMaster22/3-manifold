# 3-manifold


https://www.youtube.com/watch?v=CBPTcUxIISQ

I made this around 2016.



To run the program, execute 3_less.c

If your not using windows you probably have to change the compiler flags at the top.

The level is defined in roomgen.py starting on line 421.

# Windows 10 build instructions:

- Install this: https://www.msys2.org/ (make sure you follow steps 5-7 aswell).
- Open mingw64 (c:/msys64/mingw64 is the default install location).
- To install clang type in ``pacman -S mingw-w64-x86_64-clang`` and press enter .
- Then to install glfw type in ``pacman -S mingw-w64-x86_64-glfw`` and press enter.
- Finally drag 3_less.c into the window and press enter.

# Arch Linux build instructions:

- `pacman -S glfw-x11`
    - If you use wayland `pacman -S glfw-wayland`
- `python 3_roomgen.py`
- `gcc 3_less.c -lglfw -lm -ldl`
