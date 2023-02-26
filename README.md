# C Shell

## Building

Make sure you have `cmake` installed. 

First, Create a build directory:

```
mkdir build
cd build
```

Run `cmake`, with debug flag for debugging or release flag otherwise.

```
cmake -DCMAKE_BUILD_TYPE=Debug ..
```

Then, either run `make` or `ninja`:

```
make
```
or

```
ninja -C
```
