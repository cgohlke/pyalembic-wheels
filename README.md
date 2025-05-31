# PyAlembic wheels for Python on Windows

This repository provides unofficial binary wheels for [PyAlembic](https://github.com/alembic/alembic) for Python on Windows. The wheels also include the [PyImath](https://github.com/AcademySoftwareFoundation/Imath) extension.

The files are unofficial (meaning: informal, unrecognized, personal, unsupported, no warranty, no liability, provided "as is") and made available for testing and evaluation purposes.

Source code changes, if any, have been submitted to the project maintainers or are included in the wheels.

The [Microsoft Visual C++ Redistributable packages for Visual Studio 2022](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170) is required.

The ``alembic`` extension conflicts with the [``alembic``](https://pypi.org/project/alembic/) database migration tool, which must not be installed.

The wheels can be downloaded from the [Releases](https://github.com/cgohlke/pyalembic-wheels/releases) page.

## Release 2025.5.30

This release was built from the following source code:

- [alembic](https://github.com/alembic/alembic) 1.8.8
- [boost](https://www.boost.org/users/download/) 1.88.0
- [hdf5](https://support.hdfgroup.org/ftp/HDF5/releases/hdf5-1.8/hdf5-1.8.23/src/hdf5-1.8.23.zip) 1.8.23
- [imath](https://github.com/AcademySoftwareFoundation/Imath) 3.1.12
- [libaec](https://gitlab.dkrz.de/k202009/libaec) 1.1.3
- [zlib](https://github.com/madler/zlib) 1.3.1

## Build system

- [Windows Dev Kit](https://learn.microsoft.com/en-us/windows/arm/dev-kit/) 2023
- [Visual Studio](https://visualstudio.microsoft.com/vs/community/) 2022 Community 17.14
- [CPython](https://www.python.org/downloads/windows/) 3.11, 3.12, 3.13, 3.14 (win32, win-amd64, win-arm64)
