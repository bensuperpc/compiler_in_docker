# compiler_in_docker
List of my docker image with compiler

## C or C++ Compiler and ASM

| Compiler name | Host arch  | Target arch | Language support | Workflow status  |
|:-------:|:--------:|:------:|:-----:|:-----:|
| tinycc | AMD64, ARMv8 | AMD64, ARMv8 | C99 and part of C11 | [![docker-tinycc](https://github.com/bensuperpc/docker-tinycc/actions/workflows/main.yml/badge.svg)](https://github.com/bensuperpc/docker-tinycc/actions/workflows/main.yml) |
| pcc-revived | AMD64, ARMv8, I386 | ARMv8, I386 | C99 | [![docker-pcc-revived](https://github.com/bensuperpc/docker-pcc-revived/actions/workflows/main.yml/badge.svg)](https://github.com/bensuperpc/docker-pcc-revived/actions/workflows/main.yml) | 
| open64 | AMD64 | AMD64 | C++03 and C99 | [![docker-open64](https://github.com/bensuperpc/docker-open64/actions/workflows/main.yml/badge.svg)](https://github.com/bensuperpc/docker-open64/actions/workflows/main.yml) |
| ack | AMD64, I386 | I386 | C99 | [![docker-ack](https://github.com/bensuperpc/docker-ack/actions/workflows/main.yml/badge.svg)](https://github.com/bensuperpc/docker-ack/actions/workflows/main.yml) |
| clang | AMD64 | AMD64 | C++20 and C17 | [![docker-clang](https://github.com/bensuperpc/docker-clang/actions/workflows/main.yml/badge.svg)](https://github.com/bensuperpc/docker-clang/actions/workflows/main.yml) |
| lacc | AMD64, ARMv8, I386 | AMD64, ARMv8, I386 | C99 | [![docker-lacc](https://github.com/bensuperpc/docker-lacc/actions/workflows/main.yml/badge.svg)](https://github.com/bensuperpc/docker-lacc/actions/workflows/main.yml) |
| tendra | AMD64 | I386 | C89/C99 | [![docker-tendra](https://github.com/bensuperpc/docker-tendra/actions/workflows/main.yml/badge.svg)](https://github.com/bensuperpc/docker-tendra/actions/workflows/main.yml) |
| cproc | AMD64, ARMv8 | AMD64, ARMv8 | C11 | [![docker-cproc](https://github.com/bensuperpc/docker-cproc/actions/workflows/main.yml/badge.svg)](https://github.com/bensuperpc/docker-cproc/actions/workflows/main.yml) |
| subc | AMD64 | AMD64 | C99 | [![docker-subc](https://github.com/bensuperpc/docker-subc/actions/workflows/main.yml/badge.svg)](https://github.com/bensuperpc/docker-subc/actions/workflows/main.yml) |
| ShivyC | AMD64 | AMD64 |  C99 (WIP) | [![docker-shivyc](https://github.com/bensuperpc/docker-ShivyC/actions/workflows/main.yml/badge.svg)](https://github.com/bensuperpc/docker-ShivyC/actions/workflows/main.yml)|
| rgbds | All* | Gameboy | ASM | [![docker-rgbds](https://github.com/bensuperpc/docker-rgbds/actions/workflows/main.yml/badge.svg)](https://github.com/bensuperpc/docker-rgbds/actions/workflows/main.yml) |
| Ndless | AMD64 | Ti-NSpire | C11 | [![docker-ndless](https://github.com/bensuperpc/Docker-Ndless/actions/workflows/main.yml/badge.svg)](https://github.com/bensuperpc/Docker-Ndless/actions/workflows/main.yml) |
| chibicc | AMD64 | AMD64 | C99 (WIP) | [![docker-chibicc](https://github.com/bensuperpc/docker-chibicc/actions/workflows/main.yml/badge.svg)](https://github.com/bensuperpc/docker-chibicc/actions/workflows/main.yml) |
| MazuCC | AMD64 | AMD64 | C99 | [![docker-mzcc](https://github.com/bensuperpc/docker-MazuCC/actions/workflows/main.yml/badge.svg)](https://github.com/bensuperpc/docker-MazuCC/actions/workflows/main.yml) |
| sjasmplus | All* | Z80 | ASM | [![docker-sjasmplus](https://github.com/bensuperpc/docker-sjasmplus/actions/workflows/main.yml/badge.svg)](https://github.com/bensuperpc/docker-sjasmplus/actions/workflows/main.yml) | 
| cc65 | All* | 6502  | C99 (WIP) | [![cc65](https://github.com/bensuperpc/cc65-docker/actions/workflows/main.yml/badge.svg)](https://github.com/bensuperpc/cc65-docker/actions/workflows/main.yml) | 
| ppci | All* | AMD64, ARMv8... | C99 (WIP) | [![docker-ppci](https://github.com/bensuperpc/docker-ppci/actions/workflows/main.yml/badge.svg)](https://github.com/bensuperpc/docker-ppci/actions/workflows/main.yml)| 
| pvsneslib | AMD64, I386 | SNES | C99 (WIP) | [![pvsneslib-docker](https://github.com/bensuperpc/pvsneslib-docker/actions/workflows/main.yml/badge.svg)](https://github.com/bensuperpc/pvsneslib-docker/actions/workflows/main.yml) |
| 1 | 2 | 3 | 4 | 5 |


All = AMD64, I386, ARMv8, ARMv7, ARMv6, s390x, ppc64le

## Brainfuck Compiler

| Compiler name | Host arch  | Target arch | Workflow status  |
|:-------:|:--------:|:--------:|:-----:|
| brainfuck | All | All | [![docker-brainfuck](https://github.com/bensuperpc/docker-brainfuck/actions/workflows/main.yml/badge.svg)](https://github.com/bensuperpc/docker-brainfuck/actions/workflows/main.yml) |
| brainfuck-tritium | All | All | [![docker-brainfuck-tritium](https://github.com/bensuperpc/docker-brainfuck-tritium/actions/workflows/main.yml/badge.svg)](https://github.com/bensuperpc/docker-brainfuck-tritium/actions/workflows/main.yml) |

All = AMD64, I386, ARMv8, ARMv7, ARMv6, s390x, ppc64le

## Whitespace Compiler

| Compiler name | Host arch  | Target arch | Workflow status  |
|:-------:|:--------:|:--------:|:-----:|
| whitespace | AMD64, I386 | AMD64, I386 | [![docker-whitespace](https://github.com/bensuperpc/docker-whitespace/actions/workflows/main.yml/badge.svg)](https://github.com/bensuperpc/docker-whitespace/actions/workflows/main.yml) |

All = AMD64, I386, ARMv8, ARMv7, ARMv6, s390x, ppc64le

