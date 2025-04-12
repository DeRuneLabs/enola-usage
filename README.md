# Enola Example Code

This repository contain basic or example usage of enola library which can be as reference

## Installation

```
git clone https://github.com/DeRuneLabs/enola.git
cd enola
```
After that you can make build folder which create cmake files to install libs
```
mkdir build
cd build
cmake ..
```
default installation usually on `/usr/local/include/` folders, but you can change installation prefix by specify the `cmake` by `-DCMAKE_INSTALL_PREFIX=path/to/installation` when running the `cmake`

```
make
sudo make install
```
