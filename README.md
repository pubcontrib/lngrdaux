# lngrdaux

> Supplementary scripts, configurations, and documentation for lngrd development
and usage.

## Scripts

### check

Runs all check scripts.

### check-cxx

Compiles lngrd for each C standard then runs the test suite looking for source
incompatibility.

### check-cpp

Compiles lngrd using g++ then runs the test suite looking for source
incompatibility.

### check-sanitizers

Compiles lngrd using sanitizers then runs the test suite looking for undefined
behavior and memory bugs.

### check-valgrind

Compiles lngrd using valgrind then runs the test suite looking for memory bugs.

### check-powerpc

Compiles lngrd using powerpc-linux-gnu-gcc then runs the test suite using
qemu-user-binfmt looking for memory bugs.

### generate-argument-cases

Generates test cases of invalid arguments for lngrd built-ins.
