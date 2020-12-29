# BM

![birch](./assets/birch-296x328.png)

Birtual Machine for [Ebisp](https://github.com/tsoding/ebisp)

## Quick Start

```console
$ make
$ make examples
$ ./bme ./examples/fibs.bm
```

## Components

### basm

Assembly language for the Virtual Machine. For examples see [./examples/](./examples) folder.

### bme

BM emulator. Used to run programs generated by [basm](#basm).
