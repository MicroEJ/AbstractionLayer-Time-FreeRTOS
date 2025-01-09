# Overview
MicroEJ Time Abstraction Layer implementation for FreeRTOS.

This module implements the `microej_time.h` APIs for MicroEJ Platforms connected to a Board Support Package based on FreeRTOS.

# Usage
These sources can be included in the VEE Port with the method you prefer, by using this repository as a submodule or by doing a copy of the sources in the VEE Port repository.

# Requirements
N/A

# Validation

- Hardware
    - [ESP32-S2-Saola](https://docs.espressif.com/projects/esp-idf/en/latest/esp32s2/hw-reference/esp32s2/user-guide-saola-1-v1.2.html) (**Tested up to 0.1.0 release**)
    - [i.MX RT1170 Evaluation Kit](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/i-mx-rt1170-evaluation-kit:MIMXRT1170-EVKB)
- Compiler / Build environment
    - xtensa-esp32-elf-gcc 8.4.0 / [ESP-IDF v4.2.2](https://github.com/espressif/esp-idf/tree/v4.2.2) (**Tested up to 0.1.0 release**)
    - [MCUXpresso SDK 2.15.0](https://mcuxpresso.nxp.com/en) for i.MXRT1170-EVKB (using GNU GCC toolchain)
- RTOS
    - FreeRTOS 8.2.0 (**Tested up to 0.1.0 release**)
    - FreeRTOS 10.4.3

# MISRA Compliance


This Abstraction Layer implementation is MISRA-compliant (MISRA C:2012) with some noted exception.
It has been verified with Cppcheck v2.10. Here is the list of deviations from MISRA standard:

| Deviation   | Category | Justification                                                      |
|:-----------:|:--------:|:------------------------------------------------------------------ |
|  Rule 10.4  | Required | Intentional usage of different operators to check an overflow.     |


# Dependencies
N/A

# Source
N/A

# Restrictions
This implementation is not compatible with FreeRTOS tickless idle mode.

---

_Copyright 2022-2025 MicroEJ Corp. All rights reserved._  
_Use of this source code is governed by a BSD-style license that can be found with this software._  
