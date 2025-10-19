-   Place source cpp files at src directory
-   Place header files at include/game directory
-   use #include "SDL3/header_name"    <---- SDL header file 
-   use #include "game/header_name"    <---- game header file 
-   use build directory and append .exe name 

x-------------------------------------------------------------x
-   When compiling using G++ compiler use cmd command format

g++ source files -o build/exe_name -I include -L lib -l SDL3

-   open file 

build/exe_file_name.exe