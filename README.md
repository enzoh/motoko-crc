## The CRC Package

[![Build Status](https://github.com/enzoh/motoko-crc/workflows/build/badge.svg)](https://github.com/enzoh/motoko-crc/actions?query=workflow%3Abuild)

This package implements cyclic redundancy checks for the Motoko programming language.

### Prerequisites

- [DFINITY SDK](https://sdk.dfinity.org/docs/download.html) v0.5.11
- [Vessel](https://github.com/kritzcreek/vessel/releases/tag/v0.4.1) v0.4.1 (Optional)

### Usage

Calculate an 8-bit cyclic redundancy check.
```motoko
public func crc8(data : [Word8]) : Word8
```

Calculate a 32-bit cyclic redundancy check.
```motoko
public func crc32(data : [Nat8]) : [Nat8]
```