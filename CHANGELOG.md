## 1.0.0

- The source code has been migrated to null safety. Thanks to the author of this work, Brett Sutton (github.com/bsutton).

## 0.1.3

- Minor changes in processor architecture recognition

## 0.1.2

- The source code has been modified in accordance with Google’s guidelines about the effectiveness of the Dart language

## 0.1.1

- To avoid downgrading the rating on https://pub.dartlang.org, the source code has been changed to fit Google’s ever-changing recommendations on what a good (pedantic) source code should be.

## 0.1.0

- Adaptation to Dart 2.0

## 0.0.16

- Fixed bug in detection of `user space bitness` on Mac OS X

## 0.0.15

- Fixed bug in detection of `bitness of kernel` on Mac OS X

## 0.0.14

- Added statistics `getVirtualMemorySize()` about the current memory usage by the current process

## 0.0.12

- Breaking change, `ProcessorArchitecture.ARM64` renamed to `ProcessorArchitecture.AARCH64`

## 0.0.11

- Fixed bug in detection of `kernel architecture` on Windows. More universal algorithm independent from the architecture name, allows detect any architecture (X86/ AMD64/ IA64/ etc)
- Impoved detection of `bitness of kernel` on Windows. Added suport of `IA64`
- Impoved detection of `bitness of user space` on Windows. Added suport of `IA64`

## 0.0.10

- Implemented `getFreePhysicalMemory()` and `getTotalVirtualMemory()` on Mac OS X

## 0.0.9

- Fixed bug in detection of `bitness of kernel` on Linux

## 0.0.8

- Detection of `bitness of kernel` on Linux are based on the found file formats of `libc.so.*`

## 0.0.7

- Partial support of `processor architecture` statistics

## 0.0.6

- Renamed method `physicalMemoryFreeSize()` to `getFreePhysicalMemory()`
- Renamed method `physicalMemoryTotalSize()` to `getTotalPhysicalMemory()`
- Renamed method `virtualMemoryFreeSize()` to `getFreeVirtualMemory()`
- Renamed method `virtualMemoryTotalSize()` to `getTotalVirtualMemory()`

## 0.0.5

- Partial support of `phycical memory` and `virtual memory` statistics

## 0.0.4

- Fixed a bug when parsing comments in the file `/boot/config` on Linux

## 0.0.3

- Changed the algorithm for detecting the number of physical processor sockets on Windows

## 0.0.1

- Initial release

