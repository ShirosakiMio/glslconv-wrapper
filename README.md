# How to compile?
aarch64-linux-android-g++ glslconv.cpp -I ./include -L ./lib -lglslang -lc++ -shared -fPIC -Wl,--soname=libglslconv.so -o ./libglslconv.so
# A warpper of glslang
  This is a simple wrapper of glslang-based shader converter.
  - [glslang-converter](https://github.com/AOF-Dev/glslang-converter).
