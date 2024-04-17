**POLYBAR**

apt install cmake cmake-data pkg-config python3-sphinx libcairo2-dev libxcb1-dev libxcb-util0-dev libxcb-randr0-dev libxcb-composite0-dev python3-xcbgen xcb-proto libxcb-image0-dev libxcb-ewmh-dev libxcb-icccm4-dev libxcb-xkb-dev libxcb-xrm-dev libxcb-cursor-dev libasound2-dev libpulse-dev libjsoncpp-dev libmpdclient-dev libuv1-dev libnl-genl-3-dev


git clone - -recursive <https://github.com/polybar/polybar>

mkdir build
cd build
cmake ..
make -j$(nproc)
sudo make install

-- No build type specified; using Release
-- Couldn't locate ccache, disabling ccache...
-- Using supported compiler GNU-12.2.0
CMake Error at lib/CMakeLists.txt:15 (add_subdirectory):
  The source directory

    /home/rioikit/Custom Parrot/polybar/lib/xpp

  does not contain a CMakeLists.txt file.


CMake Error at lib/CMakeLists.txt:17 (message):
  Target xpp not generated


-- Configuring incomplete, errors occurred!
See also "/home/rioikit/Custom Parrot/polybar/build/CMakeFiles/CMakeOutput.log".


