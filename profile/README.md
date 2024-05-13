## The Eigen Compiler Suite

This is an inofficial mirror of parts of https://ecs.openbrace.org/.

The Eigen Compiler Suite is a software development toolchain. It contains tools like compilers, pretty printers, interpreters, assemblers, and linkers targeting a variety of programming languages and hardware architectures. 

The Eigen Compiler Suite is particularly suited as a compiler kit and helps you to build your own compiler; the compiler kit features a documented intermediate language with assembler, disassembler, and interpreter. 

The compiler kit itself is implemented in C++17 and platform independent. The assemblers and code generators support the following hardware architectures:

- Intel/AMD x86_64 and x86
- Virtual 8086 and Real Mode
- ARM 64 and 32 bit (including thumb)
- Xtensa LX6 32 bit (Espressif ESP32)
- Amtel AVR and AVR32
- Motorola 68000
- Xilinx MicroBlaze 
- MIPS 64 and 32 bit
- OpenCores OpenRISC 1000
- PowerPC 64 and 32 bit
- WebAssembly
- and some others

Code generators and linkers for the following platforms/operating systems are available:

- Linux
- Windows
- macOS
- Raspberry Pi 
- DOS
- Atari TOS
- Bare metal and embedded systems
- and more

### Documentation

There is an extensive user manual available. All features of the Eigen Compiler Suite and especially the usage of its toolchain are documented in detail. For all major components like implementations of a programming language or supported hardware architectures, there are consistent documentations available which describe the usage of the corresponding component and its implementation by the Eigen Compiler Suite. This user manual merges all of these documentations into a single document. The user manual is available online and as a PDF:

- [Online](https://ecs.openbrace.org/manual/)
- [PDF](https://software.openbrace.org/attachments/269), 544 pages

### Source Code

This site includes an inofficial mirror of the source code usually distributed in compressed tar by the author.

- [Source repository](https://github.com/EigenCompilerSuite/sources)

### Precompiled binaries

- [Windows x86, self-extracting](https://software.openbrace.org/attachments/271)

### Live Demo

Visit the online version and try out over 100 tools provided by the Eigen Compiler Suite without having to install anything on your machine. 

- [Online Version](https://sandbox.openbrace.org/)

### Community

Your comments and suggestions help to improve the Eigen Compiler Suite for everyone. Please use the following links to post messages or submit bug reports:

- [Forums](https://software.openbrace.org/projects/ecs/boards)
- [Open Issues](https://software.openbrace.org/projects/ecs/issues?set_filter=1)


### Licensing

The Eigen Compiler Suite is licensed under the [GNU General Public License version 3](https://ecs.openbrace.org/licenses/gpl.html). All of its libraries and runtime support files are furthermore governed by the [ECS Runtime Support Exception](https://ecs.openbrace.org/licenses/rse.html). This is an additional permission under section 7 of the GPL which allows users of the Eigen Compiler Suite to create non-GPL (including proprietary) programs. 
