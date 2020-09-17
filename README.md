# Tessellation
Tessellation is the covering of a plane using one or more geometric shapes, called tiles, with no overlaps and no gaps. - Wikipedia

# Features
The program shows a tessellation on the screen. Upon closing the window, the tessellation is saved to 'tessellation.png' which located in the same directory as the program.

# Build
```
cmake -G <generator-of-choice> -S . -B build -DCGLM_STATIC=ON
cmake --build build
```
The executable will bin located in `./bin/`.
