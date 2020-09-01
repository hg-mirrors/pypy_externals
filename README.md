This repository contains scripts which can be used to build PyPy dependencies on Windows.

To run these scripts you must use Python 3.6+ and have Visual Studio 2017+ installed.

These scripts were tested on x86 with VS 2017 Community (version 15.9.20).

Tcl/Tk fails to build, all other dependencies build successfully (some are downloaded pre-built).

See `build_prepare.py` for details, based on https://foss.heptapod.net/pypy/externals/-/tree/branch/win32_160 readme.
