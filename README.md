# Objdump Highlighting for TextMate

##What

Syntax grammar that matches various parts of `objdump` listings. Includes support for highlighting some ARM instructions and registers (including sp, ip, pc).

Section name extraction works, as do the "Go to symbol" shortcuts.

## Installing

Double click the Bundle file & TextMate will install it  `~/Library/Application Support/Avian`.

## Issues

* Not all ARM instructions are supported - only those that cropped up in a binary I had to hand.
* No support for other architectures - most x86 instructions aren't highlighted, nor are registers or prefixes.
* No support for different hex dump formats. (ARM instructions are dumped as 4 hex bytes, while x86 are space-separated hex bytes).