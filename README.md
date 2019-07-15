# Basic NodeJS APIs for the QuickJS Javascript Engine
This project is based on QuickJS Engine and add some of the most common methods or global objects used in NodeJS

# Getting started
This was tested in Linux (Ubuntu), install the following dependencies before to compile:
- `apt-get install build-essential`
- `apt-get install gcc-multilib`

Then run:
```
make
```

To use compiler:
```
./qjsc -o myBinary myCode.js
./myBinary
```

With modules:
```
./qjsc -m -o myBinary myCode.js
```

To use the interpreter:
```
./qjs
```
or
```
./qjs myCode.js
```
Find out more here https://bellard.org/quickjs/


# What's new here?

## Console global object
- `console.error(...)`
- `console.warn(...)`

## Process global object
- `process.platform`
- `process.cwd()`
- `process.argv`
- `process.EOL`

## Path global object
- `path.basename(...)`
