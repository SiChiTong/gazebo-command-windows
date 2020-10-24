# gazebo-command-windows
gazebo command for the version of the Gazebo simulator that on Windows does not provide it.

## Build 
Compile Gazebo for Windows or download a Gazebo binary build, for example from https://github.com/robotology/robotology-superbuild-dependencies-vcpkg .

Then, download, compile and install this repo:
~~~
git clone https://github.com/traversaro/gazebo-command-windows
cd gazebo-command-windows
cmake -DCMAKE_INSTALL_PREFIX=<install_prefix>
cmake --build . --config Release
cmake --install . --config Release
~~~

## Use 
To use the binary, either add `<install_prefix>/bin` to the path and then launch the `gazebo` command from terminal.

