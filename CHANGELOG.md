# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2025-01-08

### Changed
- Move module repository path to clibrary/llimpl
- Remove top level folder and unused files

## [0.2.0] - 2024-12-10

### Fixed
- Overflow of integer leading to undefined behavior.
- MISRA C:2012 compliance of microej_time_freertos.c.

### Changed
- Uncrustify: Apply MicroEJ coding rules.

## [0.1.0] - 2022-01-19
### Added
- MicroEJ Time implementation for FreeRTOS.

### Fixed
- Overflow in time to tick and tick to time conversions.

---  
_Copyright 2022-2025 MicroEJ Corp. All rights reserved._  
_Use of this source code is governed by a BSD-style license that can be found with this software._  
