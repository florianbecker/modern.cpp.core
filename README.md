# modern.cpp.core
Modern C++ core classes for specific functions in most native and modern C++17.

## Build
```bash
mkdir build
cd build
cmake -DCMAKE_BUILD_TYPE=Debug|Release ../modern.cpp.core
make -j`nproc`
```

## Classes
- **CPU** - Get CPU information.
- **Double** - Less, Greater, Equal, Between, Round, Split.
- **Exec** - Run command and return stdout or mixed (stdout and stderr) and result code.
- **Keyboard** - Check for caps lock state.
- **Serial** - Serial communication class (Not for Windows).
- **StringExtra** - LeftTrim, RightTrim, Trim.
- **Timing** - Measuring time, cpu and real time.

## Template classes
- **CSVWriter** - Write out comma-separated values.
- **Singleton** - Singleton templace class.
- **Timer** - Timeout thread on time or interval.

## Unixservice class
- Main function to run as a unix daemon (Not for Windows).
