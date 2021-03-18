# 00_OpenWindow
![](thumbnail.png)


## How to build

First, make a direcotry for **out-of-source build**

```bash
$ cd 00_OpenWindow
$ mkdir build
$ cd build
```

Then, inside `build` folder, generate build files and build the code. 

```bash
cmake .. 
cmake --build .
```

There is a CI build script file at [ci_windows.yml](../.github/workflows/ci_windows.yml). 

