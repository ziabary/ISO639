ISO639
===========================

This is a simple C header file used to convert between different ISO639 Language codes. All of the ISO639 types including ISO639-1, ISO639-2/T and ISO639-2/B are supported.

## Build and test:

Dependencies:
 * GCC (+4)
 * Make or any IDE supported by CMake (Visual Studio, Eclipse, XCode, KDevelop, etc)


#### Configure and generate build files:

    mkdir -p $ISO639/build
    cd $ISO639/build
    cmake -DCMAKE_INSTALL_PREFIX:PATH=~/local ..

#### Install:

    cd $ISO639/build
    make install

###References
 http://www.iso.org/iso/home/standards/language_codes.htm

