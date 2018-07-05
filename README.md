# μEVM (Micro Ethereum Virtual Machine)

Highly-portable Ethereum VM distributed as a single header file
with no dependencies and licensed under public domain.

## Features

- Single header file written in C89 (ANSI C)
- Focus on portability, efficiency and simplicity
- No dependencies (not even the standard library if not wanted)

## Usage

μEVM is self contained in one single header file and can be used either
in header only mode (by default) or in implementation mode (is activated
by requires the preprocessor macro `UEVM_IMPLEMENTATION`), e.g.:

```c
#define UEVM_IMPLEMENTATION
#include "uevm.h"
```

## Example

TBD

## Building

TBD

## Unlicensed

μEVM is free and unencumbered public domain software,
for more information, see http://unlicense.org/.
