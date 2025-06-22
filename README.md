# About

Basic Qt-CMake Hello world project.

## How to Build

```
// Below is an example if you're using vcpkg.
cmake -B build -S . -DCMAKE_TOOLCHAIN_FILE=D:/projects/ThirdParty/vcpkg/scripts/buildsystems/vcpkg.cmake
cmake --build build
```

## Troubleshooting

If you see this error  below you will need to set `QT_QPA_PLATFORM_PLUGIN_PATH`.
```
qt.qpa.plugin: Could not find the Qt platform plugin "windows" in ""
This application failed to start because no Qt platform plugin could be initialized. Reinstalling the application may fix this problem.
```