# Environment Variables
Windows + R
```sh
systempropertiesadvanced
```
Create a Path variable with the value:  
C:\MinGW\bin  

```sh
mingw-get install mingw32-make
```  

```sh
mingw32-make
```

Inside the folder:
C:\MinGW\bin  
Make a cpy from the file "mingw32-make.exe" and rename it to "make.exe".


Compile and Run using the Makefile
```sh
make
```


# CMake
CMake


```sh
default:
  g++ main.cpp -o out
```

```sh
MyName: main.c
  gcc -o MyName main.c
```
