# Learn CMake
cmake for simple application

## Dependencies
- C++ compiler
- CMake 3.18

## Compile
### Linux
```
# generate makefile
cmake --source . --build ./build
# or
cmake -S . -B ./build

# build program
cmake --build ./build
```

## Run program
```
./build/hello
```

## Clean
```
# remove generated binaries
cmake --build ./build --target clean
```