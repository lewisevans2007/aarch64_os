# AARCH64 OS

This is a simple OS for the aarch64 architecture. It is written in C and assembly.

Most of the help for this project came from [OS Dev](https://wiki.osdev.org/).

## Building

To build the OS, you need to have the following installed:
- [aarch64-linux-gnu-gcc](https://packages.ubuntu.com/focal/aarch64-linux-gnu-gcc)
- [aarch64-linux-gnu-binutils](https://packages.ubuntu.com/focal/aarch64-linux-gnu-binutils)
- [GNU Make](https://www.gnu.org/software/make/)
- [QEMU](https://www.qemu.org/)

To build the OS, run `make` in the root directory of the project.

## Running

To run the project in qemu run `make run`. This will run the OS in qemu
## Hexdump of image
```
0000000 457f 464c 0102 0001 0000 0000 0000 0000
0000010 0002 00b7 0001 0000 0000 4000 0000 0000
0000020 0040 0000 0000 0000 0408 0001 0000 0000
0000030 0000 0000 0040 0038 0002 0040 000a 0009
0000040 0001 0000 0007 0000 0000 0001 0000 0000
0000050 0000 4000 0000 0000 0000 4000 0000 0000
0000060 0150 0000 0000 0000 0150 0000 0000 0000
0000070 0000 0001 0000 0000 e551 6474 0006 0000
0000080 0000 0000 0000 0000 0000 0000 0000 0000
*
00000a0 0000 0000 0000 0000 0010 0000 0000 0000
00000b0 0000 0000 0000 0000 0000 0000 0000 0000
*
0010000 00de 5800 03df 9100 0000 d280 0021 9400
0010010 0000 1400 0000 0000 1150 4000 0000 0000
0010020 43ff d100 3fe0 3900 0000 9000 2000 9105
0010030 0000 f940 3fe1 3940 0001 3900 201f d503
0010040 43ff 9100 03c0 d65f 7bfd a9be 03fd 9100
0010050 0fe0 f900 0007 1400 0fe0 f940 0000 3940
0010060 fff0 97ff 0fe0 f940 0400 9100 0fe0 f900
0010070 0fe0 f940 0000 3940 001f 7100 fee1 54ff
0010080 201f d503 201f d503 7bfd a8c2 03c0 d65f
0010090 7bfd a9bf 03fd 9100 0000 9000 c000 9102
00100a0 ffea 97ff 201f d503 7bfd a8c1 03c0 d65f
00100b0 6557 636c 6d6f 2065 6f74 7420 6968 2073
00100c0 6973 706d 656c 6120 7261 6863 3436 4f20
00100d0 2153 000a 0000 0000 0010 0000 0000 0000
00100e0 7a01 0052 7804 011e 0c1b 001f 0014 0000
00100f0 0018 0000 ff2c ffff 0028 0000 4100 100e
0010100 0e48 0000 001c 0000 0030 0000 ff3c ffff
0010110 0048 0000 4100 200e 049d 039e de50 0edd
0010120 0000 0000 001c 0000 0050 0000 ff64 ffff
0010130 0020 0000 4100 100e 029d 019e de46 0edd
0010140 0000 0000 0000 0000 0000 0900 0000 0000
0010150 4347 3a43 2820 6255 6e75 7574 3120 2e31
0010160 2e33 2d30 7531 7562 746e 3175 327e 2e32
0010170 3430 2029 3131 332e 302e 0000 0000 0000
0010180 0000 0000 0000 0000 0000 0000 0000 0000
0010190 0000 0000 0000 0000 0000 0000 0003 0001
00101a0 0000 4000 0000 0000 0000 0000 0000 0000
00101b0 0000 0000 0003 0002 0020 4000 0000 0000
00101c0 0000 0000 0000 0000 0000 0000 0003 0003
00101d0 00b0 4000 0000 0000 0000 0000 0000 0000
00101e0 0000 0000 0003 0004 00d8 4000 0000 0000
00101f0 0000 0000 0000 0000 0000 0000 0003 0005
0010200 0148 4000 0000 0000 0000 0000 0000 0000
0010210 0000 0000 0003 0006 0000 0000 0000 0000
0010220 0000 0000 0000 0000 0001 0000 0004 fff1
0010230 0000 0000 0000 0000 0000 0000 0000 0000
0010240 0008 0000 0000 0001 0000 4000 0000 0000
0010250 0000 0000 0000 0000 000b 0000 0000 0001
0010260 0018 4000 0000 0000 0000 0000 0000 0000
0010270 000e 0000 0004 fff1 0000 0000 0000 0000
0010280 0000 0000 0000 0000 000b 0000 0000 0005
0010290 0148 4000 0000 0000 0000 0000 0000 0000
00102a0 0008 0000 0000 0002 0020 4000 0000 0000
00102b0 0000 0000 0000 0000 000b 0000 0000 0003
00102c0 00b0 4000 0000 0000 0000 0000 0000 0000
00102d0 000b 0000 0000 0004 00ec 4000 0000 0000
00102e0 0000 0000 0000 0000 0017 0000 0012 0002
00102f0 0020 4000 0000 0000 0028 0000 0000 0000
0010300 001f 0000 0010 0001 0000 4000 0000 0000
0010310 0000 0000 0000 0000 0026 0000 0012 0002
0010320 0048 4000 0000 0000 0048 0000 0000 0000
0010330 002d 0000 0010 0005 1150 4000 0000 0000
0010340 0000 0000 0000 0000 0037 0000 0011 0005
0010350 0148 4000 0000 0000 0008 0000 0000 0000
0010360 003c 0000 0012 0002 0090 4000 0000 0000
0010370 0020 0000 0000 0000 6200 6f6f 2e74 006f
0010380 7824 2400 0064 656b 6e72 6c65 632e 7000
0010390 7475 6863 7261 5f00 7473 7261 0074 7270
00103a0 6e69 6b74 7300 6174 6b63 745f 706f 7500
00103b0 7261 0074 6d6b 6961 006e 2e00 7973 746d
00103c0 6261 2e00 7473 7472 6261 2e00 6873 7473
00103d0 7472 6261 2e00 7473 7261 7574 0070 742e
00103e0 7865 0074 722e 646f 7461 0061 652e 5f68
00103f0 7266 6d61 0065 642e 7461 0061 632e 6d6f
0010400 656d 746e 0000 0000 0000 0000 0000 0000
0010410 0000 0000 0000 0000 0000 0000 0000 0000
*
0010440 0000 0000 0000 0000 001b 0000 0001 0000
0010450 0006 0000 0000 0000 0000 4000 0000 0000
0010460 0000 0001 0000 0000 0020 0000 0000 0000
0010470 0000 0000 0000 0000 0008 0000 0000 0000
0010480 0000 0000 0000 0000 0024 0000 0001 0000
0010490 0006 0000 0000 0000 0020 4000 0000 0000
00104a0 0020 0001 0000 0000 0090 0000 0000 0000
00104b0 0000 0000 0000 0000 0004 0000 0000 0000
00104c0 0000 0000 0000 0000 002a 0000 0001 0000
00104d0 0002 0000 0000 0000 00b0 4000 0000 0000
00104e0 00b0 0001 0000 0000 0024 0000 0000 0000
00104f0 0000 0000 0000 0000 0008 0000 0000 0000
0010500 0000 0000 0000 0000 0032 0000 0001 0000
0010510 0002 0000 0000 0000 00d8 4000 0000 0000
0010520 00d8 0001 0000 0000 006c 0000 0000 0000
0010530 0000 0000 0000 0000 0008 0000 0000 0000
0010540 0000 0000 0000 0000 003c 0000 0001 0000
0010550 0003 0000 0000 0000 0148 4000 0000 0000
0010560 0148 0001 0000 0000 0008 0000 0000 0000
0010570 0000 0000 0000 0000 0008 0000 0000 0000
0010580 0000 0000 0000 0000 0042 0000 0001 0000
0010590 0030 0000 0000 0000 0000 0000 0000 0000
00105a0 0150 0001 0000 0000 002b 0000 0000 0000
00105b0 0000 0000 0000 0000 0001 0000 0000 0000
00105c0 0001 0000 0000 0000 0001 0000 0002 0000
00105d0 0000 0000 0000 0000 0000 0000 0000 0000
00105e0 0180 0001 0000 0000 01f8 0000 0000 0000
00105f0 0008 0000 000f 0000 0008 0000 0000 0000
0010600 0018 0000 0000 0000 0009 0000 0003 0000
0010610 0000 0000 0000 0000 0000 0000 0000 0000
0010620 0378 0001 0000 0000 0042 0000 0000 0000
0010630 0000 0000 0000 0000 0001 0000 0000 0000
0010640 0000 0000 0000 0000 0011 0000 0003 0000
0010650 0000 0000 0000 0000 0000 0000 0000 0000
0010660 03ba 0001 0000 0000 004b 0000 0000 0000
0010670 0000 0000 0000 0000 0001 0000 0000 0000
0010680 0000 0000 0000 0000                    
0010688

```
