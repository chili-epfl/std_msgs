```
mkdir build-android && build-android
cmake -DCMAKE_TOOLCHAIN_FILE=~/src/android-cmake/android.toolchain.cmake -DANDROID_STANDALONE_TOOLCHAIN=/opt/crystax-standalone-toolchain -DCMAKE_INSTALL_PREFIX=/opt/crystax-standalone-toolchain/sysroot/usr/ -DCMAKE_BUILD_TYPE=Release ..
make -j 5
sudo make install
```
