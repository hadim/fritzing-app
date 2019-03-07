# Building Fritzing

```bash
mkdir build/ && cd build/
conan remote add .. https://api.bintray.com/conan/bincrafters/public-conan
conan install .. --build missing
```
