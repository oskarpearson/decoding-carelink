## do stuff with an insulin pump over RF
using ` Namespace(begin=None, bytesPerRecord=None, command='tweak', descr=None, dryrun=False, effectTime=None, end=None, init=False, maxRecords=None, name=None, no_postlude=False, no_prelude=False, no_rf_prelude=False, other='ReadISIGHistory', page=7, params=None, port='/dev/ttyUSB0', postfix=None, prefix=None, prefix_path='logs/20140501_225611-pg-7-', save=True, saveall=False, serial='584923', verbose=None) `
```
```
```
```
```
```
```
```
```javascript
{'radio': {'errors.crc': 0,
           'errors.naks': 0,
           'errors.sequence': 0,
           'errors.timeouts': 0,
           'packets.received': 436L,
           'packets.transmit': 453L},
 'usb': {'errors.crc': 0,
         'errors.naks': 0,
         'errors.sequence': 0,
         'errors.timeouts': 0,
         'packets.received': 627L,
         'packets.transmit': 627L}}
```
```
```
### PUMP MODEL: `ReadPumpModel:size[64]:data:'722'`
<class 'decocare.commands.ReadISIGHistory'> {'page': 7}
response: ReadISIGHistory:size[2048]:[page][0]:data[2048]:
hexdump:
```python
0000   0x11 0x06 0x2a 0x06 0x2f 0x06 0x27 0x06    ..*./.'.
0008   0x4e 0x06 0x80 0x06 0x88 0x06 0x8b 0x06    N.......
0010   0x84 0x06 0x5c 0x06 0x7e 0x06 0x96 0x06    ..\.~...
0018   0x9f 0x06 0xa2 0x06 0x9e 0x06 0x94 0x06    ........
0020   0x42 0x06 0xff 0x05 0xf1 0x05 0xfd 0x05    B.......
0028   0x22 0x06 0x23 0x06 0x20 0x06 0x37 0x06    ".#. .7.
0030   0x4d 0x06 0x58 0x06 0x7e 0x06 0xae 0x06    M.X.~...
0038   0xc5 0x06 0xd6 0x06 0xe3 0x06 0xed 0x06    ........
0040   0xed 0x06 0xe9 0x06 0x22 0x00 0x22 0x00    ....".".
0048   0x22 0x00 0x22 0x00 0x22 0x00 0x0e 0x00    "."."...
0050   0x22 0x00 0xc4 0x06 0x22 0x00 0xe0 0x06    "..."...
0058   0x22 0x00 0xd2 0x06 0xdb 0x06 0x22 0x00    ".....".
0060   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".
0068   0x22 0x00 0x0f 0x00 0xbb 0x06 0x94 0x06    ".......
0070   0x80 0x06 0x60 0x06 0x28 0x06 0xf9 0x05    ..`.(...
0078   0xc7 0x05 0x8b 0x05 0x6e 0x05 0x44 0x05    ....n.D.
0080   0x04 0x05 0xd8 0x04 0xa5 0x04 0x79 0x04    ......y.
0088   0x64 0x04 0x57 0x04 0x47 0x04 0x2c 0x04    d.W.G.,.
0090   0x14 0x04 0xf1 0x03 0xd9 0x03 0xc9 0x03    ........
0098   0xa8 0x03 0x93 0x03 0xa5 0x03 0xfb 0x03    ........
00A0   0x56 0x04 0xb8 0x04 0x03 0x05 0x52 0x05    V.....R.
00A8   0xb6 0x05 0x06 0x06 0x3a 0x06 0x64 0x06    ....:.d.
00B0   0x8c 0x06 0xc9 0x06 0xda 0x06 0xbe 0x06    ........
00B8   0xd3 0x06 0x0a 0x07 0x2c 0x07 0x31 0x07    ....,.1.
00C0   0x21 0x07 0x17 0x07 0x47 0x07 0x57 0x07    !...G.W.
00C8   0x3d 0x07 0x27 0x07 0x1e 0x07 0x2a 0x07    =.'...*.
00D0   0xf5 0x06 0xb0 0x06 0x54 0x06 0xf7 0x05    ....T...
00D8   0xb0 0x05 0x6e 0x05 0x21 0x05 0xc2 0x04    ..n.!...
00E0   0x9d 0x04 0x86 0x04 0x66 0x04 0x4a 0x04    ....f.J.
00E8   0x31 0x04 0x30 0x04 0x26 0x04 0x3f 0x04    1.0.&.?.
00F0   0x57 0x04 0x73 0x04 0x90 0x04 0xab 0x04    W.s.....
00F8   0xc4 0x04 0xcc 0x04 0xda 0x04 0x0d 0x05    ........
0100   0x3a 0x05 0x73 0x05 0xad 0x05 0xdd 0x05    :.s.....
0108   0xfe 0x05 0x18 0x06 0x24 0x06 0x48 0x06    ....$.H.
0110   0x82 0x06 0xbc 0x06 0xeb 0x06 0x15 0x07    ........
0118   0x37 0x07 0x59 0x07 0x75 0x07 0x88 0x07    7.Y.u...
0120   0x8a 0x07 0x97 0x07 0xad 0x07 0xc5 0x07    ........
0128   0xd5 0x07 0xf8 0x07 0x1b 0x08 0xfa 0x07    ........
0130   0x24 0x08 0x2d 0x08 0x15 0x08 0x02 0x08    $.-.....
0138   0xd7 0x07 0x93 0x07 0x49 0x07 0x10 0x07    ....I...
0140   0xea 0x06 0xcb 0x06 0x9d 0x06 0x6c 0x06    ......l.
0148   0x49 0x06 0x3a 0x06 0x21 0x06 0xff 0x05    I.:.!...
0150   0xcb 0x05 0x9a 0x05 0x7e 0x05 0x68 0x05    ....~.h.
0158   0x5c 0x05 0x50 0x05 0x23 0x05 0x02 0x05    \.P.#...
0160   0xe0 0x04 0xb6 0x04 0xad 0x04 0x9f 0x04    ........
0168   0x9d 0x04 0x77 0x04 0x60 0x04 0x3d 0x04    ..w.`.=.
0170   0x1e 0x04 0xed 0x03 0xab 0x03 0x69 0x03    ......i.
0178   0x3d 0x03 0x31 0x03 0x4c 0x03 0x7d 0x03    =.1.L.}.
0180   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".
0188   0x22 0x00 0x0e 0x00 0x90 0x03 0x98 0x03    ".......
0190   0x78 0x03 0x22 0x00 0x22 0x00 0x22 0x00    x.".".".
0198   0x22 0x00 0x22 0x00 0x22 0x00 0x0f 0x00    "."."...
01A0   0x54 0x03 0x54 0x03 0x53 0x03 0x4b 0x03    T.T.S.K.
01A8   0x55 0x03 0x7d 0x03 0x8d 0x03 0x8e 0x03    U.}.....
01B0   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".
01B8   0x22 0x00 0x0e 0x00 0xb9 0x03 0xcd 0x03    ".......
01C0   0xdf 0x03 0x20 0x04 0x22 0x00 0x22 0x00    .. .".".
01C8   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".
01D0   0x0f 0x00 0x5b 0x04 0x92 0x04 0xe2 0x04    ..[.....
01D8   0x31 0x05 0x82 0x05 0xd1 0x05 0x09 0x06    1.......
01E0   0xdb 0x05 0xe1 0x05 0x22 0x00 0x01 0x06    ...."...
01E8   0x5f 0x06 0x22 0x00 0xae 0x06 0xf0 0x06    _.".....
01F0   0x22 0x00 0x13 0x07 0x2b 0x07 0x41 0x07    "...+.A.
01F8   0x22 0x00 0x02 0x00 0x22 0x00 0x02 0x00    "..."...
0200   0x22 0x00 0x02 0x00 0x22 0x00 0x02 0x00    "..."...
0208   0x22 0x00 0x02 0x00 0x22 0x00 0x02 0x00    "..."...
0210   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".
0218   0x08 0x00 0x22 0x00 0x02 0x00 0x22 0x00    .."...".
0220   0x02 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ..".".".
0228   0x22 0x00 0x08 0x00 0x22 0x00 0x22 0x00    "...".".
0230   0x22 0x00 0x22 0x00 0x0b 0x00 0x22 0x00    "."...".
0238   0x22 0x00 0x22 0x00 0x22 0x00 0x0d 0x00    "."."...
0240   0x22 0x00 0xa2 0x03 0x22 0x00 0x22 0x00    "...".".
0248   0x22 0x00 0x22 0x00 0x22 0x00 0x0e 0x00    "."."...
0250   0x22 0x00 0x84 0x03 0x22 0x00 0x6e 0x03    "...".n.
0258   0x4f 0x03 0x22 0x00 0x22 0x00 0x22 0x00    O.".".".
0260   0x22 0x00 0x22 0x00 0x22 0x00 0x0f 0x00    "."."...
0268   0x51 0x03 0x72 0x03 0xad 0x03 0xf5 0x03    Q.r.....
0270   0x3b 0x04 0x6c 0x04 0x7d 0x04 0x7a 0x04    ;.l.}.z.
0278   0x74 0x04 0x70 0x04 0x69 0x04 0x50 0x04    t.p.i.P.
0280   0x40 0x04 0x27 0x04 0x00 0x04 0xe8 0x03    @.'.....
0288   0xea 0x03 0xdd 0x03 0xc9 0x03 0xca 0x03    ........
0290   0xd4 0x03 0xe1 0x03 0x2b 0x04 0xa1 0x04    ....+...
0298   0x06 0x05 0x57 0x05 0x7a 0x05 0x8d 0x05    ..W.z...
02A0   0x91 0x05 0x80 0x05 0x6c 0x05 0x52 0x05    ....l.R.
02A8   0x3b 0x05 0x1e 0x05 0x09 0x05 0xf6 0x04    ;.......
02B0   0xe0 0x04 0xcb 0x04 0xb7 0x04 0xa2 0x04    ........
02B8   0x92 0x04 0x22 0x00 0x22 0x00 0x22 0x00    ..".".".
02C0   0x22 0x00 0x22 0x00 0x0e 0x00 0x88 0x04    ".".....
02C8   0x83 0x04 0x81 0x04 0x22 0x00 0x22 0x00    ....".".
02D0   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".
02D8   0x0f 0x00 0x83 0x04 0x83 0x04 0x8d 0x04    ........
02E0   0x8c 0x04 0x8a 0x04 0x88 0x04 0x79 0x04    ......y.
02E8   0x59 0x04 0x4d 0x04 0x48 0x04 0x46 0x04    Y.M.H.F.
02F0   0x37 0x04 0x32 0x04 0x2b 0x04 0x0c 0x04    7.2.+...
02F8   0x11 0x04 0x30 0x04 0x4a 0x04 0x62 0x04    ..0.J.b.
0300   0x6f 0x04 0x7f 0x04 0x86 0x04 0x91 0x04    o.......
0308   0x94 0x04 0x84 0x04 0x71 0x04 0x4e 0x04    ....q.N.
0310   0x32 0x04 0xf8 0x03 0xf3 0x03 0x11 0x04    2.......
0318   0x03 0x04 0xe2 0x03 0xc1 0x03 0xab 0x03    ........
0320   0x90 0x03 0x76 0x03 0x57 0x03 0x43 0x03    ..v.W.C.
0328   0x48 0x03 0x80 0x03 0xdf 0x03 0x2c 0x04    H.....,.
0330   0x66 0x04 0x94 0x04 0xae 0x04 0xcb 0x04    f.......
0338   0xc9 0x04 0xc9 0x04 0xb5 0x04 0x84 0x04    ........
0340   0x3e 0x04 0xef 0x03 0xb1 0x03 0x8e 0x03    >.......
0348   0x7f 0x03 0x7b 0x03 0xa2 0x03 0xd1 0x03    ..{.....
0350   0x03 0x04 0x18 0x04 0x0b 0x04 0xea 0x03    ........
0358   0xbe 0x03 0xa7 0x03 0x97 0x03 0x99 0x03    ........
0360   0x9d 0x03 0xb8 0x03 0xeb 0x03 0x21 0x04    ......!.
0368   0x65 0x04 0x96 0x04 0x22 0x00 0x02 0x00    e..."...
0370   0x22 0x00 0x02 0x00 0x22 0x00 0x22 0x00    "...".".
0378   0x22 0x00 0x22 0x00 0x08 0x00 0x22 0x00    "."...".
0380   0x22 0x00 0x22 0x00 0x22 0x00 0x0b 0x00    "."."...
0388   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".
0390   0x0b 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ..".".".
0398   0x22 0x00 0x0d 0x00 0x22 0x00 0x04 0x14    "..."...
03A0   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".
03A8   0x22 0x00 0x0e 0x00 0x22 0x00 0x9a 0x13    "..."...
03B0   0x22 0x00 0x28 0x13 0x96 0x12 0x22 0x00    ".(...".
03B8   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".
03C0   0x22 0x00 0x0f 0x00 0xf7 0x11 0x5e 0x11    ".....^.
03C8   0xf3 0x10 0xcc 0x10 0xe7 0x10 0x15 0x11    ........
03D0   0x0d 0x11 0xeb 0x10 0xc8 0x10 0xa3 0x10    ........
03D8   0x88 0x10 0x69 0x10 0x56 0x10 0x5b 0x10    ..i.V.[.
03E0   0x70 0x10 0x23 0x10 0xed 0x0f 0xd4 0x0f    p.#.....
03E8   0xbc 0x0f 0xce 0x0f 0x89 0x0f 0x2d 0x0f    ......-.
03F0   0x73 0x0f 0x93 0x0f 0x4c 0x0f 0x11 0x0f    s...L...
03F8   0xf2 0x0e 0xf5 0x0e 0x27 0x0f 0x50 0x0f    ....'.P.
0400   0x78 0x0f 0xa5 0x0f 0xf3 0x0f 0xc0 0x11    x.......
0408   0xaf 0x12 0xe0 0x12 0xcc 0x12 0x2d 0x12    ......-.
0410   0x64 0x12 0x6a 0x13 0x46 0x13 0x03 0x13    d.j.F...
0418   0x6c 0x12 0xa9 0x11 0x05 0x11 0x75 0x10    l.....u.
0420   0x09 0x10 0xc5 0x0f 0x96 0x0f 0x5c 0x0f    ......\.
0428   0x30 0x0f 0x1d 0x0f 0x10 0x0f 0x96 0x0f    0.......
0430   0x48 0x10 0xfd 0x0f 0xf4 0x0f 0xf8 0x0f    H.......
0438   0x22 0x00 0xec 0x0f 0xa6 0x0f 0x7d 0x10    ".....}.
0440   0xf1 0x10 0x32 0x11 0xd0 0x10 0xa1 0x10    ..2.....
0448   0xbb 0x10 0x6d 0x10 0x22 0x00 0x22 0x00    ..m.".".
0450   0x22 0x00 0x22 0x00 0x22 0x00 0x0e 0x00    "."."...
0458   0x50 0x10 0x27 0x10 0xdb 0x0f 0x22 0x00    P.'...".
0460   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".
0468   0x22 0x00 0x0f 0x00 0x94 0x0f 0x44 0x0f    ".....D.
0470   0xf1 0x0e 0xce 0x0e 0xe8 0x0e 0xfc 0x0e    ........
0478   0x00 0x0f 0xd1 0x0e 0xbd 0x0e 0x98 0x0f    ........
0480   0xe5 0x10 0x77 0x10 0x25 0x10 0xb6 0x0f    ..w.%...
0488   0x4f 0x0f 0x12 0x0f 0xf8 0x0e 0xf1 0x0e    O.......
0490   0x00 0x0f 0x11 0x0f 0xc6 0x0f 0x7d 0x10    ......}.
0498   0x7e 0x10 0x69 0x10 0x51 0x10 0x45 0x10    ~.i.Q.E.
04A0   0x3c 0x10 0x5d 0x10 0x96 0x10 0x9f 0x10    <.].....
04A8   0x95 0x10 0x91 0x10 0x91 0x10 0x69 0x10    ......i.
04B0   0x09 0x10 0xf1 0x0f 0xbf 0x10 0x17 0x11    ........
04B8   0x00 0x11 0x3e 0x10 0x28 0x10 0x84 0x10    ..>.(...
04C0   0xd8 0x10 0x80 0x11 0x5e 0x11 0x44 0x11    ....^.D.
04C8   0x6b 0x11 0x0a 0x12 0x40 0x12 0x26 0x12    k...@.&.
04D0   0x84 0x12 0x0d 0x13 0x22 0x00 0x22 0x00    ....".".
04D8   0x22 0x00 0x22 0x00 0x22 0x00 0x0e 0x00    "."."...
04E0   0xa6 0x13 0x08 0x14 0x5b 0x14 0x22 0x00    ....[.".
04E8   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".
04F0   0x22 0x00 0x0f 0x00 0x26 0x14 0x18 0x14    "...&...
04F8   0x26 0x14 0x96 0x13 0xc5 0x13 0xcb 0x13    &.......
0500   0xd3 0x13 0x86 0x13 0x5e 0x13 0x7e 0x13    ....^.~.
0508   0xd3 0x12 0x86 0x12 0x67 0x12 0x07 0x12    ....g...
0510   0x58 0x11 0x31 0x11 0xa7 0x11 0x42 0x11    X.1...B.
0518   0x9e 0x10 0x22 0x00 0x1e 0x10 0xc8 0x0f    ..".....
0520   0xa8 0x10 0xb1 0x10 0x4d 0x10 0xff 0x0f    ....M...
0528   0xdf 0x0f 0x00 0x10 0xee 0x0f 0x0a 0x10    ........
0530   0xea 0x0f 0x92 0x0f 0x7f 0x0f 0x7a 0x0f    ......z.
0538   0x37 0x0f 0x15 0x0f 0xf8 0x0e 0x6d 0x0e    7.....m.
0540   0x2a 0x0e 0xc3 0x0e 0xb9 0x0e 0x2a 0x0e    *.....*.
0548   0xef 0x0d 0x23 0x0e 0x21 0x0e 0x12 0x0e    ..#.!...
0550   0xd7 0x0d 0xb6 0x0d 0xa7 0x0d 0x7a 0x0d    ......z.
0558   0x28 0x0d 0xc3 0x0c 0x63 0x0c 0x02 0x0c    (...c...
0560   0xac 0x0b 0x8c 0x0b 0x89 0x0b 0x80 0x0b    ........
0568   0x6d 0x0b 0x67 0x0b 0x8b 0x0b 0xd7 0x0b    m.g.....
0570   0x15 0x0c 0x51 0x0c 0x6f 0x0c 0x5a 0x0c    ..Q.o.Z.
0578   0x58 0x0c 0x56 0x0c 0x7c 0x0c 0xb2 0x0c    X.V.|...
0580   0xae 0x0c 0xc3 0x0c 0xde 0x0c 0x0f 0x0d    ........
0588   0x49 0x0d 0x7d 0x0d 0xc3 0x0d 0x3e 0x0e    I.}...>.
0590   0x94 0x0e 0xb4 0x0e 0xca 0x0e 0xef 0x0e    ........
0598   0xd1 0x0e 0x53 0x0e 0x9b 0x0d 0xfd 0x0c    ..S.....
05A0   0x7e 0x0c 0x15 0x0c 0x22 0x00 0xc6 0x0b    ~..."...
05A8   0x86 0x0b 0x58 0x0b 0x1e 0x0b 0xf2 0x0a    ..X.....
05B0   0xbc 0x0a 0xa9 0x0a 0x98 0x0a 0x73 0x0a    ......s.
05B8   0x4d 0x0a 0x53 0x0a 0x7d 0x0a 0x4f 0x0a    M.S.}.O.
05C0   0x55 0x0a 0xb8 0x0a 0x54 0x0b 0xa7 0x0b    U...T...
05C8   0x34 0x0c 0xaa 0x0c 0x1b 0x0d 0x58 0x0d    4.....X.
05D0   0x7b 0x0d 0x74 0x0d 0x62 0x0d 0x39 0x0d    {.t.b.9.
05D8   0x12 0x0d 0x5e 0x0d 0xc5 0x0d 0xb6 0x0d    ..^.....
05E0   0x06 0x0e 0x3a 0x0e 0x66 0x0e 0x9b 0x0e    ..:.f...
05E8   0x8e 0x0e 0x97 0x0e 0x22 0x00 0xee 0x0e    ...."...
05F0   0x22 0x00 0xb2 0x0e 0xf1 0x0d 0x2c 0x0d    ".....,.
05F8   0x8b 0x0c 0xd5 0x0b 0x22 0x00 0xf4 0x0a    ...."...
0600   0x61 0x0a 0xd3 0x09 0x50 0x09 0xd9 0x08    a...P...
0608   0x74 0x08 0x17 0x08 0xcd 0x07 0xb7 0x07    t.......
0610   0xaa 0x07 0x22 0x00 0x22 0x00 0x22 0x00    ..".".".
0618   0x22 0x00 0x22 0x00 0x0e 0x00 0xc6 0x07    ".".....
0620   0xff 0x07 0x28 0x08 0x22 0x00 0x22 0x00    ..(.".".
0628   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".
0630   0x0f 0x00 0x64 0x08 0x9a 0x08 0x95 0x08    ..d.....
0638   0x93 0x08 0x85 0x08 0x46 0x08 0x45 0x08    ....F.E.
0640   0x6f 0x08 0x76 0x08 0x74 0x08 0x5a 0x08    o.v.t.Z.
0648   0x5f 0x08 0x6a 0x08 0xcf 0x08 0x55 0x09    _.j...U.
0650   0x5f 0x09 0x7f 0x09 0x7d 0x09 0x65 0x09    _...}.e.
0658   0x6d 0x09 0x22 0x09 0xb7 0x08 0x22 0x00    m."...".
0660   0x30 0x08 0xd8 0x07 0x95 0x07 0x40 0x07    0.....@.
0668   0x30 0x07 0x3b 0x07 0x22 0x00 0x8c 0x07    0.;."...
0670   0xce 0x07 0xe3 0x07 0x19 0x08 0x53 0x08    ......S.
0678   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".
0680   0x22 0x00 0x0e 0x00 0x5c 0x08 0x5b 0x08    "...\.[.
0688   0x6a 0x08 0x22 0x00 0x22 0x00 0x22 0x00    j.".".".
0690   0x22 0x00 0x22 0x00 0x22 0x00 0x0f 0x00    "."."...
0698   0x91 0x08 0xc6 0x08 0x0e 0x09 0x54 0x09    ......T.
06A0   0x7c 0x09 0xa8 0x09 0xd5 0x09 0x01 0x0a    |.......
06A8   0x24 0x0a 0x82 0x0a 0xf3 0x0a 0xf5 0x0a    $.......
06B0   0x0a 0x0b 0x23 0x0b 0x3c 0x0b 0x55 0x0b    ..#.<.U.
06B8   0xd9 0x0b 0x1e 0x0c 0x1b 0x0c 0x22 0x0c    ......".
06C0   0x27 0x0c 0x27 0x0c 0x27 0x0c 0x1f 0x0c    '.'.'...
06C8   0x16 0x0c 0x22 0x00 0x70 0x0c 0x22 0x00    ..".p.".
06D0   0x83 0x0c 0x22 0x00 0x5b 0x0c 0x22 0x00    ..".[.".
06D8   0x42 0x0c 0x38 0x0c 0x22 0x00 0x2f 0x0c    B.8."./.
06E0   0x22 0x00 0x2f 0x0c 0x22 0x00 0x2f 0x0c    "./."./.
06E8   0x22 0x00 0x33 0x0c 0x22 0x00 0x47 0x0c    ".3.".G.
06F0   0x22 0x00 0x5c 0x0c 0x79 0x0c 0x7f 0x0c    ".\.y...
06F8   0x77 0x0c 0x82 0x0c 0x22 0x00 0x9c 0x0c    w..."...
0700   0x2f 0x0d 0xba 0x0d 0xf1 0x0d 0x24 0x0e    /.....$.
0708   0x22 0x00 0x6a 0x0e 0x22 0x00 0x71 0x0e    ".j.".q.
0710   0x22 0x00 0x2f 0x0e 0x22 0x00 0x06 0x0e    "./."...
0718   0x22 0x00 0xeb 0x0d 0x22 0x00 0xd8 0x0d    "..."...
0720   0xd4 0x0d 0xdd 0x0d 0xc5 0x0d 0xc1 0x0d    ........
0728   0xc9 0x0d 0xd3 0x0d 0xdb 0x0d 0xdf 0x0d    ........
0730   0x33 0x0e 0xff 0x0d 0x79 0x0d 0x45 0x0d    3...y.E.
0738   0x27 0x0d 0x1c 0x0d 0x1b 0x0d 0x46 0x0d    '.....F.
0740   0xe4 0x0e 0xa3 0x0f 0xb2 0x0f 0xc2 0x0f    ........
0748   0xd6 0x0f 0xe0 0x0f 0xeb 0x0f 0xf5 0x0f    ........
0750   0xf9 0x0f 0xef 0x0f 0xe1 0x0f 0xcb 0x0f    ........
0758   0xbc 0x0f 0x15 0x10 0x26 0x10 0xf0 0x0f    ....&...
0760   0x82 0x0f 0xc6 0x0e 0x64 0x0e 0x2d 0x0e    ....d.-.
0768   0xfc 0x0d 0xe5 0x0d 0xc6 0x0e 0x58 0x0f    ......X.
0770   0x60 0x0f 0x7a 0x0f 0x99 0x0f 0xd7 0x0f    `.z.....
0778   0x13 0x10 0x0e 0x10 0x06 0x10 0xf8 0x0f    ........
0780   0x06 0x10 0xcf 0x0f 0x90 0x0f 0x74 0x0f    ......t.
0788   0x61 0x0f 0xf1 0x0f 0x8f 0x10 0x6c 0x10    a.....l.
0790   0x5b 0x10 0xed 0x0f 0x72 0x0f 0x44 0x0f    [...r.D.
0798   0x1e 0x0f 0x09 0x0f 0x9e 0x0f 0xc8 0x0f    ........
07A0   0x78 0x0f 0xc9 0x0f 0x37 0x10 0x4d 0x10    x...7.M.
07A8   0x68 0x10 0xc8 0x10 0xc8 0x10 0x40 0x11    h.....@.
07B0   0x87 0x11 0x9c 0x11 0xb4 0x11 0x53 0x12    ......S.
07B8   0x22 0x00 0x32 0x13 0xe8 0x12 0x03 0x13    ".2.....
07C0   0xa6 0x13 0x01 0x14 0x15 0x14 0x12 0x14    ........
07C8   0x8f 0x14 0x47 0x15 0xc9 0x15 0x60 0x16    ..G...`.
07D0   0x01 0x17 0x22 0x00 0x22 0x00 0x22 0x00    ..".".".
07D8   0x22 0x00 0x22 0x00 0x0e 0x00 0x64 0x17    "."...d.
07E0   0xa3 0x17 0xfb 0x17 0x22 0x00 0x22 0x00    ....".".
07E8   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".
07F0   0x0f 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ..".".".
07F8   0x22 0x00 0x08 0x00 0x2b 0x00 0x24 0x00    "...+.$.
```
#### decoded:
```python
'0000   0x11 0x06 0x2a 0x06 0x2f 0x06 0x27 0x06    ..*./.\'.\n0008   0x4e 0x06 0x80 0x06 0x88 0x06 0x8b 0x06    N.......\n0010   0x84 0x06 0x5c 0x06 0x7e 0x06 0x96 0x06    ..\\.~...\n0018   0x9f 0x06 0xa2 0x06 0x9e 0x06 0x94 0x06    ........\n0020   0x42 0x06 0xff 0x05 0xf1 0x05 0xfd 0x05    B.......\n0028   0x22 0x06 0x23 0x06 0x20 0x06 0x37 0x06    ".#. .7.\n0030   0x4d 0x06 0x58 0x06 0x7e 0x06 0xae 0x06    M.X.~...\n0038   0xc5 0x06 0xd6 0x06 0xe3 0x06 0xed 0x06    ........\n0040   0xed 0x06 0xe9 0x06 0x22 0x00 0x22 0x00    ....".".\n0048   0x22 0x00 0x22 0x00 0x22 0x00 0x0e 0x00    "."."...\n0050   0x22 0x00 0xc4 0x06 0x22 0x00 0xe0 0x06    "..."...\n0058   0x22 0x00 0xd2 0x06 0xdb 0x06 0x22 0x00    ".....".\n0060   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".\n0068   0x22 0x00 0x0f 0x00 0xbb 0x06 0x94 0x06    ".......\n0070   0x80 0x06 0x60 0x06 0x28 0x06 0xf9 0x05    ..`.(...\n0078   0xc7 0x05 0x8b 0x05 0x6e 0x05 0x44 0x05    ....n.D.\n0080   0x04 0x05 0xd8 0x04 0xa5 0x04 0x79 0x04    ......y.\n0088   0x64 0x04 0x57 0x04 0x47 0x04 0x2c 0x04    d.W.G.,.\n0090   0x14 0x04 0xf1 0x03 0xd9 0x03 0xc9 0x03    ........\n0098   0xa8 0x03 0x93 0x03 0xa5 0x03 0xfb 0x03    ........\n00A0   0x56 0x04 0xb8 0x04 0x03 0x05 0x52 0x05    V.....R.\n00A8   0xb6 0x05 0x06 0x06 0x3a 0x06 0x64 0x06    ....:.d.\n00B0   0x8c 0x06 0xc9 0x06 0xda 0x06 0xbe 0x06    ........\n00B8   0xd3 0x06 0x0a 0x07 0x2c 0x07 0x31 0x07    ....,.1.\n00C0   0x21 0x07 0x17 0x07 0x47 0x07 0x57 0x07    !...G.W.\n00C8   0x3d 0x07 0x27 0x07 0x1e 0x07 0x2a 0x07    =.\'...*.\n00D0   0xf5 0x06 0xb0 0x06 0x54 0x06 0xf7 0x05    ....T...\n00D8   0xb0 0x05 0x6e 0x05 0x21 0x05 0xc2 0x04    ..n.!...\n00E0   0x9d 0x04 0x86 0x04 0x66 0x04 0x4a 0x04    ....f.J.\n00E8   0x31 0x04 0x30 0x04 0x26 0x04 0x3f 0x04    1.0.&.?.\n00F0   0x57 0x04 0x73 0x04 0x90 0x04 0xab 0x04    W.s.....\n00F8   0xc4 0x04 0xcc 0x04 0xda 0x04 0x0d 0x05    ........\n0100   0x3a 0x05 0x73 0x05 0xad 0x05 0xdd 0x05    :.s.....\n0108   0xfe 0x05 0x18 0x06 0x24 0x06 0x48 0x06    ....$.H.\n0110   0x82 0x06 0xbc 0x06 0xeb 0x06 0x15 0x07    ........\n0118   0x37 0x07 0x59 0x07 0x75 0x07 0x88 0x07    7.Y.u...\n0120   0x8a 0x07 0x97 0x07 0xad 0x07 0xc5 0x07    ........\n0128   0xd5 0x07 0xf8 0x07 0x1b 0x08 0xfa 0x07    ........\n0130   0x24 0x08 0x2d 0x08 0x15 0x08 0x02 0x08    $.-.....\n0138   0xd7 0x07 0x93 0x07 0x49 0x07 0x10 0x07    ....I...\n0140   0xea 0x06 0xcb 0x06 0x9d 0x06 0x6c 0x06    ......l.\n0148   0x49 0x06 0x3a 0x06 0x21 0x06 0xff 0x05    I.:.!...\n0150   0xcb 0x05 0x9a 0x05 0x7e 0x05 0x68 0x05    ....~.h.\n0158   0x5c 0x05 0x50 0x05 0x23 0x05 0x02 0x05    \\.P.#...\n0160   0xe0 0x04 0xb6 0x04 0xad 0x04 0x9f 0x04    ........\n0168   0x9d 0x04 0x77 0x04 0x60 0x04 0x3d 0x04    ..w.`.=.\n0170   0x1e 0x04 0xed 0x03 0xab 0x03 0x69 0x03    ......i.\n0178   0x3d 0x03 0x31 0x03 0x4c 0x03 0x7d 0x03    =.1.L.}.\n0180   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".\n0188   0x22 0x00 0x0e 0x00 0x90 0x03 0x98 0x03    ".......\n0190   0x78 0x03 0x22 0x00 0x22 0x00 0x22 0x00    x.".".".\n0198   0x22 0x00 0x22 0x00 0x22 0x00 0x0f 0x00    "."."...\n01A0   0x54 0x03 0x54 0x03 0x53 0x03 0x4b 0x03    T.T.S.K.\n01A8   0x55 0x03 0x7d 0x03 0x8d 0x03 0x8e 0x03    U.}.....\n01B0   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".\n01B8   0x22 0x00 0x0e 0x00 0xb9 0x03 0xcd 0x03    ".......\n01C0   0xdf 0x03 0x20 0x04 0x22 0x00 0x22 0x00    .. .".".\n01C8   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".\n01D0   0x0f 0x00 0x5b 0x04 0x92 0x04 0xe2 0x04    ..[.....\n01D8   0x31 0x05 0x82 0x05 0xd1 0x05 0x09 0x06    1.......\n01E0   0xdb 0x05 0xe1 0x05 0x22 0x00 0x01 0x06    ...."...\n01E8   0x5f 0x06 0x22 0x00 0xae 0x06 0xf0 0x06    _.".....\n01F0   0x22 0x00 0x13 0x07 0x2b 0x07 0x41 0x07    "...+.A.\n01F8   0x22 0x00 0x02 0x00 0x22 0x00 0x02 0x00    "..."...\n0200   0x22 0x00 0x02 0x00 0x22 0x00 0x02 0x00    "..."...\n0208   0x22 0x00 0x02 0x00 0x22 0x00 0x02 0x00    "..."...\n0210   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".\n0218   0x08 0x00 0x22 0x00 0x02 0x00 0x22 0x00    .."...".\n0220   0x02 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ..".".".\n0228   0x22 0x00 0x08 0x00 0x22 0x00 0x22 0x00    "...".".\n0230   0x22 0x00 0x22 0x00 0x0b 0x00 0x22 0x00    "."...".\n0238   0x22 0x00 0x22 0x00 0x22 0x00 0x0d 0x00    "."."...\n0240   0x22 0x00 0xa2 0x03 0x22 0x00 0x22 0x00    "...".".\n0248   0x22 0x00 0x22 0x00 0x22 0x00 0x0e 0x00    "."."...\n0250   0x22 0x00 0x84 0x03 0x22 0x00 0x6e 0x03    "...".n.\n0258   0x4f 0x03 0x22 0x00 0x22 0x00 0x22 0x00    O.".".".\n0260   0x22 0x00 0x22 0x00 0x22 0x00 0x0f 0x00    "."."...\n0268   0x51 0x03 0x72 0x03 0xad 0x03 0xf5 0x03    Q.r.....\n0270   0x3b 0x04 0x6c 0x04 0x7d 0x04 0x7a 0x04    ;.l.}.z.\n0278   0x74 0x04 0x70 0x04 0x69 0x04 0x50 0x04    t.p.i.P.\n0280   0x40 0x04 0x27 0x04 0x00 0x04 0xe8 0x03    @.\'.....\n0288   0xea 0x03 0xdd 0x03 0xc9 0x03 0xca 0x03    ........\n0290   0xd4 0x03 0xe1 0x03 0x2b 0x04 0xa1 0x04    ....+...\n0298   0x06 0x05 0x57 0x05 0x7a 0x05 0x8d 0x05    ..W.z...\n02A0   0x91 0x05 0x80 0x05 0x6c 0x05 0x52 0x05    ....l.R.\n02A8   0x3b 0x05 0x1e 0x05 0x09 0x05 0xf6 0x04    ;.......\n02B0   0xe0 0x04 0xcb 0x04 0xb7 0x04 0xa2 0x04    ........\n02B8   0x92 0x04 0x22 0x00 0x22 0x00 0x22 0x00    ..".".".\n02C0   0x22 0x00 0x22 0x00 0x0e 0x00 0x88 0x04    ".".....\n02C8   0x83 0x04 0x81 0x04 0x22 0x00 0x22 0x00    ....".".\n02D0   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".\n02D8   0x0f 0x00 0x83 0x04 0x83 0x04 0x8d 0x04    ........\n02E0   0x8c 0x04 0x8a 0x04 0x88 0x04 0x79 0x04    ......y.\n02E8   0x59 0x04 0x4d 0x04 0x48 0x04 0x46 0x04    Y.M.H.F.\n02F0   0x37 0x04 0x32 0x04 0x2b 0x04 0x0c 0x04    7.2.+...\n02F8   0x11 0x04 0x30 0x04 0x4a 0x04 0x62 0x04    ..0.J.b.\n0300   0x6f 0x04 0x7f 0x04 0x86 0x04 0x91 0x04    o.......\n0308   0x94 0x04 0x84 0x04 0x71 0x04 0x4e 0x04    ....q.N.\n0310   0x32 0x04 0xf8 0x03 0xf3 0x03 0x11 0x04    2.......\n0318   0x03 0x04 0xe2 0x03 0xc1 0x03 0xab 0x03    ........\n0320   0x90 0x03 0x76 0x03 0x57 0x03 0x43 0x03    ..v.W.C.\n0328   0x48 0x03 0x80 0x03 0xdf 0x03 0x2c 0x04    H.....,.\n0330   0x66 0x04 0x94 0x04 0xae 0x04 0xcb 0x04    f.......\n0338   0xc9 0x04 0xc9 0x04 0xb5 0x04 0x84 0x04    ........\n0340   0x3e 0x04 0xef 0x03 0xb1 0x03 0x8e 0x03    >.......\n0348   0x7f 0x03 0x7b 0x03 0xa2 0x03 0xd1 0x03    ..{.....\n0350   0x03 0x04 0x18 0x04 0x0b 0x04 0xea 0x03    ........\n0358   0xbe 0x03 0xa7 0x03 0x97 0x03 0x99 0x03    ........\n0360   0x9d 0x03 0xb8 0x03 0xeb 0x03 0x21 0x04    ......!.\n0368   0x65 0x04 0x96 0x04 0x22 0x00 0x02 0x00    e..."...\n0370   0x22 0x00 0x02 0x00 0x22 0x00 0x22 0x00    "...".".\n0378   0x22 0x00 0x22 0x00 0x08 0x00 0x22 0x00    "."...".\n0380   0x22 0x00 0x22 0x00 0x22 0x00 0x0b 0x00    "."."...\n0388   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".\n0390   0x0b 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ..".".".\n0398   0x22 0x00 0x0d 0x00 0x22 0x00 0x04 0x14    "..."...\n03A0   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".\n03A8   0x22 0x00 0x0e 0x00 0x22 0x00 0x9a 0x13    "..."...\n03B0   0x22 0x00 0x28 0x13 0x96 0x12 0x22 0x00    ".(...".\n03B8   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".\n03C0   0x22 0x00 0x0f 0x00 0xf7 0x11 0x5e 0x11    ".....^.\n03C8   0xf3 0x10 0xcc 0x10 0xe7 0x10 0x15 0x11    ........\n03D0   0x0d 0x11 0xeb 0x10 0xc8 0x10 0xa3 0x10    ........\n03D8   0x88 0x10 0x69 0x10 0x56 0x10 0x5b 0x10    ..i.V.[.\n03E0   0x70 0x10 0x23 0x10 0xed 0x0f 0xd4 0x0f    p.#.....\n03E8   0xbc 0x0f 0xce 0x0f 0x89 0x0f 0x2d 0x0f    ......-.\n03F0   0x73 0x0f 0x93 0x0f 0x4c 0x0f 0x11 0x0f    s...L...\n03F8   0xf2 0x0e 0xf5 0x0e 0x27 0x0f 0x50 0x0f    ....\'.P.\n0400   0x78 0x0f 0xa5 0x0f 0xf3 0x0f 0xc0 0x11    x.......\n0408   0xaf 0x12 0xe0 0x12 0xcc 0x12 0x2d 0x12    ......-.\n0410   0x64 0x12 0x6a 0x13 0x46 0x13 0x03 0x13    d.j.F...\n0418   0x6c 0x12 0xa9 0x11 0x05 0x11 0x75 0x10    l.....u.\n0420   0x09 0x10 0xc5 0x0f 0x96 0x0f 0x5c 0x0f    ......\\.\n0428   0x30 0x0f 0x1d 0x0f 0x10 0x0f 0x96 0x0f    0.......\n0430   0x48 0x10 0xfd 0x0f 0xf4 0x0f 0xf8 0x0f    H.......\n0438   0x22 0x00 0xec 0x0f 0xa6 0x0f 0x7d 0x10    ".....}.\n0440   0xf1 0x10 0x32 0x11 0xd0 0x10 0xa1 0x10    ..2.....\n0448   0xbb 0x10 0x6d 0x10 0x22 0x00 0x22 0x00    ..m.".".\n0450   0x22 0x00 0x22 0x00 0x22 0x00 0x0e 0x00    "."."...\n0458   0x50 0x10 0x27 0x10 0xdb 0x0f 0x22 0x00    P.\'...".\n0460   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".\n0468   0x22 0x00 0x0f 0x00 0x94 0x0f 0x44 0x0f    ".....D.\n0470   0xf1 0x0e 0xce 0x0e 0xe8 0x0e 0xfc 0x0e    ........\n0478   0x00 0x0f 0xd1 0x0e 0xbd 0x0e 0x98 0x0f    ........\n0480   0xe5 0x10 0x77 0x10 0x25 0x10 0xb6 0x0f    ..w.%...\n0488   0x4f 0x0f 0x12 0x0f 0xf8 0x0e 0xf1 0x0e    O.......\n0490   0x00 0x0f 0x11 0x0f 0xc6 0x0f 0x7d 0x10    ......}.\n0498   0x7e 0x10 0x69 0x10 0x51 0x10 0x45 0x10    ~.i.Q.E.\n04A0   0x3c 0x10 0x5d 0x10 0x96 0x10 0x9f 0x10    <.].....\n04A8   0x95 0x10 0x91 0x10 0x91 0x10 0x69 0x10    ......i.\n04B0   0x09 0x10 0xf1 0x0f 0xbf 0x10 0x17 0x11    ........\n04B8   0x00 0x11 0x3e 0x10 0x28 0x10 0x84 0x10    ..>.(...\n04C0   0xd8 0x10 0x80 0x11 0x5e 0x11 0x44 0x11    ....^.D.\n04C8   0x6b 0x11 0x0a 0x12 0x40 0x12 0x26 0x12    k...@.&.\n04D0   0x84 0x12 0x0d 0x13 0x22 0x00 0x22 0x00    ....".".\n04D8   0x22 0x00 0x22 0x00 0x22 0x00 0x0e 0x00    "."."...\n04E0   0xa6 0x13 0x08 0x14 0x5b 0x14 0x22 0x00    ....[.".\n04E8   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".\n04F0   0x22 0x00 0x0f 0x00 0x26 0x14 0x18 0x14    "...&...\n04F8   0x26 0x14 0x96 0x13 0xc5 0x13 0xcb 0x13    &.......\n0500   0xd3 0x13 0x86 0x13 0x5e 0x13 0x7e 0x13    ....^.~.\n0508   0xd3 0x12 0x86 0x12 0x67 0x12 0x07 0x12    ....g...\n0510   0x58 0x11 0x31 0x11 0xa7 0x11 0x42 0x11    X.1...B.\n0518   0x9e 0x10 0x22 0x00 0x1e 0x10 0xc8 0x0f    ..".....\n0520   0xa8 0x10 0xb1 0x10 0x4d 0x10 0xff 0x0f    ....M...\n0528   0xdf 0x0f 0x00 0x10 0xee 0x0f 0x0a 0x10    ........\n0530   0xea 0x0f 0x92 0x0f 0x7f 0x0f 0x7a 0x0f    ......z.\n0538   0x37 0x0f 0x15 0x0f 0xf8 0x0e 0x6d 0x0e    7.....m.\n0540   0x2a 0x0e 0xc3 0x0e 0xb9 0x0e 0x2a 0x0e    *.....*.\n0548   0xef 0x0d 0x23 0x0e 0x21 0x0e 0x12 0x0e    ..#.!...\n0550   0xd7 0x0d 0xb6 0x0d 0xa7 0x0d 0x7a 0x0d    ......z.\n0558   0x28 0x0d 0xc3 0x0c 0x63 0x0c 0x02 0x0c    (...c...\n0560   0xac 0x0b 0x8c 0x0b 0x89 0x0b 0x80 0x0b    ........\n0568   0x6d 0x0b 0x67 0x0b 0x8b 0x0b 0xd7 0x0b    m.g.....\n0570   0x15 0x0c 0x51 0x0c 0x6f 0x0c 0x5a 0x0c    ..Q.o.Z.\n0578   0x58 0x0c 0x56 0x0c 0x7c 0x0c 0xb2 0x0c    X.V.|...\n0580   0xae 0x0c 0xc3 0x0c 0xde 0x0c 0x0f 0x0d    ........\n0588   0x49 0x0d 0x7d 0x0d 0xc3 0x0d 0x3e 0x0e    I.}...>.\n0590   0x94 0x0e 0xb4 0x0e 0xca 0x0e 0xef 0x0e    ........\n0598   0xd1 0x0e 0x53 0x0e 0x9b 0x0d 0xfd 0x0c    ..S.....\n05A0   0x7e 0x0c 0x15 0x0c 0x22 0x00 0xc6 0x0b    ~..."...\n05A8   0x86 0x0b 0x58 0x0b 0x1e 0x0b 0xf2 0x0a    ..X.....\n05B0   0xbc 0x0a 0xa9 0x0a 0x98 0x0a 0x73 0x0a    ......s.\n05B8   0x4d 0x0a 0x53 0x0a 0x7d 0x0a 0x4f 0x0a    M.S.}.O.\n05C0   0x55 0x0a 0xb8 0x0a 0x54 0x0b 0xa7 0x0b    U...T...\n05C8   0x34 0x0c 0xaa 0x0c 0x1b 0x0d 0x58 0x0d    4.....X.\n05D0   0x7b 0x0d 0x74 0x0d 0x62 0x0d 0x39 0x0d    {.t.b.9.\n05D8   0x12 0x0d 0x5e 0x0d 0xc5 0x0d 0xb6 0x0d    ..^.....\n05E0   0x06 0x0e 0x3a 0x0e 0x66 0x0e 0x9b 0x0e    ..:.f...\n05E8   0x8e 0x0e 0x97 0x0e 0x22 0x00 0xee 0x0e    ...."...\n05F0   0x22 0x00 0xb2 0x0e 0xf1 0x0d 0x2c 0x0d    ".....,.\n05F8   0x8b 0x0c 0xd5 0x0b 0x22 0x00 0xf4 0x0a    ...."...\n0600   0x61 0x0a 0xd3 0x09 0x50 0x09 0xd9 0x08    a...P...\n0608   0x74 0x08 0x17 0x08 0xcd 0x07 0xb7 0x07    t.......\n0610   0xaa 0x07 0x22 0x00 0x22 0x00 0x22 0x00    ..".".".\n0618   0x22 0x00 0x22 0x00 0x0e 0x00 0xc6 0x07    ".".....\n0620   0xff 0x07 0x28 0x08 0x22 0x00 0x22 0x00    ..(.".".\n0628   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".\n0630   0x0f 0x00 0x64 0x08 0x9a 0x08 0x95 0x08    ..d.....\n0638   0x93 0x08 0x85 0x08 0x46 0x08 0x45 0x08    ....F.E.\n0640   0x6f 0x08 0x76 0x08 0x74 0x08 0x5a 0x08    o.v.t.Z.\n0648   0x5f 0x08 0x6a 0x08 0xcf 0x08 0x55 0x09    _.j...U.\n0650   0x5f 0x09 0x7f 0x09 0x7d 0x09 0x65 0x09    _...}.e.\n0658   0x6d 0x09 0x22 0x09 0xb7 0x08 0x22 0x00    m."...".\n0660   0x30 0x08 0xd8 0x07 0x95 0x07 0x40 0x07    0.....@.\n0668   0x30 0x07 0x3b 0x07 0x22 0x00 0x8c 0x07    0.;."...\n0670   0xce 0x07 0xe3 0x07 0x19 0x08 0x53 0x08    ......S.\n0678   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".\n0680   0x22 0x00 0x0e 0x00 0x5c 0x08 0x5b 0x08    "...\\.[.\n0688   0x6a 0x08 0x22 0x00 0x22 0x00 0x22 0x00    j.".".".\n0690   0x22 0x00 0x22 0x00 0x22 0x00 0x0f 0x00    "."."...\n0698   0x91 0x08 0xc6 0x08 0x0e 0x09 0x54 0x09    ......T.\n06A0   0x7c 0x09 0xa8 0x09 0xd5 0x09 0x01 0x0a    |.......\n06A8   0x24 0x0a 0x82 0x0a 0xf3 0x0a 0xf5 0x0a    $.......\n06B0   0x0a 0x0b 0x23 0x0b 0x3c 0x0b 0x55 0x0b    ..#.<.U.\n06B8   0xd9 0x0b 0x1e 0x0c 0x1b 0x0c 0x22 0x0c    ......".\n06C0   0x27 0x0c 0x27 0x0c 0x27 0x0c 0x1f 0x0c    \'.\'.\'...\n06C8   0x16 0x0c 0x22 0x00 0x70 0x0c 0x22 0x00    ..".p.".\n06D0   0x83 0x0c 0x22 0x00 0x5b 0x0c 0x22 0x00    ..".[.".\n06D8   0x42 0x0c 0x38 0x0c 0x22 0x00 0x2f 0x0c    B.8."./.\n06E0   0x22 0x00 0x2f 0x0c 0x22 0x00 0x2f 0x0c    "./."./.\n06E8   0x22 0x00 0x33 0x0c 0x22 0x00 0x47 0x0c    ".3.".G.\n06F0   0x22 0x00 0x5c 0x0c 0x79 0x0c 0x7f 0x0c    ".\\.y...\n06F8   0x77 0x0c 0x82 0x0c 0x22 0x00 0x9c 0x0c    w..."...\n0700   0x2f 0x0d 0xba 0x0d 0xf1 0x0d 0x24 0x0e    /.....$.\n0708   0x22 0x00 0x6a 0x0e 0x22 0x00 0x71 0x0e    ".j.".q.\n0710   0x22 0x00 0x2f 0x0e 0x22 0x00 0x06 0x0e    "./."...\n0718   0x22 0x00 0xeb 0x0d 0x22 0x00 0xd8 0x0d    "..."...\n0720   0xd4 0x0d 0xdd 0x0d 0xc5 0x0d 0xc1 0x0d    ........\n0728   0xc9 0x0d 0xd3 0x0d 0xdb 0x0d 0xdf 0x0d    ........\n0730   0x33 0x0e 0xff 0x0d 0x79 0x0d 0x45 0x0d    3...y.E.\n0738   0x27 0x0d 0x1c 0x0d 0x1b 0x0d 0x46 0x0d    \'.....F.\n0740   0xe4 0x0e 0xa3 0x0f 0xb2 0x0f 0xc2 0x0f    ........\n0748   0xd6 0x0f 0xe0 0x0f 0xeb 0x0f 0xf5 0x0f    ........\n0750   0xf9 0x0f 0xef 0x0f 0xe1 0x0f 0xcb 0x0f    ........\n0758   0xbc 0x0f 0x15 0x10 0x26 0x10 0xf0 0x0f    ....&...\n0760   0x82 0x0f 0xc6 0x0e 0x64 0x0e 0x2d 0x0e    ....d.-.\n0768   0xfc 0x0d 0xe5 0x0d 0xc6 0x0e 0x58 0x0f    ......X.\n0770   0x60 0x0f 0x7a 0x0f 0x99 0x0f 0xd7 0x0f    `.z.....\n0778   0x13 0x10 0x0e 0x10 0x06 0x10 0xf8 0x0f    ........\n0780   0x06 0x10 0xcf 0x0f 0x90 0x0f 0x74 0x0f    ......t.\n0788   0x61 0x0f 0xf1 0x0f 0x8f 0x10 0x6c 0x10    a.....l.\n0790   0x5b 0x10 0xed 0x0f 0x72 0x0f 0x44 0x0f    [...r.D.\n0798   0x1e 0x0f 0x09 0x0f 0x9e 0x0f 0xc8 0x0f    ........\n07A0   0x78 0x0f 0xc9 0x0f 0x37 0x10 0x4d 0x10    x...7.M.\n07A8   0x68 0x10 0xc8 0x10 0xc8 0x10 0x40 0x11    h.....@.\n07B0   0x87 0x11 0x9c 0x11 0xb4 0x11 0x53 0x12    ......S.\n07B8   0x22 0x00 0x32 0x13 0xe8 0x12 0x03 0x13    ".2.....\n07C0   0xa6 0x13 0x01 0x14 0x15 0x14 0x12 0x14    ........\n07C8   0x8f 0x14 0x47 0x15 0xc9 0x15 0x60 0x16    ..G...`.\n07D0   0x01 0x17 0x22 0x00 0x22 0x00 0x22 0x00    ..".".".\n07D8   0x22 0x00 0x22 0x00 0x0e 0x00 0x64 0x17    "."...d.\n07E0   0xa3 0x17 0xfb 0x17 0x22 0x00 0x22 0x00    ....".".\n07E8   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".\n07F0   0x0f 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ..".".".\n07F8   0x22 0x00 0x08 0x00 0x2b 0x00 0x24 0x00    "...+.$.'
```
### end stats
```
```
```javascript
{'radio': {'errors.crc': 0,
           'errors.naks': 0,
           'errors.sequence': 0,
           'errors.timeouts': 0,
           'packets.received': 470L,
           'packets.transmit': 488L},
 'usb': {'errors.crc': 0,
         'errors.naks': 0,
         'errors.sequence': 0,
         'errors.timeouts': 0,
         'packets.received': 667L,
         'packets.transmit': 667L}}
```
