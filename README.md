This repository contains scripts which can be used to build PyPy dependencies on Windows.

To run these scripts you must use Python 3.6+ and have Visual Studio 2017+ installed.

These scripts were tested on x86 with VS 2019 version 16.5 (MSVC v142)

Tcl/Tk fails to build, all other dependencies build successfully (some are downloaded pre-built).

See `build_prepare.py` for details, based on https://foss.heptapod.net/pypy/externals/-/tree/branch/win32_160 readme.
