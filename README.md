# SepaNCNN (Under Construction)

This is SepaNCNN. 

## Build
1. clone ncnn and init submodule.
```bash
cd /pathto/ncnn
git submodule init && git submodule update
```
2. build.
```bash
mkdir build
cd build
cmake ..
cmake --build . --config Release -j 2
```
