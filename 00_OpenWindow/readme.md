# 00_OpenWindow
![](thumbnail.png)


## How to build

<<<<<<< HEAD
First, make a direcotry `build` for **out-of-source build**
=======
First, make a direcotry for **out-of-source build**

>>>>>>> 931d63e884045ebdb239c98ef6529e1af945ac7c
```bash
$ cd 00_OpenWindow
$ mkdir build
$ cd build
```

<<<<<<< HEAD
Then, cofigure and build the demo by typing
```bash
cmake .. 
cmake --build .
```
=======
Then, inside `build` folder, generate build files and build the code. 

```bash
cmake .. 
cmake --build .
```

There is a CI build script file at [ci_windows.yml](../.github/workflows/ci_windows.yml). 

>>>>>>> 931d63e884045ebdb239c98ef6529e1af945ac7c
