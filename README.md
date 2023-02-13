# chiaki
This fork provides an up to date build of Chiaki built with QT6 and containing the other feature improvements as listed below.  It is compatible with the latest Mac OS Catalina 10.15.7 intended for use on Intel based Macs.  The description below is copied from the main updated version of this project found here: [jbg77/chiaki](https://github.com/jbg77/chiaki)

---

This fork of Chiaki combines the works of Alvaromunoz, Jbaiters, Egoistically, and Streetpea to deliver an optimized gaming experience. It includes features such as haptic vibrations and adaptive triggers for a more immersive gaming experience, as well as improved colorimetry. Although haptic vibrations only work with USB and may not function, an emulation function for vibrations has been added for use with both USB and Bluetooth. The software is built using QT6.

## Features:

- Adaptive Triggers (Bluetooth and USB)
- Haptic rumble (only USB, may not work)
- Emulated haptic rumble (works with USB and Bluetooth)
- Built with QT6
- Improved colorimetry.

## Not Working:

- Controller microphone
- Controller speaker.

## Build
The program has been compiled for Mac (Apple Silicon) and can be built from source using CMake, Qt6, QtOpenGL and QtSvg, FFMPEG (libavcodec with H264 is enough), libopus, OpenSSL 1.1, SDL 2, protoc and the protobuf Python library (only used during compilation for Nanopb). To build the program, follow these instructions:

    bash
    Copy code
    git submodule update --init
    mkdir build && cd build
    cmake ..
    make

Enjoy playing games like Astrobots, now fully playable.
