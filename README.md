# ECE4122HW3 README File
By: Fabian Contreras
HW3 Includes a rural scene that was rendered through PACE-ICE to ensure compatibility and correctness.

#Build Instructions
With the included CMakeLists.txt one can:
1) Go into the build directory after making one (i.e mkdir build and cd build)
2) Run a clean build (i.e cmake ..)
3) Compile the build (i.e cmake --build . -j24)
4) cd into the bin directory (i.e cd bin)
5) Finally run the executable using ./Executable_name (i.e ./HW3)

#Controls
Within the rendered rural scene you actually have contorl in what you can do for instance:
1) W - Moves you forward
2) S - Moves you backward
3) A - Moves you left
4) D - Moves you right
5) E - Moves you up
6) Q - Moves you down
7) Right Mouse Button + drag - Rotates camera torward the drag direction
8) Scroll Wheel - Zooms in and out controlling FOV(A faster forward and backward)
9) R - Resets the camera to its original position
10) ESC - Exits the application

#Assets used
Within the rural scene i used these assets:
1) Farmhouse (1x)
2) Barrel (2x) (one with 15 dgree rotation, other one no rotation)
3) Pine Tree (4x) (Each with a random degree of rotation)
4) Wooden Bench (1x) (With -30 degrees of rotation)
5) Street Lamp (2x) (Both with .5 scale and no rotation)
6) Robot (1x) (A rotation that will make it so the default camera view faces it)

#Lighting
For lighting I used A purple background that should have represented an almost dusk scene, the default terrain color with a better diffuse to make it lighter, Point Light 0 allows lamp 0 to emit light to nearby objects almost like a real light should. The same goes for Point Light 1, but corresponds to lamp 1 instead.

#Shaders
As for shaders I used two files that were given to us that being:
1) object.vert
2) object.frag
