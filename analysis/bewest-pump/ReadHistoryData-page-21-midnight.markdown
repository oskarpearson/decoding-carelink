### MIDNIGHTS analysis/bewest-pump/ReadHistoryData-page-21.data.list_opcodes.markdown: 4
## START logs/ReadHistoryData-page-21.data
#### RECORD 0 hack1 2012-11-05T03:16:57 head[46], body[0] op[0x6d]

    op hex (46)
    0000   0x6d 0xa4 0x8c 0x05 0x00 0xda 0xaa 0xfb    m.......
    0008   0x06 0x00 0x00 0x05 0x64 0x03 0x78 0x40    ....d.x@
    0010   0x01 0xec 0x24 0x00 0x0e 0x01 0xec 0x24    ..$....$
    0018   0x00 0x28 0x08 0x01 0xc4 0x5c 0x00 0x00    .(...\..
    0020   0x00 0x07 0x01 0x06 0x00 0x00 0x0c 0x00    ........
    0028   0xe8 0x00 0x00 0x00 0x0a 0x49              .....I
    decimal
            109  164  140    5    0  218  170  251
              6    0    0    5  100    3  120   64
              1  236   36    0   14    1  236   36
              0   40    8    1  196   92    0    0
              0    7    1    6    0    0   12    0
            232    0    0    0   10   73
    datetime (2012-11-05T03:16:57)
    0000   0xb9 0xd0 0x23 0x05 0x0c                   ..#..
    body (0)
    HOUR BITS: [1, 1, 0]
#### RECORD 1 PumpSuspend 2012-11-05T12:59:16 head[2], body[0] op[0x1e]

    op hex (2)
    0000   0x1e 0x00                                  ..
    decimal
             30    0
    datetime (2012-11-05T12:59:16)
    0000   0x90 0xfb 0x0c 0x05 0x0c                   .....
    body (0)
    HOUR BITS: [1, 1, 1]
#### RECORD 2 PumpResume 2012-11-05T13:14:45 head[2], body[0] op[0x1f]

    op hex (2)
    0000   0x1f 0x00                                  ..
    decimal
             31    0
    datetime (2012-11-05T13:14:45)
    0000   0xad 0xce 0x0d 0x05 0x0c                   .....
    body (0)
    HOUR BITS: [1, 1, 0]
--
    decimal
             92   11   80   99    4   12   53   20
            224  213   20
    datetime (unknown)

    body (0)

#### RECORD 24 Bolus 2012-11-05T20:43:34 head[4], body[0] op[0x01]
###### DECODED
```python
{'amount': 2.1, 'dual_component': '??', 'programmed': 2.1, 'type': '??'}
```
    op hex (4)
    0000   0x01 0x15 0x15 0x00                        ....
    decimal
              1   21   21    0
    datetime (2012-11-05T20:43:34)
    0000   0xa2 0xeb 0x54 0x05 0x0c                   ..T..
    body (0)
    HOUR BITS: [1, 1, 1]
#### RECORD 25 ResultTotals 2012-10-05T13:12:37 head[5], body[41] op[0x07]

    op hex (5)
    0000   0x07 0x00 0x00 0x05 0x2e                   .....
    decimal
              7    0    0    5   46
    datetime (2012-10-05T13:12:37)
    0000   0xa5 0x8c 0x6d 0xa5 0x8c                   ..m..
    body (41)
    hex
    0000   0x05 0x00 0x89 0x49 0xde 0x06 0x00 0x00    ...I....
    0008   0x05 0x2e 0x03 0x9e 0x46 0x01 0x90 0x1e    ....F...
    0010   0x00 0x62 0x01 0x90 0x1e 0x01 0x28 0x4a    .b....(J
    0018   0x00 0x68 0x1a 0x00 0x00 0x00 0x04 0x02    .h......
    0020   0x01 0x01 0x00 0x0c 0x00 0xe8 0x00 0x00    ........
    0028   0x00                                       .
    decimal
              5    0  137   73  222    6    0    0
              5   46    3  158   70    1  144   30
              0   98    1  144   30    1   40   74
              0  104   26    0    0    0    4    2
              1    1    0   12    0  232    0    0
              0
    HOUR BITS: [1, 0, 0] DAY BITS: [1, 0, 1] YEAR BITS: [1, 0, 0, 0]
#### RECORD 26 CalBGForPH 2012-11-06T01:05:40 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 121}
```
    op hex (2)
    0000   0x0a 0x79                                  .y
    decimal
             10  121
    datetime (2012-11-06T01:05:40)
    0000   0xa8 0xc5 0x21 0x06 0x0c                   ..!..
    body (0)
    HOUR BITS: [1, 1, 0]
#### RECORD 27 PumpSuspend 2012-11-06T13:59:42 head[2], body[0] op[0x1e]

    op hex (2)
    0000   0x1e 0x00                                  ..
--
    0000   0x5c 0x08 0x28 0x92 0x04 0x98 0x46 0x14    \.(...F.
    decimal
             92    8   40  146    4  152   70   20
    datetime (unknown)

    body (0)

#### RECORD 42 Bolus 2012-11-06T20:00:17 head[4], body[0] op[0x01]
###### DECODED
```python
{'amount': 2.5, 'dual_component': '??', 'programmed': 2.5, 'type': '??'}
```
    op hex (4)
    0000   0x01 0x19 0x19 0x00                        ....
    decimal
              1   25   25    0
    datetime (2012-11-06T20:00:17)
    0000   0x91 0xc0 0x54 0x06 0x0c                   ..T..
    body (0)
    HOUR BITS: [1, 1, 0]
#### RECORD 43 ResultTotals 2012-10-06T13:12:38 head[5], body[41] op[0x07]

    op hex (5)
    0000   0x07 0x00 0x00 0x04 0xa0                   .....
    decimal
              7    0    0    4  160
    datetime (2012-10-06T13:12:38)
    0000   0xa6 0x8c 0x6d 0xa6 0x8c                   ..m..
    body (41)
    hex
    0000   0x05 0x10 0x76 0x4e 0x02 0x07 0x00 0x00    ..vN....
    0008   0x04 0xa0 0x03 0x7c 0x4b 0x01 0x24 0x19    ...|K.$.
    0010   0x00 0x48 0x01 0x24 0x19 0x00 0xc0 0x42    .H.$...B
    0018   0x00 0x64 0x22 0x00 0x00 0x00 0x03 0x02    .d".....
    0020   0x01 0x00 0x00 0x0c 0x00 0xe8 0x00 0x00    ........
    0028   0x00                                       .
    decimal
              5   16  118   78    2    7    0    0
              4  160    3  124   75    1   36   25
              0   72    1   36   25    0  192   66
              0  100   34    0    0    0    3    2
              1    0    0   12    0  232    0    0
              0
    HOUR BITS: [1, 0, 0] DAY BITS: [1, 0, 1] YEAR BITS: [1, 0, 0, 0]
#### RECORD 44 CalBGForPH 2012-11-07T06:45:31 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 177}
```
    op hex (2)
    0000   0x0a 0xb1                                  ..
    decimal
             10  177
    datetime (2012-11-07T06:45:31)
    0000   0x9f 0xed 0x26 0x07 0x0c                   ..&..
    body (0)
    HOUR BITS: [1, 1, 1]
#### RECORD 45 BolusWizard 2012-11-07T06:45:33 head[2], body[13] op[0x5b]
###### DECODED
```python
{'_byte[5]': 11,
--
    decimal
             92   14   20  227    4   36   71   20
             98   81   20   34   91   20
    datetime (unknown)

    body (0)

#### RECORD 65 Bolus 2012-11-07T20:51:10 head[4], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.4, 'dual_component': '??', 'programmed': 0.4, 'type': '??'}
```
    op hex (4)
    0000   0x01 0x04 0x04 0x00                        ....
    decimal
              1    4    4    0
    datetime (2012-11-07T20:51:10)
    0000   0x8a 0xf3 0x54 0x07 0x0c                   ..T..
    body (0)
    HOUR BITS: [1, 1, 1]
#### RECORD 66 ResultTotals 2012-10-07T13:12:39 head[5], body[41] op[0x07]

    op hex (5)
    0000   0x07 0x00 0x00 0x04 0x72                   ....r
    decimal
              7    0    0    4  114
    datetime (2012-10-07T13:12:39)
    0000   0xa7 0x8c 0x6d 0xa7 0x8c                   ..m..
    body (41)
    hex
    0000   0x05 0x00 0x7f 0x4e 0xb4 0x07 0x00 0x00    ...N....
    0008   0x04 0x72 0x03 0x7a 0x4e 0x00 0xf8 0x16    .r.zN...
    0010   0x00 0x46 0x00 0xf8 0x16 0x00 0xbc 0x4c    .F.....L
    0018   0x00 0x3c 0x18 0x00 0x00 0x00 0x05 0x03    .<......
    0020   0x02 0x00 0x00 0x0c 0x00 0xe8 0x00 0x00    ........
    0028   0x00                                       .
    decimal
              5    0  127   78  180    7    0    0
              4  114    3  122   78    0  248   22
              0   70    0  248   22    0  188   76
              0   60   24    0    0    0    5    3
              2    0    0   12    0  232    0    0
              0
    HOUR BITS: [1, 0, 0] DAY BITS: [1, 0, 1] YEAR BITS: [1, 0, 0, 0]
#### RECORD 67 PumpSuspend 2012-11-08T10:27:56 head[2], body[0] op[0x1e]

    op hex (2)
    0000   0x1e 0x00                                  ..
    decimal
             30    0
    datetime (2012-11-08T10:27:56)
    0000   0xb8 0xdb 0x0a 0x08 0x0c                   .....
    body (0)
    HOUR BITS: [1, 1, 0]
#### RECORD 68 PumpResume 2012-11-08T11:00:04 head[2], body[0] op[0x1f]

    op hex (2)
    0000   0x1f 0x00                                  ..
    decimal
             31    0
    datetime (2012-11-08T11:00:04)
--
    0000   0x0a 0x4d                                  .M
    decimal
             10   77
    datetime (2012-11-08T21:36:41)
    0000   0xa9 0xe4 0x35 0x08 0x0c                   ..5..
    body (0)
    HOUR BITS: [1, 1, 1]
#### RECORD 83 LowReservoir 2012-11-08T23:15:47 head[2], body[0] op[0x34]
###### DECODED
```python
{'amount': 10.0}
```
    op hex (2)
    0000   0x34 0x64                                  4d
    decimal
             52  100
    datetime (2012-11-08T23:15:47)
    0000   0xaf 0xcf 0x17 0x08 0x0c                   .....
    body (0)
    HOUR BITS: [1, 1, 0]
#### RECORD 84 ResultTotals (2000, 10, 0, 0, 12, 40) head[5], body[9] op[0x07]

    op hex (5)
    0000   0x07 0x00 0x00 0x05 0x34                   ....4
    decimal
              7    0    0    5   52
    datetime ((2000, 10, 0, 0, 12, 40))
    0000   0xa8 0x8c 0x00 0x00 0x00                   .....
    body (9)
    hex
    0000   0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x02    ........
    0008   0x0e                                       .
    decimal
              0    0    0    0    0    0    0    2
             14
    HOUR BITS: [1, 0, 0]
`end logs/ReadHistoryData-page-21.data: 85 records`
