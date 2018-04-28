# Questions

## What's `stdint.h`?

Is a header file in the C standard library.
It allows programmers to write "more portable code by providing a set of typedefs that specify exact-width integer types,
together with the defined minimum and maximum allowable values for each type, using macros ."

## What's the point of using `uint8_t`, `uint32_t`, `int32_t`, and `uint16_t` in a program?

`uint8_t` is the same as a byte. its shorthand for: a type of unsigned integer of length 8 bits

## How many bytes is a `BYTE`, a `DWORD`, a `LONG`, and a `WORD`, respectively?

There is 1 btye in a byte. There are 32 bytes in a DWORD(Couble word). There are 8 bytes in a long. A word can hold different numbers of bytes(8, 16, 32,64).

## What (in ASCII, decimal, or hexadecimal) must the first two bytes of any BMP file be? Leading bytes used to identify file formats (with high probability) are generally called "magic numbers."

TODO

## What's the difference between `bfSize` and `biSize`?

TODO

## What does it mean if `biHeight` is negative?

TODO

## What field in `BITMAPINFOHEADER` specifies the BMP's color depth (i.e., bits per pixel)?

TODO

## Why might `fopen` return `NULL` in lines 24 and 32 of `copy.c`?

TODO

## Why is the third argument to `fread` always `1` in our code?

TODO

## What value does line 63 of `copy.c` assign to `padding` if `bi.biWidth` is `3`?

TODO

## What does `fseek` do?

TODO

## What is `SEEK_CUR`?

TODO
