# Project Template for Cpp & GLFW

## How to set up GLFW

you can set up GLFW  
1. download using package manager (for Mac and Ubuntu)
2. download prebuild library
3. compile the GLFW source code by yourself 

- install `glfw` on Mac using package manager

```bash
$ brew install glfw
```

- install `glfw` on Ubuntu using package manager

```bash
$ sudo apt-get install -y libx11-dev xorg-dev \
                          libglu1-mesa libglu1-mesa-dev \
                          libgl1-mesa-glx libgl1-mesa-dev
$ sudo apt install -y libglfw3 libglfw3-dev
$ sudo apt install -y libglew-dev
```

- You can download the prebuild library from here: https://www.glfw.org/download.html . 
Extract the compressed file and rename it as `GLFW_Lib` and put it under the `3rd_party/` folder of the repository.

- alternatively you can build `glfw` from source code

```bash
$ mkdir 3rd_party/GLFW_Lib 
$ git submodule update --init 3rd_party/glfw
$ cd 3rd_party/glfw
$ cmake .
$ cmake --build . 
$ cmake --install . --prefix ../GLFW_Lib 
``` 






## [00_OpenWin](00_OpenWindow)

a simplest demo to open window and draw triangle usign legacy OpenGL commands using GLFW library.

![thubmnail](00_OpenWindow/thumbnail.png)







 



