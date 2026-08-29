# Awesome Embedded Resources for Developers with stars

[![GitHub stars](https://badgen.net/github/stars/iDoka/awesome-embedded-software)](https://GitHub.com/iDoka/awesome-embedded-software/stargazers/) ⭐ 1,101 | 🐛 0 | 📅 2026-08-27
[![GitHub forks](https://badgen.net/github/forks/iDoka/awesome-embedded-software)](https://GitHub.com/iDoka/awesome-embedded-software/network/) ⭐ 1,101 | 🐛 0 | 📅 2026-08-27
[![GitHub watchers](https://badgen.net/github/watchers/iDoka/awesome-embedded-software/)](https://GitHub.com/iDoka/awesome-embedded-software/watchers/) ⭐ 1,101 | 🐛 0 | 📅 2026-08-27

<!--
[![GitHub contributors](https://badgen.net/github/contributors/iDoka/awesome-embedded-software)](https://GitHub.com/iDoka/awesome-embedded-software/graphs/contributors/)
[![GitHub pull-requests merged](https://badgen.net/github/merged-prs/iDoka/awesome-embedded-software)](https://github.com/iDoka/awesome-embedded-software/pulls?q=is%3Amerged)
[![GitHub latest commit](https://badgen.net/github/last-commit/iDoka/awesome-embedded-software)](https://GitHub.com/iDoka/awesome-embedded-software/commit/)
-->

> Awesome List of Sources and Libs for Embedded Systems Development

Implementation of Sources and Libs in this list are specifically suitable for resource-constrained Embedded Systems (low-memory and low-power) like 8-bit, 16-bit and 32-bit microcontrollers.

> **Warning**
> This list does'nt cover any linux-related topics (like Raspberry Pi platform or any other SBCs (Single Board Computer)).

Permanent URL to this list: <https://github.com/iDoka/awesome-embedded-software> ⭐ 1,101 | 🐛 0 | 📅 2026-08-27

## Contents

* [Common](#common)
* [Memory](#memory)
  * [Memory management](#memory-management)
  * [Buffers](#buffers)
  * [Ring Buffer](#ring-buffer)
  * [FIFO](#fifo)
* [Storage](#storage)
  * [Filesystems](#filesystems)
  * [Data Bases](#data-bases)
  * [Flash Memory](#flash-memory)
* [Protocols](#protocols)
  * [Radio Frequency Protocols](#radio-frequency-protocols)
  * [Network protocols](#network-protocols)
  * [Web Server](#web-server)
  * [MQTT](#mqtt)
  * [Protocol Parsers](#protocol-parsers)
* [Data processing](#data-processing)
  * [Math](#math)
  * [DSP and Filtering](#dsp-and-filtering)
  * [Compression](#compression)
  * [AI ML](#ai-ml)
  * [CV](#cv)
* [Cryptography](#cryptography)
  * [General](#general)
  * [Elliptic Curve Cryptography](#elliptic-curve-cryptography)
  * [Random Number Generation](#random-number-generation)
* [OS](#os)
  * [RTOS](#rtos)
  * [Event based scheduler](#event-based-scheduler)
* [User Interface](#user-interface)
  * [CLI](#cli)
  * [Menu](#menu)
  * [printf](#printf)
  * [scanf](#scanf)
  * [Logging](#logging)
* [GUI](#gui)
  * [GUI editors](#gui-editors)
  * [Font utils](#font-utils)
  * [Picture manupulation tools](#picture-manupulation-tools)
* [Hardware](#hardware)
  * [IO](#io)
  * [USB](#usb)
  * [Flash](#flash)
  * [CAN bus](#can-bus)
  * [Sensors](#sensors)
* [Others](#others)
  * [Thread management](#thread-management)
  * [Bootloaders](#bootloaders)
  * [Firmware updates](#firmware-updates)
  * [Touch Screen](#touch-screen)
  * [Time Management Libs](#time-management-libs)
  * [Embeddable Scripts and Languages](#embeddable-scripts-and-languages)
* [Compilers](#compilers)
* [Uncategorized](#uncategorized)

## Common

* [ETLCPP](https://github.com/ETLCPP/etl) ⭐ 3,110 | 🐛 62 | 🌐 C++ | 📅 2026-08-28 - Embedded Template Library where the user can declare the size, or maximum size of any object upfront.
* [sc](https://github.com/tezc/sc) ⭐ 2,569 | 🐛 3 | 🌐 C | 📅 2026-07-18 - Portable, stand-alone C libraries and data structures (C99).
* [Collection of miscellaneous portable C snippets](https://github.com/nemequ/portable-snippets) ⭐ 774 | 🐛 22 | 🌐 C | 📅 2024-01-16 - Collection of miscellaneous portable C snippets.
* [Embedded Artistry's libc](https://github.com/embeddedartistry/libc) ⭐ 661 | 🐛 34 | 🌐 C | 📅 2026-03-17 - A stripped-down C standard library implementation targeted for microcontroller-based embedded systems. Reduced set of functionality (due to embedded nature). Chosen for portability and quick bringup.
* [embxx](https://github.com/arobenko/embxx) ⭐ 295 | 🐛 9 | 🌐 C++ | 📅 2019-12-08 - Embedded C++ Library.
* [ctl](https://github.com/rurban/ctl) ⭐ 289 | 🐛 15 | 🌐 C | 📅 2026-02-10 - C Container Template Library. There is a fast compiling, type safe, header only, template-like container library for ISO C99/C11.
* [µClibc-ng](https://github.com/wbx-github/uclibc-ng) ⭐ 214 | 🐛 0 | 🌐 C | 📅 2026-08-25 - Embedded C Library.
* [wiselib](https://github.com/ibr-alg/wiselib) ⭐ 128 | 🐛 15 | 🌐 C | 📅 2014-08-26 - Generic algorithms library for heterogeneous, distributed, embedded systems.
* [embedded-libs](https://github.com/MaJerle/embedded-libs) ⭐ 61 | 🐛 0 | 🌐 C | 📅 2020-01-02 - Libraries for embedded software (mainly for STM32).
* [HWlib](https://github.com/wovo/hwlib) ⭐ 59 | 🐛 3 | 🌐 C++ | 📅 2021-11-22 - C++ OO micro-controller library for close-to-the-hardware programming.
* [MicroTBX](https://github.com/feaser/microtbx) ⭐ 41 | 🐛 0 | 🌐 C | 📅 2026-08-24 - Open source Microcontroller ToolBoX consisting of software components commonly needed in embedded software applications. MicroTBX is written in the C programming language (C99) with MISRA compliance in mind.
* [FSMLang](https://github.com/FSMLang/FSMLang) ⭐ 10 | 🐛 19 | 🌐 C | 📅 2026-08-26 - State machine description language with C language generator. Supports flat and hierarchical machines and event subsystem.
* [umlibc](https://github.com/rhempel/umlibc) ⭐ 9 | 🐛 0 | 🌐 C | 📅 2024-12-08 - A bare-bones libc for memory constrained systems.
* [util.embedded](https://github.com/malachib/util.embedded) ⚠️ Archived - Useful support code for embedded development.
* [eFLL](https://github.com/zerokol/eFLL) ⭐ 0 | 🐛 0 | 📅 2026-01-22 - Embedded Fuzzy Logic Library is a standard library for Embedded Systems.

## Memory

### Memory management

* [umm\_malloc](https://github.com/rhempel/umm_malloc) ⭐ 490 | 🐛 6 | 🌐 C | 📅 2026-06-25 - Memory Manager For Small(ish) Microprocessors.
* [lwmem](https://github.com/MaJerle/lwmem) ⭐ 458 | 🐛 1 | 🌐 C | 📅 2026-08-21 - Lightweight dynamic memory manager library for embedded systems with memory constraints. It implements malloc, calloc, realloc and free functions.
* [o1heap](https://github.com/pavel-kirienko/o1heap) ⭐ 417 | 🐛 4 | 🌐 C++ | 📅 2026-02-09 - A highly deterministic constant-complexity memory allocator designed for hard real-time high-integrity embedded systems.
* [libmemory](https://github.com/embeddedartistry/libmemory) ⭐ 285 | 🐛 8 | 🌐 C | 📅 2026-01-21 - Memory management library with implementations for malloc(), free(), and other useful memory management functions.

### Buffers

* [EmbeddedProto](https://github.com/Embedded-AMS/EmbeddedProto) ⭐ 276 | 🐛 5 | 🌐 C++ | 📅 2026-08-20 -  C++ Protocol Buffers implementation specifically suitable for ARM Cortex-M microcontrollers. It is small, reliable and easy to use.
* [protobuf-embedded-c](https://github.com/berezovskyi/protobuf-embedded-c) ⭐ 48 | 🐛 27 | 🌐 C | 📅 2015-09-26 - Protocol buffers generator for resource constrained embedded applications written in the C programming language.

### Ring Buffer

* [LwRB](https://github.com/MaJerle/lwrb) ⭐ 1,527 | 🐛 2 | 🌐 C | 📅 2026-08-21 - Lightweight generic ring buffer manager library.
* [lfbb](https://github.com/DNedic/lfbb) ⭐ 119 | 🐛 0 | 🌐 C++ | 📅 2026-05-20 - Lock-free bipartite buffer, a variant of the ring buffer which can always provide contigous space inside the buffer for reading, writing or modifying the data in-place.
* [RingBuffer](https://github.com/wizard97/ArduinoRingBuffer) ⭐ 117 | 🐛 5 | 🌐 C | 📅 2020-10-24 - Simple Interrupt Safe Ring (Circular) Buffer Queuing Library for Embedded platforms.

### FIFO

* [fifofast](https://github.com/nqtronix/fifofast) ⭐ 280 | 🐛 2 | 🌐 C | 📅 2022-07-02 - A fast, generic fifo for MCUs.

## Storage

### Filesystems

* [littlefs](https://github.com/littlefs-project/littlefs) ⭐ 6,912 | 🐛 632 | 🌐 C | 📅 2026-03-25 - Little fail-safe filesystem designed for microcontrollers.
* [SdFat](https://github.com/greiman/SdFat) ⭐ 1,208 | 🐛 241 | 🌐 C++ | 📅 2025-08-13 - Arduino FAT16/FAT32 exFAT Library.
* [lwext4](https://github.com/gkostka/lwext4) ⭐ 592 | 🐛 34 | 🌐 C | 📅 2024-03-22 - An ext2/ext3/ext4 filesystem library for microcontrollers.
* [LevelX](https://github.com/azure-rtos/levelx) ⭐ 153 | 🐛 27 | 🌐 C | 📅 2026-07-22 - Provides Flash Wear Leveling for FileX and Stand Alone purposes.
* [uC-FS](https://github.com/weston-embedded/uC-FS) ⭐ 110 | 🐛 5 | 🌐 C | 📅 2021-05-20 - Compact, reliable, high-performance, and thread-safe embedded file system for microprocessors, microcontrollers, and DSPs. An optional journaling component provides fail-safe operation while maintaining FAT compatibility.
* [fat32](https://github.com/strawberryhacker/fat32) ⭐ 105 | 🐛 0 | 🌐 C | 📅 2025-04-03 - Lighweight FAT32 file system written in C with no thirdparty dependencies. It requires a small port which provide functions for initializing, reading and writing to the MSD.
* [fat\_io\_lib](https://github.com/ultraembedded/fat_io_lib) ⭐ 79 | 🐛 6 | 🌐 C | 📅 2019-04-23 - Small footprint, low dependency, C code implementation of a FAT16 & FAT32 driver.
* [ufat](https://github.com/dlbeer/ufat) ⭐ 59 | 🐛 3 | 🌐 C | 📅 2023-04-25 - Low-memory feature-complete VFAT implementation.
* [UFFS](https://github.com/rickyzheng/uffs) ⭐ 56 | 🐛 7 | 🌐 C | 📅 2021-03-18 - Filesystem for NAND devices with wear leveling and good fault tolerance.
* [emfat](https://github.com/fetisov/emfat) ⭐ 39 | 🐛 0 | 🌐 C | 📅 2017-06-26 - FAT32 emulation library for stm32f4.
* [OpenFAT](https://github.com/tmolteno/openfat) ⭐ 39 | 🐛 2 | 🌐 C | 📅 2015-04-27 - FAT filesystem implementation for embedded processors.
* [FatFS](http://elm-chan.org/fsw/ff/00index_e.html) - FAT filesystem implementation.

### Data Bases

* [FlashDB](https://github.com/armink/FlashDB) ⭐ 2,837 | 🐛 192 | 🌐 C | 📅 2026-08-15 - Ultra-lightweight database that supports key-value and time series data.
* [UnQLite](https://github.com/symisc/unqlite) ⭐ 2,314 | 🐛 31 | 🌐 C | 📅 2026-05-01 - Embedded NoSQL, Transactional Database Engine.
* [Vedis](https://github.com/symisc/vedis) ⭐ 562 | 🐛 2 | 🌐 C | 📅 2021-11-25 - Embedded Implementation of Redis (an embeddable datastore C library built with over 70 commands similar in concept to Redis but without the networking layer since Vedis run in the same process of the host application).
* [PureDB](https://github.com/jedisct1/PureDB) ⭐ 36 | 🐛 0 | 🌐 C | 📅 2026-06-25 - Portable and tiny set of libraries for creating and reading constant databases.
* [microkvs](https://github.com/azonenberg/microkvs) ⭐ 24 | 🐛 0 | 🌐 C++ | 📅 2025-11-16 - Tiny key-value store for persisting configuration data on microcontrollers.

### Flash Memory

* [EasyFlash](https://github.com/armink/EasyFlash#1-introduction) ⭐ 2,363 | 🐛 61 | 🌐 C | 📅 2025-03-14 - Lightweight embedded flash memory library.
* [FlashAlgo](https://github.com/pyocd/FlashAlgo) ⭐ 179 | 🐛 17 | 🌐 C | 📅 2023-09-01 - Framework for building Arm Cortex-M "FLM" style flash programming algorithms.
* [FCB](https://docs.zephyrproject.org/latest/services/storage/fcb/fcb.html) - Flash Circular Buffer provides an abstraction through which you can treat flash like a FIFO.

## Protocols

* [nanoPB](https://github.com/nanopb/nanopb) ⭐ 5,541 | 🐛 80 | 🌐 C | 📅 2026-08-26 - Small code-size Protocol Buffers implementation in ANSI C. It is especially suitable for use in microcontrollers, but fits any memory restricted system.
* [nanoMODBUS](https://github.com/debevv/nanoMODBUS) ⭐ 903 | 🐛 37 | 🌐 C | 📅 2026-02-01 - A compact MODBUS RTU/TCP C library for embedded/microcontrollers.
* [TinyFrame](https://github.com/MightyPork/TinyFrame) ⭐ 433 | 🐛 10 | 🌐 C | 📅 2022-08-26 - Simple library for building and parsing data frames for serial interfaces (like UART / RS232).
* [rcobs](https://github.com/Dirbaio/rcobs) ⭐ 16 | 🐛 0 | 🌐 Rust | 📅 2021-04-16 - Reverse-COBS encoding (rCOBS) is a variant of [COBS encoding](https://en.wikipedia.org/wiki/Consistent_Overhead_Byte_Stuffing) designed to allow encoding with zero lookahead.
* [interchange](https://github.com/trussed-dev/interchange) ⭐ 15 | 🐛 2 | 🌐 Rust | 📅 2025-08-08 - Request/response mechanism for embedded development, using atomics.
* [aem-modbus-simulator](https://github.com/leaberg69/aem-modbus-simulator) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-05-31 - Open-source Python Modbus RTU/TCP slave simulator emulating an industrial DC monitor (147 holding registers, 6 baudrates). Useful for testing embedded firmware Modbus master implementations without physical slave hardware on the bench.
* [xmodem](https://github.com/bsail/xmodem) - XMODEM Library for embedded, mobile, iot, and desktop systems.

### Radio Frequency Protocols

* [Adafruit's RadioHead](https://github.com/adafruit/RadioHead) ⭐ 205 | 🐛 41 | 🌐 C++ | 📅 2023-05-12 - Packet Radio library for embedded microprocessors with [docs](http://www.airspayce.com/mikem/arduino/RadioHead/).
* [RadioHead](https://github.com/hallard/RadioHead) ⭐ 147 | 🐛 0 | 🌐 C++ | 📅 2021-11-17 - Packet Radio library for embedded microprocessors.

### Network protocols

* [uIP](https://github.com/adamdunkels/uip) ⭐ 1,082 | 🐛 5 | 🌐 C | 📅 2017-01-09 - Very small implementation of the TCP/IP stack that is written by Adam Dunkels.
* [LRNDIS](https://github.com/fetisov/lrndis) ⭐ 368 | 🐛 4 | 🌐 C | 📅 2021-06-24 - Ethernet over USB (rndis + lwip).
* [CycloneTCP](https://github.com/Oryx-Embedded/CycloneTCP) ⭐ 206 | 🐛 14 | 🌐 C | 📅 2026-05-29 - A dual IPv4/IPv6 stack dedicated to embedded applications. The stack is distributed as a full ANSI C and highly maintainable source code ([examples](https://www.oryx-embedded.com/download/CycloneTCP_SSL_SSH_CRYPTO_Open_2_2_4.zip) not included in GitHub's sources).
* [LiveKit](https://github.com/livekit/client-sdk-esp32) ⭐ 147 | 🐛 16 | 🌐 C | 📅 2026-08-28 - ESP32 SDK for LiveKit: real-time audio, video, and data streaming.
* [HttpClient](https://github.com/nmattisson/HttpClient) ⭐ 121 | 🐛 8 | 🌐 C++ | 📅 2019-02-05 - Http Client Library.
* [RawTCP\_Lib](https://github.com/h3xduck/RawTCP_Lib) ⭐ 73 | 🐛 0 | 🌐 C | 📅 2024-12-20 - C library for creating and using TCP/IP packets with raw network sockets.
* [StaticNet](https://github.com/azonenberg/staticnet) ⭐ 41 | 🐛 7 | 🌐 C++ | 📅 2025-07-18 - C++ TCP/IP and SSH stack with all-static allocations designed for bare metal (no operating system) embedded applications with minimal footprint.
* [httpio](https://github.com/fetisov/httpio) ⭐ 6 | 🐛 0 | 🌐 C | 📅 2016-09-06 - Stand-Alone Cross Platform request parser and response generator for the HTTP protocol.
* [PicoTCP](https://github.com/Tubbz-alt/picotcp) ⭐ 1 | 🐛 0 | 📅 2020-12-11 - Small-footprint, modular TCP/IP stack designed for embedded systems and the Internet of Things.
* [LwIP](http://savannah.nongnu.org/projects/lwip/) - Small independent implementation of the TCP/IP protocol suite that has been initially developed by Adam Dunkels. lwIP suitable for use in embedded systems with tens of kilobytes of free RAM and room for around 40 kilobytes of code ROM.

### Web Server

* [mongoose](https://github.com/cesanta/mongoose) ⭐ 13,012 | 🐛 2 | 🌐 C | 📅 2026-08-28 - Embedded Web Server and Embedded Networking Library. It implements event-driven non-blocking APIs for TCP, UDP, HTTP, WebSocket, MQTT.
* [libevhtp](https://github.com/criticalstack/libevhtp) ⚠️ Archived - Extremely-fast and secure embedded HTTP servers with ease.
* [libμhttpd](https://github.com/zhaojh329/libuhttpd) ⭐ 432 | 🐛 7 | 🌐 C | 📅 2025-08-08 - Very flexible, lightweight and fully asynchronous HTTP server library based on libev and http-parser.
* [sandbird](https://github.com/rxi/sandbird) ⭐ 221 | 🐛 5 | 🌐 C | 📅 2019-10-27 - Tiny (800sloc) embeddable HTTP server written in C89.

### MQTT

* [Paho MQTT](https://github.com/eclipse/paho.mqtt.embedded-c) ⭐ 1,539 | 🐛 92 | 🌐 C | 📅 2026-07-03 - C client library for embedded systems.
* [libemqtt 1](https://github.com/menudoproblema/libemqtt) ⭐ 225 | 🐛 6 | 🌐 C | 📅 2019-11-05 - Embedded C client library for the MQTT protocol.
* [libumqtt 2](https://github.com/zhaojh329/libumqtt) ⭐ 196 | 🐛 2 | 🌐 C | 📅 2024-08-29 - Lightweight and fully asynchronous MQTT client C library based on libev.

### Protocol Parsers

#### Regular Expressions Parsers

* [RegExp](https://github.com/MaJerle/RegExp) ⭐ 47 | 🐛 0 | 🌐 C | 📅 2017-11-11 - Regular expressions library for embedded systems.

#### GSM

* [TinyGSM](https://github.com/vshymanskyy/TinyGSM) ⭐ 2,212 | 🐛 354 | 🌐 C++ | 📅 2026-07-21 - Small Arduino library for GSM modules, that just works.
* [LwGSM](https://github.com/MaJerle/lwgsm) ⭐ 487 | 🐛 22 | 🌐 C | 📅 2026-08-11 - Library for SIMCOM GSM modules to communicate with AT commands and RTOS from host device.
* [GSM\_Engine](https://github.com/MikroElektronika/GSM_Engine) ⭐ 86 | 🐛 1 | 🌐 C | 📅 2017-09-11 - Generic AT parser for AT command based modules.

#### GPS

* [minmea](https://github.com/kosma/minmea) ⭐ 960 | 🐛 14 | 🌐 C | 📅 2026-07-15 - Lightweight GPS NMEA 0183 parser library in pure C.
* [LwGPS](https://github.com/MaJerle/lwgps) ⭐ 505 | 🐛 4 | 🌐 C | 📅 2026-08-21 - Lightweight GPS NMEA parser for embedded systems.

#### AT command parser

* [LwESP](https://github.com/MaJerle/lwesp) ⭐ 562 | 🐛 7 | 🌐 C | 📅 2026-08-11 - Lightweight ESP AT commands parser library to communicate with ESP8266 or ESP32 Wi-Fi module using AT commands.
* [cAT](https://github.com/marcinbor85/cAT) ⭐ 493 | 🐛 14 | 🌐 C | 📅 2023-12-20 - Plain C library for parsing AT commands for use in host devices.
* [ATParser](https://github.com/ARMmbed/ATParser) ⭐ 39 | 🐛 8 | 🌐 C++ | 📅 2019-10-29 - An mbed-os compatible AT command parser.
* [atcommander](https://github.com/malachi-iot/atcommander) ⚠️ Archived - Portable C++ library for sending AT commands and parsing their responses.
* [atat](https://github.com/esynr3z/atat) ⭐ 8 | 🐛 1 | 🌐 C | 📅 2018-08-10 - Lib for AT-like custom commands processing.
* [gzat](https://github.com/gzhouct/gzat) ⭐ 1 | 🐛 0 | 🌐 C++ | 📅 2020-08-09 - Portable AT command parsing library in C++ language.

#### Various protocols

* [libCoAP](https://github.com/obgm/libcoap) ⭐ 918 | 🐛 57 | 🌐 C | 📅 2026-08-25 - C implementation of a lightweight application-protocol for devices that are constrained their resources such as computing power, RF range, memory, bandwidth, or network packet sizes. This protocol, CoAP, is standardized by the IETF as RFC 7252.
* [lwpkt](https://github.com/MaJerle/lwpkt) ⭐ 380 | 🐛 3 | 🌐 C | 📅 2026-08-21 - Lightweight packet protocol structure for multi-device communication focused on RS-485.
* [MIN](https://github.com/min-protocol/min) ⭐ 284 | 🐛 25 | 🌐 Python | 📅 2024-01-30 - Microcontroller Interconnect Network protocol version 2.0.
* [lwow](https://github.com/MaJerle/lwow) ⭐ 278 | 🐛 1 | 🌐 C | 📅 2026-08-21 - Lightweight onewire protocol library optimized for UART hardware on embedded systems.
* [panStamp-SWAP](https://github.com/panStamp/swap) ⭐ 23 | 🐛 1 | 🌐 C++ | 📅 2017-07-12 - Simple Wireless Abstract Protocol for any existing ISM radio.
* [panStamp-uSWAP](https://github.com/panStamp/uswap) ⭐ 5 | 🐛 0 | 🌐 C++ | 📅 2016-02-08 - Micro SWAP stack for MCU's connected via UART.

## Data processing

### Math

* [FPM](https://github.com/MikeLankamp/fpm) ⭐ 834 | 🐛 21 | 🌐 C++ | 📅 2026-03-29 - C++ header-only fixed-point math library.
* [liquid-fpm](https://github.com/jgaeddert/liquid-fpm) ⭐ 65 | 🐛 4 | 🌐 C | 📅 2015-09-01 - Software-Defined Radio Fixed-Point Math Library for embedded signal processing.
* [Eigen](https://gitlab.com/libeigen/eigen) - C++ template library for linear algebra: matrices, vectors, numerical solvers, and related algorithms.

### DSP and Filtering

* [liquid-dsp](https://github.com/jgaeddert/liquid-dsp) ⭐ 2,284 | 🐛 163 | 🌐 C | 📅 2026-08-22 - Digital signal processing library for software-defined radios.
* [KISS FFT](https://github.com/mborgerding/kissfft) ⭐ 1,974 | 🐛 40 | 🌐 C | 📅 2026-08-12 - Mixed-radix Fast Fourier Transform based up on the principle, "Keep It Simple, Stupid".
* [CMSIS-DSP](https://github.com/ARM-software/CMSIS-DSP) ⭐ 1,074 | 🐛 52 | 🌐 C | 📅 2026-08-14 - Embedded compute library for Cortex-M and Cortex-A.
* [iir1](https://github.com/berndporr/iir1) ⭐ 780 | 🐛 0 | 🌐 C++ | 📅 2025-07-07 - DSP IIR realtime filter library written in C++.
* [pocketfft](https://github.com/mreineck/pocketfft) ⭐ 156 | 🐛 6 | 🌐 C++ | 📅 2026-06-30 - Heavily modified implementation of FFTPack.
* [kalman-clib](https://github.com/sunsided/kalman-clib) ⭐ 143 | 🐛 0 | 🌐 C | 📅 2026-06-09 - Microcontroller targeted naive Kalman filter implementation in pure C.
* [SigLib](https://github.com/Numerix-DSP/siglib) ⭐ 108 | 🐛 0 | 🌐 C | 📅 2026-08-23 - Digital Signal Processing and Machine Learning Library (x86, Cortex-A and Cortex-M, RISC-V, DSPs from TI, ADI etc).
* [lsp-dsp-lib](https://github.com/lsp-plugins/lsp-dsp-lib) ⭐ 92 | 🐛 0 | 🌐 C++ | 📅 2026-08-20 - DSP library for digital signal processing provides set of functions that perform SIMD-optimized computing on several hardware architectures. All functions currently operate on IEEE-754 single-precision floating-point numbers.
* [minfft](https://github.com/aimukhin/minfft) ⭐ 52 | 🐛 0 | 🌐 C | 📅 2025-08-11 - Small and fast Discrete Fourier Transform library.
* [libdspl](https://sourceforge.net/p/libdspl-2-0/code/ci/master/tree/) - Cross-platform digital signal processing algorithm library, written in C language.

### Compression

* [heatshrink](https://github.com/atomicobject/heatshrink) ⭐ 1,547 | 🐛 42 | 🌐 C | 📅 2024-05-19 - Data compression library for embedded/real-time systems.
* [SMAZ](https://github.com/antirez/smaz) ⭐ 1,221 | 🐛 13 | 🌐 C | 📅 2019-10-25 - Compression for very small strings.
* [shoco](https://github.com/Ed-von-Schleck/shoco) ⭐ 390 | 🐛 32 | 🌐 C | 📅 2026-02-16 - C library to compress and decompress short strings. It is very fast and easy to use. The default compression model is optimized for english words, but you can generate your own compression model.
* [Unishox2](https://github.com/siara-cc/Unishox2) ⭐ 249 | 🐛 15 | 🌐 C | 📅 2026-08-26 - Hybrid encoder for Short Unicode Strings (Unishox provides the best compression for short text and not to be compared with general purpose compression algorithm like lz4, snappy, lzma, brottli and zstd).
* [TCOBS](https://github.com/rokath/tcobs) ⭐ 31 | 🐛 2 | 🌐 C | 📅 2026-04-29 - Short messages compression with COBS framing using implicit run-length-encoding, optimized for data containing statistically a bit more 0 and FF bytes in a row, as data often carry 16, 32 or 64 bit numbers with small values.
* [ECL](https://github.com/Nonoum/ECL) ⭐ 25 | 🐛 0 | 🌐 C | 📅 2026-03-01 - Embedded Compression Library is not only for embedded, it is mostly oriented for small data and has special optimized low-memory modes for restricted environments.

### AI ML

Artificial Intelligence and Machine Learning

* [μTensor](https://github.com/uTensor/uTensor) ⭐ 1,928 | 🐛 56 | 🌐 C++ | 📅 2025-05-10 - TinyML AI inference library.
* [nnom](https://github.com/majianjia/nnom) ⭐ 1,164 | 🐛 88 | 🌐 C | 📅 2024-04-08 - Neural Network on Microcontroller (NNoM) is a high-level inference Neural Network library specifically for microcontrollers.
* [TinyMaix](https://github.com/sipeed/TinyMaix) ⭐ 1,071 | 🐛 22 | 🌐 C | 📅 2025-02-05 - A tiny inference Neural Network library specifically for microcontrollers (TinyML). Designed to follow the rule: Easy-to-Use > Portable > Speed > Space.
* [libonnx](https://github.com/xboot/libonnx) ⭐ 652 | 🐛 16 | 🌐 C | 📅 2026-07-07 - Lightweight, portable pure C99 onnx inference engine for embedded devices with hardware acceleration support.
* [Cranium](https://github.com/100/Cranium) ⭐ 604 | 🐛 10 | 🌐 C | 📅 2023-10-29 - Portable, header-only, feedforward artificial neural network library written in vanilla C99.
* [Fido](https://github.com/FidoProject/Fido) ⭐ 463 | 🐛 15 | 🌐 C++ | 📅 2020-01-05 - Lightweight C++ machine learning library for embedded electronics and robotics.
* [edge-agents (ForestHub)](https://github.com/ForestHubAI/edge-agents) ⭐ 100 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-24 - Open-source (AGPL-3.0) 30 MB AI agent runtime for edge devices. Offline by default; GPIO/UART/MQTT as first-class nodes; local SLMs alongside cloud LLMs. Runs on Raspberry Pi, Jetson, STM32MP25.
* [caffepresso](https://github.com/gplhegde/caffepresso) ⭐ 88 | 🐛 0 | 🌐 C | 📅 2024-10-16 - Optimized Library for Deep Learning on Embedded Accelerator-based platforms.

### CV

Computer Vision

* [Embedded SOD](https://github.com/symisc/sod) ⭐ 1,798 | 🐛 7 | 🌐 C | 📅 2023-10-20 - Embedded Computer Vision & Machine Learning Library (CPU Optimized & IoT Capable).
* [QR-Image-embedded](https://github.com/swex/QR-Image-embedded) ⭐ 74 | 🐛 0 | 🌐 C | 📅 2020-01-15 - QR library fork for embedded systems.

## Cryptography

### General

* [mbedTLS](https://github.com/Mbed-TLS/mbedtls) ⭐ 6,926 | 🐛 1,730 | 🌐 C | 📅 2026-08-27 - Open source, portable, easy to use, readable and flexible TLS library, and reference implementation of the PSA Cryptography API.
* [tiny-AES-c](https://github.com/kokke/tiny-AES-c) ⭐ 5,001 | 🐛 35 | 🌐 C | 📅 2024-10-04 - Small portable AES128/192/256 in C.
* 🔝[trezor-crypto](https://github.com/trezor/trezor-firmware/tree/master/crypto) ⭐ 1,815 | 🐛 729 | 🌐 C | 📅 2026-08-28 - Heavily optimized cryptography algorithms for embedded Devices.
* [LibTomCrypt](https://github.com/libtom/libtomcrypt) ⭐ 1,788 | 🐛 53 | 🌐 C | 📅 2026-08-08 - Fairly comprehensive, modular and portable cryptographic toolkit that provides developers with a vast array of well known published block ciphers, one-way hash functions, chaining modes, pseudo-random number generators, public key cryptography and a plethora of other routines.
* [Monocypher](https://github.com/LoupVaillant/Monocypher) ⭐ 780 | 🐛 9 | 🌐 C | 📅 2026-07-28 - Easy to use, easy to deploy, auditable crypto library written in portable C.
* [LibHydrogen](https://github.com/jedisct1/libhydrogen) ⭐ 779 | 🐛 0 | 🌐 C | 📅 2026-08-26 - Lightweight, secure, easy-to-use crypto library suitable for constrained environments.
* [tlse](https://github.com/eduardsui/tlse) ⭐ 685 | 🐛 33 | 🌐 C | 📅 2026-08-07 - Single C file TLS 1.2/1.3 implementation, using tomcrypt as crypto library.
* [tinycrypt](https://github.com/intel/tinycrypt) ⚠️ Archived - Library of cryptographic algorithms provides an implementation for constrained devices of a minimal set of standard cryptography primitives.
* [trussed](https://github.com/trussed-dev/trussed) ⭐ 501 | 🐛 18 | 🌐 Rust | 📅 2026-07-22 - Minimal, modular way to write cryptographic applications on microcontroller platforms (Rust).
* [arduinolibs](https://github.com/rweather/arduinolibs) ⭐ 477 | 🐛 38 | 🌐 C++ | 📅 2024-05-26 - Arduino Cryptography Library.
* [wolfTPM](https://github.com/wolfSSL/wolfTPM) ⭐ 340 | 🐛 4 | 🌐 C | 📅 2026-08-26 - Highly portable TPM 2.0 library, designed for embedded use.
* 🔝[liblithium](https://github.com/teslamotors/liblithium) ⭐ 325 | 🐛 0 | 🌐 C | 📅 2026-03-28 - Lightweight cryptography library that is portable by design. It requires only standard C99 and does not assume 8-bit addressability, making it suitable for use on some DSP architectures as well as mainstream architectures.
* [poly1305-donna](https://github.com/floodyberry/poly1305-donna) ⭐ 122 | 🐛 6 | 🌐 C | 📅 2022-09-28 -  Implementations of a fast Message-Authentication Code (8 bit, 16 bit, 32 bit and 64 bit multiplies versions).
* [µAES](https://github.com/polfosol/micro-AES) ⭐ 74 | 🐛 1 | 🌐 C | 📅 2026-04-29 - Lightweight, highly flexible, portable and ANSI-C compatible implementation of the AES encryption and block cipher modes.
* [CycloneCRYPTO](https://github.com/Oryx-Embedded/CycloneCRYPTO) ⭐ 71 | 🐛 3 | 🌐 C | 📅 2026-05-29 - A cryptographic toolkit designed for use in embedded systems. It provides a comprehensive set of cryptographic primitives (hash functions, stream and block ciphers, public key cryptography) that can be used to add security features to your embedded application.
* [krypton](https://github.com/ezhangle/krypton) ⭐ 28 | 🐛 0 | 🌐 C | 📅 2015-12-13 - Embedded TLS/DTLS library, source and binary compatible OpenSSL subset.
* [minicrypt](https://github.com/IanHarvey/minicrypt) ⭐ 27 | 🐛 0 | 🌐 C | 📅 2014-06-11 - Library of crypto primitives for embedded systems.
* [wolfSSH](https://www.wolfssl.com/products/wolfssh/) - Lightweight SSHv2 client and server library written in ANSI C and targeted for embedded, RTOS, and resource-constrained environments - primarily because of its small size, speed, and feature set.

### Elliptic Curve Cryptography

* [micro-ecc](https://github.com/kmackay/micro-ecc) ⭐ 1,432 | 🐛 62 | 🌐 PHP | 📅 2024-11-14 - ECDH and ECDSA for 8-bit, 32-bit, and 64-bit processors.
* [salty](https://github.com/ycrypto/salty) ⭐ 67 | 🐛 14 | 🌐 Rust | 📅 2026-03-24 - Ed25519 signatures with assembly optimizations for Cortex-M4 and Cortex-M33.
* [libuecc](https://github.com/NeoRaider/libuecc) ⭐ 2 | 🐛 0 | 🌐 C | 📅 2025-09-12 - Very small generic-purpose Elliptic Curve Cryptography library compatible with Ed25519.
* [c25519-and-ed25519](https://dlbeer.co.nz/oss/c25519.html) - Curve25519 and Ed25519 for low-memory systems (Curve25519 scalar multiplication uses less than half a kB of peak stack usage).

### Random Number Generation

* [pcg-c-basic](https://github.com/imneme/pcg-c-basic) ⭐ 449 | 🐛 18 | 🌐 C | 📅 2023-11-25 - Code provides a minimal implementation of one member of the PCG family of random number generators, which are fast, statistically excellent, and offer a number of useful features.
* [pcg-c](https://github.com/imneme/pcg-c) ⭐ 422 | 🐛 10 | 🌐 C | 📅 2023-10-26 - Code provides an implementation of the PCG family of random number generators, which are fast, statistically excellent, and offer a number of useful features.

## OS

* [LK kernel](https://github.com/littlekernel/lk) ⭐ 3,667 | 🐛 92 | 🌐 C | 📅 2026-08-26 - The Little Kernel Embedded Operating System is SMP-aware kernel designed for small systems ported to a variety of platforms and cpu architectures.
* [QuarkTS](https://github.com/kmilo17pet/QuarkTS) ⭐ 350 | 🐛 4 | 🌐 C | 📅 2025-10-27 - OS for embedded applications that supports prioritized cooperative scheduling, time control, inter-task communications primitives, hierarchical state machines and CoRoutines.
* [vanilla](https://github.com/strawberryhacker/vanilla) ⭐ 38 | 🐛 17 | 🌐 C | 📅 2020-10-17 - Bare metal ARM® Cortex®-M7 operating system.
* [citrus](https://github.com/strawberryhacker/citrus) ⭐ 35 | 🐛 22 | 🌐 C | 📅 2021-01-20 - Bare metal ARM® Cortex®-A5 operating system.
* 🔝[chaos](https://github.com/strawberryhacker/chaos) - Bare metal multicore ARM® Cortex®-A operating system based on a microkernel architecture.
* [micro-ROS](https://micro.ros.org/) - Micro-ROS puts ROS 2 onto microcontrollers.

### RTOS

* [Zephyr](https://github.com/zephyrproject-rtos/zephyr) ⭐ 16,338 | 🐛 3,858 | 🌐 C | 📅 2026-08-28 - New generation, scalable, optimized, secure RTOS for multiple hardware architectures.
* [RT-Thread](https://github.com/RT-Thread/rt-thread) ⭐ 12,174 | 🐛 499 | 🌐 C | 📅 2026-08-28 - RT-Thread was born in 2006, it is an open source, neutral, and community-based real-time operating system (RTOS). RT-Thread has Standard version and Nano version. For resource-constrained microcontroller (MCU) systems, the NANO kernel version that requires only 3KB Flash and 1.2KB RAM memory resources can be tailored with easy-to-use tools; And for resource-rich IoT devices, RT-Thread can use the on-line software package management tool, together with system configuration tools, to achieve intuitive and rapid modular cutting, seamlessly import rich software packages, thus achieving complex functions like Android's graphical interface and touch sliding effects, smart voice interaction effects, and so on.
* 🔝[FreeRTOS™](https://github.com/FreeRTOS/FreeRTOS) ⭐ 7,734 | 🐛 33 | 🌐 C | 📅 2026-08-26 - FreeRTOS.
* [Tock Embedded OS](https://github.com/tock/tock) ⭐ 6,428 | 🐛 200 | 🌐 Rust | 📅 2026-08-28 - Embedded operating system designed for running multiple concurrent, mutually distrustful applications on low-memory and low-power microcontrollers *(Rust)*.
* [RIOT](https://github.com/RIOT-OS/RIOT) ⭐ 5,780 | 🐛 873 | 🌐 C | 📅 2026-08-28 - Real-time multi-threading operating system that supports a range of devices that are typically found in the Internet of Things (IoT): 8-bit, 16-bit and 32-bit microcontrollers. RIOT is based on the following design principles: energy-efficiency, real-time capabilities, small memory footprint, modularity, and uniform API access, independent of the underlying hardware (this API offers partial POSIX compliance).
* [Arm Mbed OS](https://github.com/ARMmbed/mbed-os) ⭐ 4,871 | 🐛 211 | 🌐 C | 📅 2024-10-08 - Platform operating system designed for the Internet of Things. It includes all the features you need to develop a connected product based on an Arm Cortex-M microcontroller, including security, connectivity, an RTOS and drivers for sensors and I/O devices.
* [Apache NuttX](https://github.com/apache/incubator-nuttx) ⭐ 4,013 | 🐛 748 | 🌐 C | 📅 2026-08-28 - Apache NuttX is a mature, real-time embedded operating system (RTOS).
* [Azure RTOS ThreadX](https://github.com/azure-rtos/threadx) ⭐ 3,518 | 🐛 107 | 🌐 C | 📅 2026-08-28 - Advanced real-time operating system (RTOS) designed specifically for deeply embedded applications.
* [embox](https://github.com/embox/embox) ⭐ 1,590 | 🐛 216 | 🌐 C | 📅 2026-08-28 - Configurable RTOS designed for resource constrained and embedded systems. Embox main idea is using Linux software without Linux.
* [QP/C](https://github.com/QuantumLeaps/qpc) ⭐ 1,359 | 🐛 4 | 🌐 C | 📅 2026-08-28 - Real-time embedded framework/RTOS for embedded systems based on active objects (actors) and hierarchical state machines (FuSa, MISRA-C 2023 compliance).
* [µC/OS-III](https://github.com/weston-embedded/uC-OS3) ⭐ 1,087 | 🐛 4 | 🌐 C | 📅 2026-07-15 - Preemptive, highly portable, and scalable real-time kernel. Designed for ease of use on a huge number of CPU architectures.
* [MuditaOS](https://github.com/mudita/MuditaOS) ⭐ 937 | 🐛 67 | 🌐 C | 📅 2026-06-13 - Mobile operating system based on FreeRTOS optimized for E Ink displays - developed for Mudita Pure minimalist phone.
* [ChibiOS/RT](https://github.com/ChibiOS/ChibiOS) ⭐ 860 | 🐛 21 | 🌐 C | 📅 2026-05-31 - Compact and fast real-time operating system supporting multiple architectures designed for embedded applications on microcontrollers of 8-, 16-, and 32-bits.
* [µC/OS-II](https://github.com/weston-embedded/uC-OS2) ⭐ 735 | 🐛 3 | 🌐 C | 📅 2023-01-05 - Preemptive, highly portable, and scalable real-time kernels. Designed for ease of use on a huge number of CPU architectures.
* [distortos](https://github.com/DISTORTEC/distortos) ⭐ 469 | 🐛 4 | 🌐 C++ | 📅 2026-07-16 - Object-oriented C++ RTOS for microcontrollers.
* [scmRTOS](https://github.com/scmrtos/scmrtos) ⭐ 277 | 🐛 2 | 🌐 C++ | 📅 2026-03-13 - Tiny Real-Time Preemptive Operating System intended for use with Single-Chip Microcontrollers. scmRTOS is capable to run on tiny uCs with as small amount of RAM as 512 bytes. The RTOS is written on C++ and supports various platforms.
* [R3-OS](https://github.com/r3-os/r3) ⭐ 176 | 🐛 7 | 🌐 Rust | 📅 2023-04-22 - Experimental static (μITRON-esque) RTOS for deeply embedded systems, testing the limit of Rust's const eval and generics *(Rust)*.
* [dandelion](https://github.com/AntoineSebert/dandelion) ⭐ 51 | 🐛 0 | 🌐 Rust | 📅 2023-04-11 - Microkernel Real-Time Operating System in Rust.
* [eCos](https://ecos.sourceware.org/) - Real-time operating system intended for embedded applications *(Closed source)*.
* [Quite Ok RTOS](https://github.com/arabine/qortos) - Tickless, minimal, 500 lines of code, 7 functions.

### Event based scheduler

* [vsf](https://github.com/vsfteam/vsf) ⭐ 335 | 🐛 1 | 🌐 C | 📅 2026-08-29 - Versaloon Software Framework - a tiny preemptive-capable event-driven incremental software framework for Embedded Systems.
* [lwevt](https://github.com/MaJerle/lwevt) ⭐ 197 | 🐛 0 | 🌐 C | 📅 2026-08-21 - Lightweight event management system for embedded systems.
* [uevloop](https://github.com/andsmedeiros/uevloop) ⭐ 116 | 🐛 1 | 🌐 C | 📅 2026-02-18 - Fast and lightweight event loop for embedded platforms.
* [async](https://github.com/eerimoq/async) ⭐ 34 | 🐛 0 | 🌐 C | 📅 2022-11-07 - Asynchronous framework in C for systems where low memory usage is important.
* [EventOS](https://github.com/natnqweb/EventOS) ⭐ 9 | 🐛 0 | 🌐 C | 📅 2023-11-26 - Event based system designed for Arduino Framework.
* [Protothreads](http://dunkels.com/adam/pt/) - Provide linear code execution for event-driven systems implemented in C designed for severely memory constrained systems, such as small embedded systems or wireless sensor network nodes.

## User Interface

### CLI

* [embedded-cli](https://github.com/funbiscuit/embedded-cli) ⭐ 380 | 🐛 9 | 🌐 C | 📅 2026-03-11 - Single-header CLI with history and autocompletion for embedded systems.
* [microshell](https://github.com/marcinbor85/microshell) ⭐ 363 | 🐛 8 | 🌐 C | 📅 2024-06-20 - Lightweight pure C implementation of virtual shell, compatible with VT100 terminal. Support root tree, run-time mounting paths, global commands, and much more.
* [microrl](https://github.com/Helius/microrl) ⭐ 295 | 🐛 16 | 🌐 C | 📅 2023-10-29 - Micro read line library for small and embedded devices with basic VT100 support.
* [terminal](https://github.com/JingoC/terminal) ⭐ 47 | 🐛 0 | 🌐 C | 📅 2025-07-02 - Command Line Interface for microcontrollers. Flexible terminal settings allow you to integrate it with any microcontroller, without much effort.
* [SerialMenu](https://github.com/sonyhome/SerialMenu) ⭐ 30 | 🐛 6 | 🌐 C++ | 📅 2019-11-15 - Arduino library to easily create menus on the serial console.
* [microsh](https://github.com/dimmykar/microsh) ⭐ 17 | 🐛 1 | 🌐 C | 📅 2023-10-22 - Shell for Small Embedded Devices.
* [terminal-server](https://github.com/NeoProg2013/terminal-server) ⭐ 15 | 🐛 0 | 🌐 C | 📅 2021-08-18 - Terminal server for MCU.
* [cli](https://github.com/letgo0007/cli) ⭐ 9 | 🐛 0 | 🌐 C | 📅 2018-12-20 - CLI (Command Line Interface) example build in pure C. Designed for MCU, support block/non-block mode input.
* [cmd-l](https://github.com/Lambosaurus/cmd-l) ⭐ 4 | 🐛 3 | 🌐 C | 📅 2021-10-14 - Command line handler for embedded devices.

### Menu

* [micromenu-v2](https://github.com/abcminiuser/micromenu-v2) ⭐ 82 | 🐛 4 | 🌐 Makefile | 📅 2019-04-26 - Tiny text-orientated menu library in C for embedded use.
* [ProMenu](https://github.com/marcinbor85/ProMenu) ⭐ 6 | 🐛 0 | 🌐 C++ | 📅 2020-08-30 - Advanced Generic Application Menu Library. ProMenu Library is used for fast implementing advanced user menus. It supports nesting, numeric settings, text settings, boolean values and events. Library is implemented in C++ with build-in Arduino port, but it is easy to port to different architecture.
* [BBmenu](https://github.com/vborchsh/bbmenu) ⭐ 4 | 🐛 0 | 🌐 C | 📅 2022-12-09 - Simple portable CLI menu for misc tasks (it is based on text menus, easily defined in a file).

### printf

* [fmt](https://github.com/fmtlib/fmt) ⭐ 23,766 | 🐛 16 | 🌐 C++ | 📅 2026-08-27 - Modern formatting library providing a fast and safe alternative to C stdio and C++ iostreams.
* [tiny-printf](https://github.com/mpaland/printf) ⭐ 3,056 | 🐛 66 | 🌐 C | 📅 2023-04-03 - Tiny, fast, non-dependent and fully loaded printf implementation for embedded systems. Extensive test suite passing.
* [nanoprintf](https://github.com/charlesnicholson/nanoprintf) ⭐ 844 | 🐛 7 | 🌐 C++ | 📅 2026-08-10 - The smallest public printf implementation for its feature set.
* [tiny-printf new](https://github.com/eyalroz/printf) ⭐ 636 | 🐛 13 | 🌐 C | 📅 2026-06-27 - Enhanced and maintained fork of `tiny-printf`. Tiny, fast(ish), self-contained and fully loaded printf, sprinf etc.
* [lwprintf](https://github.com/MaJerle/lwprintf) ⭐ 345 | 🐛 3 | 🌐 C | 📅 2026-08-21 - Lightweight printf library optimized for embedded systems.
* [tinyprintf](https://github.com/cjlano/tinyprintf) ⭐ 254 | 🐛 8 | 🌐 C | 📅 2023-10-29 - Tiny printf and sprintf library for small embedded systems.
* [emio](https://github.com/Viatorus/emio) ⭐ 188 | 🐛 16 | 🌐 C++ | 📅 2026-08-26 - Very small binary footprint std::format like formatting using C++20.
* [xprintf-fp](https://github.com/MarioViara/xprintfc) ⭐ 72 | 🐛 1 | 🌐 C | 📅 2022-11-28 - Printf for embedded system with floating point support.
* [Embedded\_Printf](https://github.com/agaelema/Embedded_Printf) ⭐ 7 | 🐛 0 | 🌐 C | 📅 2025-06-19 - Embedded version of the famous "printf( )" function. The idea is create an simple and efficient library to meet some common needs in embedded systems.
* [xprintf](https://github.com/robbesol/xprintf) ⭐ 7 | 🐛 1 | 🌐 C | 📅 2013-06-27 - Complete fprintf() formatting implementation, suitable for embedded use.
* [xprintf-io](https://github.com/sinferwu/xprintf) ⭐ 6 | 🐛 0 | 🌐 C | 📅 2021-05-31 - Compact string I/O library. It is ideal for tiny microcontrollers that has insufficient program memory for regular printf function. The recommended use is: writing formatted strings into LCD or UART and for debug/maintenance console.
* [mini-printf](https://github.com/ldoolitt/mini-printf) ⭐ 0 | 🐛 0 | 🌐 C | 📅 2020-06-18 - Minimal printf() implementation for embedded projects.

### scanf

* [scanf](https://github.com/hisahi/scanf) ⭐ 4 | 🐛 0 | 🌐 C | 📅 2021-07-11 - Portable implementation of scanf input functions in C.
* [ft\_scanf](https://github.com/cbarbier/ft_scanf) ⭐ 1 | 🐛 0 | 🌐 C | 📅 2017-03-08 - Simple scanf %s %c %d.

### Logging

* [spdlog](https://github.com/gabime/spdlog) ⭐ 29,540 | 🐛 50 | 🌐 C++ | 📅 2026-08-08 - Very fast, header-only/compiled, C++ logging library.
* [EasyLogger](https://github.com/armink/EasyLogger) ⭐ 4,736 | 🐛 81 | 🌐 C | 📅 2026-08-13 - Ultra-lightweight (ROM<1.6K, RAM<0.3k), high-performance C/C++ log library.
* [trice](https://github.com/rokath/trice) ⭐ 984 | 🐛 0 | 🌐 Go | 📅 2026-08-27 - Super fast and tiny embedded device C printf-like trace code (works also inside interrupts) and real-time PC logging (trace ID visualization).
* [elog](https://github.com/martinribelotta/elog) ⭐ 46 | 🐛 0 | 🌐 C | 📅 2026-05-18 - Log system is thinked for embedded systems with mininmal resource utilization. The log system is designed to minimize memory compsumition in flash or RAM, enable an eficient in-ram loggin buffer with very efficient storage.
* [embedded-log](https://github.com/to9/embedded-log) ⭐ 28 | 🐛 1 | 🌐 C | 📅 2023-11-23 - Small and beautiful embedded log library for mcu.
* [embedded-diagnostic-logger](https://github.com/binarymaker/embedded-diagnostic-logger) ⭐ 10 | 🐛 1 | 🌐 C | 📅 2020-01-14 - Lightweight logger framework for small microcontroller based projects. Multilevel log and token based string transfer.

## GUI

* [lvgl](https://github.com/lvgl/lvgl) ⭐ 24,521 | 🐛 220 | 🌐 C | 📅 2026-08-28 - Powerful and easy-to-use embedded GUI with many widgets, advanced visual effects (opacity, antialiasing, animations) and low memory requirements (16K RAM, 64K Flash).
* 🔝[u8g2](https://github.com/olikraus/u8g2) ⭐ 6,652 | 🐛 280 | 🌐 C | 📅 2026-08-23 - U8glib library for monochrome displays, version 2.
* [LovyanGFX](https://github.com/lovyan03/LovyanGFX/) ⭐ 1,744 | 🐛 16 | 🌐 C | 📅 2026-08-27 - Display (LCD / OLED / EPD) graphics library (for ESP32 SPI, I2C, 8bitParallel / ESP8266 SPI, I2C / RP2040 SPI / ATSAMD51 SPI and more).
* [UGUI (µGUI)](https://github.com/achimdoebler/UGUI) ⭐ 1,388 | 🐛 43 | 🌐 C | 📅 2023-10-29 - A graphic library. It supports color, grayscale, monochrome and multiple displays, touch screen, windows and objects, basic geometric primitives, fonts, console. There is no required dynamic allocation and memory for screen buffer. Documentation available on [developer's website](https://embeddedlightning.com/download/%c2%b5gui-v0-3/).
* [Embedded-graphics](https://github.com/embedded-graphics/embedded-graphics) ⭐ 1,333 | 🐛 89 | 🌐 Rust | 📅 2026-08-02 - 2D graphics library that is focused on memory constrained embedded devices to draw graphics without using any buffers (Rust).
* [HAGL](https://github.com/tuupola/hagl) ⭐ 465 | 🐛 20 | 🌐 C | 📅 2026-04-03 - Lightweight Hardware Agnostic Graphics Library for embedded devices. It supports basic geometric primitives, bitmaps, blitting, fixed width fonts. Library tries to stay lightweight but targets reasonably powerful microchips such as ESP32. There is no dynamic allocation.
* [GUIX](https://github.com/azure-rtos/guix) ⭐ 405 | 🐛 22 | 🌐 C | 📅 2026-08-28 - Provides a complete, embedded graphical user interface (GUI) library and design environment, facilitating the creation and maintenance of all graphical elements needed by your device.
* [EasyGUI](https://github.com/MaJerle/EasyGUI) ⭐ 185 | 🐛 2 | 🌐 C | 📅 2021-11-25 - EasyGUI for embedded systems (highly optimized for STM32).
* [MakiseGUI](https://github.com/SL-RU/MakiseGUI) ⭐ 136 | 🐛 6 | 🌐 C | 📅 2021-05-07 - Graphics and GUI library for embed systems.
* [eGUI](https://github.com/NXPmicro/eGUI) ⭐ 83 | 🐛 6 | 🌐 C | 📅 2017-12-11 - An eGUI embedded graphic library.
* [emGUI](https://github.com/libEmGUI/emGUI) ⭐ 41 | 🐛 4 | 🌐 C | 📅 2018-01-24 - Simple C UI Library for embedded platforms.
* [AFGUI](https://github.com/AndreyFursov/AFGUI) ⭐ 27 | 🐛 0 | 🌐 C | 📅 2016-02-23 - Embedded GUI Library.
* [SGFX](https://github.com/rprata/sgfx) ⭐ 24 | 🐛 5 | 🌐 C | 📅 2020-05-27 - Lightweight embedded library for displays and touchscreens providing everything required to build a fully featured embedded GUI.
* [ESLowGraphics](https://github.com/errorcalc/ESLowGraphicsLibrary) ⭐ 19 | 🐛 2 | 🌐 C | 📅 2018-04-07 - Low level software graphics library by ErrorSoft (ESLGL).
* [u8glib](https://github.com/pabigot/u8glib) ⚠️ Archived - Universal Graphics Library for 8 Bit Embedded Systems.
* [HMI\_Library](https://github.com/kgrze/HMI_Library) ⭐ 11 | 🐛 0 | 🌐 C | 📅 2013-06-02 - Human Machine Interface suitable for embedded system.
* [ftk](https://github.com/prife/ftk) ⭐ 8 | 🐛 1 | 🌐 C | 📅 2016-01-15 - GUI library for embedded system.
* [GUILib](https://github.com/Nikolay-Kha/GUILib) ⭐ 8 | 🐛 1 | 🌐 C | 📅 2015-10-25 - GUI library for embedded systems.
* [TouchGFX](https://www.touchgfx.com/product/overview/) - User-friendly graphical C++ tool integrated as a free tool in the STM32 ecosystem.

### GUI editors

* [walv](https://github.com/kaiakz/walv) ⭐ 116 | 🐛 9 | 🌐 HTML | 📅 2020-07-12 - Online, WYSIWYG GUI designer for LittlevGL. Cross-platform supported(Even Android and IOS).
* [lv\_gui\_designer](https://github.com/kaiakz/lv_gui_designer) ⚠️ Archived - Drag-and-drop, simple GUI designer built with LittlevGL.

### Font utils

* [mcufont](https://github.com/mcufont/mcufont) ⭐ 418 | 🐛 4 | 🌐 C | 📅 2026-07-25 - A font rendering library for microcontrollers.
* [ttf2mesh](https://github.com/fetisov/ttf2mesh) ⭐ 233 | 🐛 12 | 🌐 C++ | 📅 2024-06-26 - Library for TrueType font tessellation. Allows to convert font glyphs to mesh objects without rasterization.
* [sfam\_generator](https://github.com/SL-RU/sfam_generator) ⭐ 18 | 🐛 0 | 🌐 Python | 📅 2016-03-23 - Simple scripts for generating bit fonts for STM32, AVR, Arduino or other MCU.
* [bitmap-OSD-font](https://github.com/frisnit/bitmap-OSD-font) ⭐ 6 | 🐛 0 | 🌐 C | 📅 2023-11-16 - A 'C' bitmap font for on screen display.

#### Fonts and Icons

* [picon](https://github.com/yne/picon) ⭐ 29 | 🐛 0 | 🌐 HTML | 📅 2024-05-01 - Pico-icon set with Hackable Ligature (Designed on a 8-grid: to be readable at 8px 16px 24px 32px 48px).

### Picture manupulation tools

* [lcd-image-converter](https://github.com/riuson/lcd-image-converter) ⭐ 404 | 🐛 6 | 🌐 C++ | 📅 2025-12-26 - Tool to create bitmaps and fonts for embedded applications; allows you to create bitmaps and fonts, and transform them to "C" source format for embedded applications.

## Hardware

* [embedded-driver](https://github.com/InfiniteYuan/embedded-driver-library) ⭐ 15 | 🐛 0 | 🌐 C | 📅 2020-12-10 - Embedded driver library for various peripheral.

### IO

* [FastIO](https://github.com/xillion/FastIO) ⭐ 0 | 🐛 0 | 🌐 C | 📅 2020-11-17 - Fast GPIO forked from <http://os.mbed.com/users/Sissors/code/FastIO/> .

### USB

* [tinyusb](https://github.com/hathach/tinyusb) ⭐ 7,066 | 🐛 251 | 🌐 C | 📅 2026-08-28 - Cross-platform USB stack for embedded system.
* [libusb\_stm32](https://github.com/dmitrystu/libusb_stm32) ⭐ 826 | 🐛 29 | 🌐 C | 📅 2025-10-06 - Lightweight USB device Stack for STM32 microcontrollers.
* [CherryUSB](https://github.com/CherryUSB) - Tiny, beautiful and portable USB host and device stack for embedded system with USB.

### Flash

* [SFUD](https://github.com/armink/SFUD) ⭐ 1,715 | 🐛 33 | 🌐 C | 📅 2025-05-30 - Serial Flash Universal Driver (using JEDEC's SFDP standard serial (SPI) flash universal driver library).

### CAN bus

* [CanBoot](https://github.com/Arksine/CanBoot) ⭐ 672 | 🐛 81 | 🌐 C | 📅 2026-03-20 -  Can Bootloader for MCUs (Currently lpc176x, stm32 and rp2040 MCUs are supported).
* [libcanard](https://github.com/UAVCAN/libcanard) ⭐ 446 | 🐛 0 | 🌐 C | 📅 2026-07-02 - Compact implementation of the UAVCAN/CAN protocol in C for high-integrity real-time embedded systems.
* [Canbus-Message](https://github.com/ReFil/Canbus-Message) ⭐ 2 | 🐛 0 | 🌐 C++ | 📅 2021-03-05 - CAN message assembly and disassembly library for teensy & stm32.

### Sensors

* [stm32-async-1wire](https://github.com/a5021/stm32-async-1wire) ⭐ 10 | 🐛 0 | 🌐 C | 📅 2026-08-28 - Non-blocking, register-level 1-Wire master for STM32 (DS18B20 temperature driver on top). Hardware-timed (TIM1+DMA, DMAMUX on G0), interrupt-free, RTOS-agnostic; header-only backends for STM32F1/F0/G0; hardware-validated on Blue Pill (F103) and STM32G031; strong-pull-up parasite powering; released v1.6.1.

## Others

### Thread management

* [C-Thread-Pool](https://github.com/Pithikos/C-Thread-Pool) ⭐ 2,361 | 🐛 29 | 🌐 C | 📅 2025-05-18 - Minimal but powerful thread pool in ANSI C.

### Bootloaders

* [mcuboot](https://github.com/mcu-tools/mcuboot) ⭐ 2,047 | 🐛 102 | 🌐 C | 📅 2026-08-13 - Secure boot for 32-bit Microcontrollers.
* [OpenBLT](https://github.com/feaser/openblt) ⭐ 969 | 🐛 0 | 🌐 C | 📅 2026-07-14 - Open source bootloader for STM32, XMC, HCS12 and other microcontroller targets. It supports communication interfaces such as: RS232, CAN, USB, TCP/IP and it ships with the easy-to-use [MicroBoot](https://www.feaser.com/openblt/doku.php?id=manual:microboot) PC tool for initiating and monitoring the firmware update. Performing firmware updates directly from an SD-card is also supported.
* [wolfBoot](https://github.com/wolfSSL/wolfBoot) ⭐ 527 | 🐛 13 | 🌐 C | 📅 2026-08-28 - Portable, OS-agnostic, secure bootloader for microcontrollers, supporting firmware authentication and firmware update mechanisms.
* [TinyUF2](https://github.com/adafruit/tinyuf2) ⭐ 470 | 🐛 15 | 🌐 C | 📅 2026-08-13 - Bootloader based on TinyUSB for embedded devices such as ESP32, STM32 and iMX RT10xx.

### Firmware updates

* [SWupdate](https://github.com/sbabic/swupdate) ⭐ 1,860 | 🐛 11 | 🌐 C | 📅 2026-08-19 - Software Update for Embedded Linux Devices to update system in field. SWUpdate supports local and OTA updates, multiple update strategies and it is designed with security in mind.
* [UF2](https://github.com/microsoft/uf2) ⭐ 1,030 | 🐛 24 | 🌐 JavaScript | 📅 2026-02-08 - USB Flashing Format specification for flashing microcontrollers over MSC (Mass Storage Class; aka removable flash drive).

### Touch Screen

* [tslib](https://github.com/libts/tslib) ⭐ 673 | 🐛 42 | 🌐 C | 📅 2025-11-05 - Touchscreen access library.

### Time Management Libs

* [μtz](https://github.com/evq/utz) ⭐ 39 | 🐛 7 | 🌐 C | 📅 2020-04-22 - Time zone library for tiny embedded systems.
* [TimeLib](https://github.com/geekfactory/TimeLib) ⭐ 14 | 🐛 1 | 🌐 C | 📅 2019-04-21 - Time management library for embedded devices.

### Embeddable Scripts and Languages

* [little](https://github.com/Beariish/little) ⭐ 309 | 🐛 5 | 🌐 C | 📅 2023-09-07 - A small, fast, easily embeddable language implemented in a single .c file.

## Compilers

* [TinyGo](https://github.com/tinygo-org/tinygo) ⭐ 17,676 | 🐛 565 | 🌐 Go | 📅 2026-08-28 - Go compiler for small things: Microcontrollers, WebAssembly (WASM/WASI), and command-line tools (Based on LLVM).
* [chibicc](https://github.com/rui314/chibicc) ⭐ 11,857 | 🐛 127 | 🌐 C | 📅 2023-10-30 - Yet another small C compiler that implements most C11 features.
* [lcc](https://github.com/drh/lcc) ⭐ 2,612 | 🐛 43 | 🌐 C | 📅 2024-10-06 - Retargetable ANSI C Compiler (fork for [ULP in ESP32](https://github.com/jasonful/lcc) ⭐ 99 | 🐛 3 | 🌐 C | 📅 2021-05-29).
* [pcc](http://pcc.ludd.ltu.se/) - Portable C Compiler ([mirror](https://github.com/IanHarvey/pcc) ⭐ 139 | 🐛 4 | 🌐 C | 📅 2024-08-01).
* [rvcc](https://github.com/mausimus/rvcc) ⭐ 100 | 🐛 0 | 🌐 C | 📅 2024-05-01 - Bootstrapped C compiler for 32-bit RISC-V and ARM ISAs (generates executable Linux ELF binaries for RV32IM and ARMv7).
* [SDCC](https://sdcc.sourceforge.net/) - Small Device C Compiler (that targets the Intel MCS51 based microprocessors (8031, 8032, 8051, 8052, etc.), Maxim (formerly Dallas) DS80C390 variants, Freescale (formerly Motorola) HC08 based (hc08, s08), Zilog Z80 based MCUs (Z80, Z180, SM83, Rabbit 2000, 2000A, 3000A, TLCS-90), Padauk (pdk14, pdk15) and STMicroelectronics STM8).
* [tcc](https://bellard.org/tcc/) - Tiny C Compiler (\~ 100KB for x86 TCC executable, including C preprocessor, C compiler, assembler and linker).

## Uncategorized

* [incbin](https://github.com/graphitemaster/incbin) ⭐ 1,186 | 🐛 10 | 🌐 C | 📅 2025-05-26 - One-header library for compile-time embedding binary and textual files.
* [modm](https://github.com/modm-io/modm) ⭐ 963 | 🐛 68 | 🌐 C++ | 📅 2026-08-07 - Barebone embedded C++20 library generator for AVR, SAM and ARM Cortex-M Microcontrollers (supported 3534 devices).
* [Apache NuttX Apps](https://github.com/apache/incubator-nuttx-apps) ⭐ 458 | 🐛 62 | 🌐 C | 📅 2026-08-28 - Collection of tools, shells, network utilities, libraries, interpreters and can be used with the NuttX RTOS.
* [WTX](https://github.com/c410-f3r/wtx) ⭐ 399 | 🐛 6 | 🌐 Rust | 📅 2026-08-23 - A set of web-oriented tools.
* [cembed](https://github.com/rxi/cembed) ⭐ 129 | 🐛 1 | 🌐 C | 📅 2024-04-07 - Small utility for embedding files in a C header.

***

## Contributing

* Your contributions are always welcome! Please read the [contribution guidelines](contributing.md) first.

## Footnotes

Please follow [this](https://github.com/iDoka/awesome-embedded-software) ⭐ 1,101 | 🐛 0 | 📅 2026-08-27 root-repo for lastest updates.

<!--
## Tags

#awesome
#awesome-list
#embedded
#embedded-systems
#rtos
#stm32
#cortex-m
#risc-v
#mcu
#uc
#lightweight
#gui
#iot
#crossplatform
#portable
#lightweight-embedded-library
#embedded-library
-->

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-29._
