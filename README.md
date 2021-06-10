# compiler_in_docker
List of my docker image with compiler

## C or C++ Compiler

| Host arch  | Target arch | Workflow status  |
|:-------------:|:-------------:|:-----:|
| AMD64, ARMv8      | AMD64, ARMv8 | [![docker-tinycc](https://github.com/bensuperpc/docker-tinycc/actions/workflows/main.yml/badge.svg)](https://github.com/bensuperpc/docker-tinycc/actions/workflows/main.yml) |
| AMD64, ARMv8, I386 | ARMv8, I386 | [![docker-pcc-revived](https://github.com/bensuperpc/docker-pcc-revived/actions/workflows/main.yml/badge.svg)](https://github.com/bensuperpc/docker-pcc-revived/actions/workflows/main.yml) | 
| AMD64, ARMv8, I386 | AMD64, ARMv8, I386 | [![docker-lacc](https://github.com/bensuperpc/docker-lacc/actions/workflows/main.yml/badge.svg)](https://github.com/bensuperpc/docker-lacc/actions/workflows/main.yml) |
| AMD64, ARMv8 | AMD64, ARMv8      | [![docker-cproc](https://github.com/bensuperpc/docker-cproc/actions/workflows/main.yml/badge.svg)](https://github.com/bensuperpc/docker-cproc/actions/workflows/main.yml) |
| AMD64 | AMD64 | [![docker-clang](https://github.com/bensuperpc/docker-clang/actions/workflows/main.yml/badge.svg)](https://github.com/bensuperpc/docker-clang/actions/workflows/main.yml) |
| AMD64 | AMD64 | [![docker-subc](https://github.com/bensuperpc/docker-subc/actions/workflows/main.yml/badge.svg)](https://github.com/bensuperpc/docker-subc/actions/workflows/main.yml) |
| AMD64 | AMD64 | [![docker-shivyc](https://github.com/bensuperpc/docker-ShivyC/actions/workflows/main.yml/badge.svg)](https://github.com/bensuperpc/docker-ShivyC/actions/workflows/main.yml)|
| All* | Gameboy | [![docker-rgbds](https://github.com/bensuperpc/docker-rgbds/actions/workflows/main.yml/badge.svg)](https://github.com/bensuperpc/docker-rgbds/actions/workflows/main.yml) |
| AMD64 | Ti-NSpire | [![docker-ndless](https://github.com/bensuperpc/Docker-Ndless/actions/workflows/main.yml/badge.svg)](https://github.com/bensuperpc/Docker-Ndless/actions/workflows/main.yml) |
| AMD64 | AMD64 | [![docker-chibicc](https://github.com/bensuperpc/docker-chibicc/actions/workflows/main.yml/badge.svg)](https://github.com/bensuperpc/docker-chibicc/actions/workflows/main.yml) |
| AMD64 | AMD64 | [![docker-mzcc](https://github.com/bensuperpc/docker-MazuCC/actions/workflows/main.yml/badge.svg)](https://github.com/bensuperpc/docker-MazuCC/actions/workflows/main.yml) |
| All* | Z80      | [![docker-sjasmplus](https://github.com/bensuperpc/docker-sjasmplus/actions/workflows/main.yml/badge.svg)](https://github.com/bensuperpc/docker-sjasmplus/actions/workflows/main.yml) | 
| All* | 6502  | [![cc65](https://github.com/bensuperpc/cc65-docker/actions/workflows/main.yml/badge.svg)](https://github.com/bensuperpc/cc65-docker/actions/workflows/main.yml) | 
| All* | AMD64, ARMv8... | [![docker-ppci](https://github.com/bensuperpc/docker-ppci/actions/workflows/main.yml/badge.svg)](https://github.com/bensuperpc/docker-ppci/actions/workflows/main.yml)| 
| AMD64, I386 | SNES | [![pvsneslib-docker](https://github.com/bensuperpc/pvsneslib-docker/actions/workflows/main.yml/badge.svg)](https://github.com/bensuperpc/pvsneslib-docker/actions/workflows/main.yml) |
| AMD64, I386 | I386 | [![docker-ack](https://github.com/bensuperpc/docker-ack/actions/workflows/main.yml/badge.svg)](https://github.com/bensuperpc/docker-ack/actions/workflows/main.yml) |
| 1 | 2 | 3 |

All = AMD64, I386, ARMv8, ARMv7, ARMv6, s390x, ppc64le

## Brainfuck Compiler

| Host arch  | Target arch | Workflow status  |
|:-------------:|:-------------:|:-----:|
| All | All | [![docker-brainfuck](https://github.com/bensuperpc/docker-brainfuck/actions/workflows/main.yml/badge.svg)](https://github.com/bensuperpc/docker-brainfuck/actions/workflows/main.yml) |
| All | All | [![docker-brainfuck-tritium](https://github.com/bensuperpc/docker-brainfuck-tritium/actions/workflows/main.yml/badge.svg)](https://github.com/bensuperpc/docker-brainfuck-tritium/actions/workflows/main.yml) |
