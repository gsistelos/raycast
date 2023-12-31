# C++ Raycast Engine: Inspired by "cub3d"

Having successfully completed the "cub3d" project at École 42, I decided to dive deeper into the fascinating world of raycast engines. My approach was straightforward: create a C++ version of the engine, with some essential changes that, in my opinion, enhance the overall experience.

## Key Features:

### Multiplatform with GLFW:
I've taken the original concept and made it even more accessible by implementing multiplatform support using the GLFW library. This allows the engine to run smoothly on various operating systems, providing a consistent experience for users.

### Floor and Ceiling Textures:
One of the significant enhancements I've introduced is the ability to render floor and ceiling textures, a feature that wasn't present in the original "cub3d" project. This addition adds depth and realism to the scenes created with the engine, enhancing the overall visual experience.

### Custom Wall Textures:
In contrast to the traditional approach of assigning wall textures based on wall sides (N, S, W, E), I've embraced a map-based approach. Each wall character in the map corresponds to a specific wall texture, allowing for a more intuitive representation of the scene. This feature makes the engine more user-friendly for both developers and users.

## Compilation

Clone repository recursively:
```sh
git clone --recursive git@github.com:gsistelos/raycast.git
```

### Dependencies

`make`, `cmake`, `libopengl-dev` and `mingw64` only for Windows.

Also, see [GLFW dependencies](https://www.glfw.org/docs/latest/compile.html#compile_deps)

### Linux and Windows:

If you are on WSL, export `OS=Windows_NT` to your environment variables.

Run `make`.

### MacOS:

As I don't have a Mac, I've followed the instructions to compile glfw, but I'm not sure if it's working.

Try `make`.

## Usage

You can run the program or specify a map with:
```sh
./raycast [map_file]
```
