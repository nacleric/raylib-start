## Packaged everything idc
mkdir build
cd /build

## Generate build files
cmake ..

## Actually build
cmake --build .

## To run
Move to /build/debug
./raylib-start.exe

## TODO
Need to configure vscode debugger