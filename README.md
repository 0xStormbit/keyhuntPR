command
```
#!/bin/sh
time ./keyhunt -m bsgs -t 8 -f tests/135.pub -k 384  -r 4000000000000008335954177800000000:7fffffffffffffffffffffffffffffffff
```
```
+] Version 0.2.230519 Satoshi Quest, developed by AlbertoBSD
[+] Threads : 8
[+] K factor 384
[+] Mode BSGS sequential
[+] Opening file tests/135.pub
[+] Added 1 points from file
[+] Range 
[+] -- from : 0x4000000000000008267155584180000000
[+] -- to   : 0x4fffffffffffffffffffffffffffffffff
[+] N = 0xfffc0000000
[+] Bloom filter for 1610612736 elements : 5520.99 MB
[+] Bloom filter for 50331648 elements : 172.53 MB
[+] Bloom filter for 1572864 elements : 5.39 MB
[+] Allocating 24.00 MB for 1572864 bP Points
[+] processing 1610612736/1610612736 bP points : 100%     
[+] Making checkums .. ... done
[+] Sorting 1572864 elements... Done!

+] Thread 0x40000000000000083357bc3dd780000000   nds: ~8 Pkeys/s (8048969104977099 keys/s)
```

command
```
#!/bin/sh
time ./keyhunt -m bsgs -t 8 -f tests/135.pub -k 384  -r 400000000000000003c88a1d9b00000000:7fffffffffffffffffffffffffffffffff
```
```
+] Version 0.2.230519 Satoshi Quest, developed by AlbertoBSD
[+] Threads : 8
[+] K factor 384
[+] Mode BSGS sequential
[+] Opening file tests/135.pub
[+] Added 1 points from file
[+] Range 
[+] -- from : 0x4000000000000000000000000000000000
[+] -- to   : 0x7fffffffffffffffffffffffffffffffff
[+] N = 0xfffc0000000
[+] Bloom filter for 1610612736 elements : 5520.99 MB
[+] Bloom filter for 50331648 elements : 172.53 MB
[+] Bloom filter for 1572864 elements : 5.39 MB
[+] Allocating 24.00 MB for 1572864 bP Points
[+] processing 1610612736/1610612736 bP points : 100%     
[+] Making checkums .. ... done
[+] Sorting 1572864 elements... Done!
^C] Thread 0x400000000000000003c88a1d9b00000000   ds: ~6 Pkeys/s (6530166779379785 keys/s)
```



command
```
#!/bin/sh
time ./keyhunt -m bsgs -t 8 -f tests/67.pub -k 384  -r 6ffffbf2000000000:7ffffffffffffffff
```
```
./runpubv6
[+] Version 0.2.230519 Satoshi Quest, developed by AlbertoBSD
[+] Threads : 8
[+] K factor 384
[+] Mode BSGS sequential
[+] Opening file tests/67.pub
[+] Added 1 points from file
[+] Range 
[+] -- from : 0x6ffffbf2000000000
[+] -- to   : 0x7ffffffffffffffff
[+] N = 0xfffc0000000
[+] Bloom filter for 1610612736 elements : 5520.99 MB
[+] Bloom filter for 50331648 elements : 172.53 MB
[+] Bloom filter for 1572864 elements : 5.39 MB
[+] Allocating 24.00 MB for 1572864 bP Points
[+] processing 1610612736/1610612736 bP points : 100%     
[+] Making checkums .. ... done
[+] Sorting 1572864 elements... Done!
[+] Thread 0x7ffffff0f00000000   ys in 2970 seconds: ~6 Pkeys/s (6202874961098218 keys/s)
End

real    117m22.457s
user    211m4.590s
sys     2m44.191s

```

command
```
#!/bin/sh
time ./keyhunt -m bsgs -t 8 -f tests/67.pub -k 384  -r 5ffffff2f00000000:6ffffffffffffffff
```

output
```
[+] Version 0.2.230519 Satoshi Quest, developed by AlbertoBSD
[+] Threads : 8
[+] K factor 384
[+] Mode BSGS sequential
[+] Opening file tests/67.pub
[+] Added 1 points from file
[+] Range 
[+] -- from : 0x5ffffff2f00000000
[+] -- to   : 0x6ffffffffffffffff
[+] N = 0xfffc0000000
[+] Bloom filter for 1610612736 elements : 5520.99 MB
[+] Bloom filter for 50331648 elements : 172.53 MB
[+] Bloom filter for 1572864 elements : 5.39 MB
[+] Allocating 24.00 MB for 1572864 bP Points
[+] processing 1610612736/1610612736 bP points : 100%     
[+] Making checkums .. ... done
[+] Sorting 1572864 elements... Done!
[+] Thread 0x6ffffbf2000000000   ys in 2940 seconds: ~6 Pkeys/s (6239687201160012 keys/s)
End

real    118m42.495s
user    212m53.942s
sys     2m44.423s
```
command
```
#!/bin/sh
time ./keyhunt -m bsgs -t 8 -f tests/67.pub -k 384  -r 5ffffff2f00000000:6ffffffffffffffff
```

output
```
[+] Version 0.2.230519 Satoshi Quest, developed by AlbertoBSD
[+] Threads : 8
[+] K factor 384
[+] Mode BSGS sequential
[+] Opening file tests/67.pub
[+] Added 1 points from file
[+] Range 
[+] -- from : 0x5ffffff2f00000000
[+] -- to   : 0x6ffffffffffffffff
[+] N = 0xfffc0000000
[+] Bloom filter for 1610612736 elements : 5520.99 MB
[+] Bloom filter for 50331648 elements : 172.53 MB
[+] Bloom filter for 1572864 elements : 5.39 MB
[+] Allocating 24.00 MB for 1572864 bP Points
[+] processing 1610612736/1610612736 bP points : 100%     
[+] Making checkums .. ... done
[+] Sorting 1572864 elements... Done!
[+] Thread 0x6ba62b59880000000   ys in 2130 seconds: ~6 Pkeys/s (6265293503129651 keys/s)
```


```sh
#!/bin/sh
time ./keyhunt -m bsgs -t 8 -f tests/67.pub -k 384  -r 527cf200000000000:5ffffffffffffffff
```

```
$ ./runpub67v0.2
[+] Version 0.2.230519 Satoshi Quest, developed by AlbertoBSD
[+] Threads : 8
[+] K factor 384
[+] Mode BSGS sequential
[+] Opening file tests/67.pub
[+] Added 1 points from file
[+] Range 
[+] -- from : 0x527cf200000000000
[+] -- to   : 0x5ffffffffffffffff
[+] N = 0xfffc0000000
[+] Bloom filter for 1610612736 elements : 5520.99 MB
[+] Bloom filter for 50331648 elements : 172.53 MB
[+] Bloom filter for 1572864 elements : 5.39 MB
[+] Allocating 24.00 MB for 1572864 bP Points
[+] processing 1610612736/1610612736 bP points : 100%     
[+] Making checkums .. ... done
[+] Sorting 1572864 elements... Done!
[+] Thread 0x5ffffff2f00000000   ys in 2400 seconds: ~6 Pkeys/s (6438156532365393 keys/s)
End

real    108m9.379s
user    195m11.447s
sys     2m31.894s
```

```sh
#!/bin/sh
time ./keyhunt -m bsgs -t 8 -f tests/67.pub -k 384  -r 527cf200000000000:5ffffffffffffffff
```
output
```
:~/keyhunt$ ./runpub67v0.2
[+] Version 0.2.230519 Satoshi Quest, developed by AlbertoBSD
[+] Threads : 8
[+] K factor 384
[+] Mode BSGS sequential
[+] Opening file tests/67.pub
[+] Added 1 points from file
[+] Range 
[+] -- from : 0x527cf200000000000
[+] -- to   : 0x5ffffffffffffffff
[+] N = 0xfffc0000000
[+] Bloom filter for 1610612736 elements : 5520.99 MB
[+] Bloom filter for 50331648 elements : 172.53 MB
[+] Bloom filter for 1572864 elements : 5.39 MB
[+] Allocating 24.00 MB for 1572864 bP Points
[+] processing 1610612736/1610612736 bP points : 100%     
[+] Making checkums .. ... done
[+] Sorting 1572864 elements... Done!
[+] Thread 0x5406e7d8100000000   s in 270 seconds: ~6 Pkeys/s (6433525834932406 keys/s)

```





```
#!/bin/sh
time ./keyhunt -m bsgs -t 8 -f tests/67.pub -k 64  -r 50000000000000000:5ffffffffffffffff

```
output
```
[+] Version 0.2.230519 Satoshi Quest, developed by AlbertoBSD
[+] Threads : 8
[+] K factor 64
[+] Mode BSGS sequential
[+] Opening file tests/67.pub
[+] Added 1 points from file
[+] Range 
[+] -- from : 0x50000000000000000
[+] -- to   : 0x5ffffffffffffffff
[+] N = 0x100000000000
[+] Bloom filter for 268435456 elements : 920.17 MB
[+] Bloom filter for 8388608 elements : 28.76 MB
[+] Bloom filter for 262144 elements : 0.90 MB
[+] Allocating 4.00 MB for 262144 bP Points
[+] processing 268435456/268435456 bP points : 100%     
[+] Making checkums .. ... done
[+] Sorting 262144 elements... Done!
[+] Thread 0x51a19e00000000000   s in 1410 seconds: ~1 Pkeys/s (1318191234017474 keys/s)




```



test commmand 63.pub
```
#!/bin/sh
time ./keyhunt -m bsgs -t 8 -f tests/63.pub -k 16 -r 7cce4e0daccf6808:7ccf5ffdaccf6808

```
output
```
:~/keyhunt$ ./testpub63
[+] Version 0.2.230519 Satoshi Quest, developed by AlbertoBSD
[+] Threads : 8
[+] K factor 16
[+] Mode BSGS sequential
[+] Opening file tests/63.pub
[+] Added 1 points from file
[+] Range 
[+] -- from : 0x7cce4e0daccf6808
[+] -- to   : 0x7ccf5ffdaccf6808
[+] N = 0x100000000000
[+] Bloom filter for 67108864 elements : 230.04 MB
[+] Bloom filter for 2097152 elements : 7.19 MB
[+] Bloom filter for 65536 elements : 0.88 MB
[+] Allocating 1.00 MB for 65536 bP Points
[+] processing 67108864/67108864 bP points : 100%     
[+] Making checkums .. ... done
[+] Sorting 65536 elements... Done!
[+] Thread Key found privkey 7cce5efdaccf6808   
[+] Publickey 0365ec2994b8cc0a20d40dd69edfe55ca32a54bcbbaa6b0ddcff36049301a54579
All points were found

real    1m47.271s
user    3m15.463s
sys     0m3.196s

```



```
time ./keyhunt -m bsgs -t 8 -f tests/67.pub -k 16  -r 4ffffe00000000000:50000000000000000
```

```
[+] Version 0.2.230519 Satoshi Quest, developed by AlbertoBSD
[+] Threads : 8
[+] K factor 16
[+] Mode BSGS sequential
[+] Opening file tests/67.pub
[+] Added 1 points from file
[+] Range 
[+] -- from : 0x4c3b9600000000000
[+] -- to   : 0x50000000000000000
[+] N = 0x100000000000
[+] Bloom filter for 67108864 elements : 230.04 MB
[+] Bloom filter for 2097152 elements : 7.19 MB
[+] Bloom filter for 65536 elements : 0.88 MB
[+] Allocating 1.00 MB for 65536 bP Points
[+] processing 67108864/67108864 bP points : 100%     
[+] Making checkums .. ... done
[+] Sorting 65536 elements... Done!
[+] Thread 0x4c62e400000000000    in 390 seconds: ~452 Tkeys/s (452434938526903 [+] Thread 0x4c631e00000000000   


[+] Thread 0x4ffffe00000000000   s in 9540 seconds: ~454 Tkeys/s (454877872150971 keys/s)
End

real    161m0.603s
user    298m57.033s
sys     0m35.525s
```

```
time ./keyhunt -m bsgs -t 8 -f tests/67.pub -k 16  -r 4eebec00000000000:50000000000000000
```

```
[+] Version 0.2.230519 Satoshi Quest, developed by AlbertoBSD
[+] Threads : 8
[+] K factor 16
[+] Mode BSGS sequential
[+] Opening file tests/67.pub
[+] Added 1 points from file
[+] Range 
[+] -- from : 0x4c3b9600000000000
[+] -- to   : 0x50000000000000000
[+] N = 0x100000000000
[+] Bloom filter for 67108864 elements : 230.04 MB
[+] Bloom filter for 2097152 elements : 7.19 MB
[+] Bloom filter for 65536 elements : 0.88 MB
[+] Allocating 1.00 MB for 65536 bP Points
[+] processing 67108864/67108864 bP points : 100%     
[+] Making checkums .. ... done
[+] Sorting 65536 elements... Done!
[+] Thread 0x4c62e400000000000    in 390 seconds: ~452 Tkeys/s (452434938526903 [+] Thread 0x4c631e00000000000   


[+] Thread 0x4eebec00000000000   s in 6810 seconds: ~453 Tkeys/s (453485740286791 keys/s)
```
```
time ./keyhunt -m bsgs -t 8 -f tests/67.pub -k 16  -r 4e4a3000000000000:50000000000000000
```
output
```
[+] Version 0.2.230519 Satoshi Quest, developed by AlbertoBSD
[+] Threads : 8
[+] K factor 16
[+] Mode BSGS sequential
[+] Opening file tests/67.pub
[+] Added 1 points from file
[+] Range 
[+] -- from : 0x4c3b9600000000000
[+] -- to   : 0x50000000000000000
[+] N = 0x100000000000
[+] Bloom filter for 67108864 elements : 230.04 MB
[+] Bloom filter for 2097152 elements : 7.19 MB
[+] Bloom filter for 65536 elements : 0.88 MB
[+] Allocating 1.00 MB for 65536 bP Points
[+] processing 67108864/67108864 bP points : 100%     
[+] Making checkums .. ... done
[+] Sorting 65536 elements... Done!
[+] Thread 0x4c62e400000000000    in 390 seconds: ~452 Tkeys/s (452434938526903 [+] Thread 0x4c631e00000000000   


[+] Thread 0x4e4a3000000000000   s in 5220 seconds: ~452 Tkeys/s (452422494893981 keys/s)
```
```
time ./keyhunt -m bsgs -t 8 -f tests/67.pub -k 16  -r 4d026c00000000000:50000000000000000
```
```
[+] Version 0.2.230519 Satoshi Quest, developed by AlbertoBSD
[+] Threads : 8
[+] K factor 16
[+] Mode BSGS sequential
[+] Opening file tests/67.pub
[+] Added 1 points from file
[+] Range 
[+] -- from : 0x4c3b9600000000000
[+] -- to   : 0x50000000000000000
[+] N = 0x100000000000
[+] Bloom filter for 67108864 elements : 230.04 MB
[+] Bloom filter for 2097152 elements : 7.19 MB
[+] Bloom filter for 65536 elements : 0.88 MB
[+] Allocating 1.00 MB for 65536 bP Points
[+] processing 67108864/67108864 bP points : 100%     
[+] Making checkums .. ... done
[+] Sorting 65536 elements... Done!
[+] Thread 0x4c62e400000000000    in 390 seconds: ~452 Tkeys/s (452434938526903 [+] Thread 0x4c631e00000000000   


[+] Thread 0x4d0a2c00000000000    in 2070 seconds: ~448 Tkeys/s (448524256367197 keys/s)

```

```
time ./keyhunt -m bsgs -t 8 -f tests/67.pub -k 16  -r 4c3b9600000000000:50000000000000000
```

```
[+] Version 0.2.230519 Satoshi Quest, developed by AlbertoBSD
[+] Threads : 8
[+] K factor 16
[+] Mode BSGS sequential
[+] Opening file tests/67.pub
[+] Added 1 points from file
[+] Range 
[+] -- from : 0x4c3b9600000000000
[+] -- to   : 0x50000000000000000
[+] N = 0x100000000000
[+] Bloom filter for 67108864 elements : 230.04 MB
[+] Bloom filter for 2097152 elements : 7.19 MB
[+] Bloom filter for 65536 elements : 0.88 MB
[+] Allocating 1.00 MB for 65536 bP Points
[+] processing 67108864/67108864 bP points : 100%     
[+] Making checkums .. ... done
[+] Sorting 65536 elements... Done!
[+] Thread 0x4c4f9400000000000   in 180 seconds: ~451 Tkeys/s (451728243873837 keys/s)
```
```
time ./keyhunt -m bsgs -t 8 -f tests/67.pub -k 16  -r 4b2c1e00000000000:50000000000000000
```
```
[+] Version 0.2.230519 Satoshi Quest, developed by AlbertoBSD
[+] Threads : 8
[+] K factor 16
[+] Mode BSGS sequential
[+] Opening file tests/67.pub
[+] Added 1 points from file
[+] Range 
[+] -- from : 0x4a060a00000000000
[+] -- to   : 0x50000000000000000
[+] N = 0x100000000000
[+] Bloom filter for 67108864 elements : 230.04 MB
[+] Bloom filter for 2097152 elements : 7.19 MB
[+] Bloom filter for 65536 elements : 0.88 MB
[+] Allocating 1.00 MB for 65536 bP Points
[+] processing 67108864/67108864 bP points : 100%     
[+] Making checkums .. ... done
[+] Sorting 65536 elements... Done!
[+] Thread 0x4b35d200000000000   s in 3270 seconds: ~414 Tkeys/s (414809759256468 keys/s

```
```
time ./keyhunt -m bsgs -t 8 -f tests/67.pub -k 16  -r 4b061c00000000000:50000000000000000
```

```
time ./keyhunt -m bsgs -t 8 -f tests/67.pub -k 16  -r 49028400000000000:50000000000000000
```

```
time ./keyhunt -m bsgs -t 8 -f tests/67.pub -k 16  -r 48b21800000000000:50000000000000000
```

```
time ./keyhunt -m bsgs -t 8 -f tests/67.pub -k 16  -r 48015000000000000:50000000000000000
```
output:
```
[+] Version 0.2.230519 Satoshi Quest, developed by AlbertoBSD
[+] Threads : 8
[+] K factor 16
[+] Mode BSGS sequential
[+] Opening file tests/67.pub
[+] Added 1 points from file
[+] Range 
[+] -- from : 0x40000000000000000
[+] -- to   : 0x50000000000000000
[+] N = 0x100000000000
[+] Bloom filter for 67108864 elements : 230.04 MB
[+] Bloom filter for 2097152 elements : 7.19 MB
[+] Bloom filter for 65536 elements : 0.88 MB
[+] Allocating 1.00 MB for 65536 bP Points
[+] processing 67108864/67108864 bP points : 100%     
[+] Making checkums .. ... done
[+] Sorting 65536 elements... Done!
[+] Thread 0x43decc00000000000   s in 10380 seconds: ~428 Tkeys/s (4286527643886[+] Total 4462398727654473728 keys in 10410 seconds: ~428 Tkeys/s (4286646232136[+] Thread 0x43df0200000000000   


[+] Thread 0x4826e600000000000   s in 21810 seconds: ~430 Tkeys/s (430677040964658 keys/s)


```
```
time ./keyhunt -m bsgs -t 8 -f tests/67.pub -k 16  -r 47006400000000000:50000000000000000
```

```
time ./keyhunt -m bsgs -t 8 -f tests/67.pub -k 16  -r 461c5a00000000000:50000000000000000
```

```
time ./keyhunt -m bsgs -t 8 -f tests/67.pub -k 16  -r 45a7a600000000000:50000000000000000
```

```
time ./keyhunt -m bsgs -t 8 -f tests/67.pub -k 16  -r 45504a00000000000:50000000000000000
```

![Snap 2025-01-31 at 1 19 12 PM](https://github.com/user-attachments/assets/3deb7568-6b86-41e2-9476-419809cbae0d)

Fri 31 Jan 2025, 1:18 PM 

```
time ./keyhunt -m bsgs -t 8 -f tests/67.pub -k 16  -r 40000000000000000:50000000000000000

```
output

```
[+] Version 0.2.230519 Satoshi Quest, developed by AlbertoBSD
[+] Threads : 8
[+] K factor 16
[+] Mode BSGS sequential
[+] Opening file tests/67.pub
[+] Added 1 points from file
[+] Range 
[+] -- from : 0x40000000000000000
[+] -- to   : 0x50000000000000000
[+] N = 0x100000000000
[+] Bloom filter for 67108864 elements : 230.04 MB
[+] Bloom filter for 2097152 elements : 7.19 MB
[+] Bloom filter for 65536 elements : 0.88 MB
[+] Allocating 1.00 MB for 65536 bP Points
[+] processing 67108864/67108864 bP points : 100%     
[+] Making checkums .. ... done
[+] Sorting 65536 elements... Done!
[+] Thread 0x428c1000000000000   s in 6840 seconds: ~428 Tkeys/s (428488040204635 keys/s)

```
































```
time ./keyhunt -m bsgs -t 8 -f tests/67.pub -k 512 -s 0 -S -b 67
```
```
[+] Version 0.2.230430 Satoshi Quest, developed by AlbertoBSD
[+] Threads : 8
[+] K factor 512
[+] Turn off stats output
[+] Mode BSGS secuential
[+] Opening file tests/63.pub
[+] Added 1 points from file
[+] Bit Range 63
[+] -- from : 0x4000000000000000
[+] -- to   : 0x8000000000000000
[+] N = 0x100000000000
[+] Bloom filter for 2147483648 elements : 7361.33 MB
[+] Bloom filter for 67108864 elements : 230.04 MB
[+] Bloom filter for 2097152 elements : 7.19 MB
[+] Allocating 32.00 MB for 2097152 bP Points
[+] Reading bloom filter from file keyhunt_bsgs_4_2147483648.blm .... Done!
[+] Reading bloom filter from file keyhunt_bsgs_6_67108864.blm .... Done!
[+] Reading bP Table from file keyhunt_bsgs_2_2097152.tbl .... Done!
[+] Reading bloom filter from file keyhunt_bsgs_7_2097152.blm .... Done!
[+] Thread Key found privkey 7cce5efdaccf6808
[+] Publickey 0365ec2994b8cc0a20d40dd69edfe55ca32a54bcbbaa6b0ddcff36049301a54579
All points were found00000000
[+] Thread 0x7cf4d00000000000
real    4m11.358s
user    26m23.474s
sys     0m20.061s
```

# keyhunt customizations tool's logs

Thus 30 Jan 2025 8:03:45 PM 

```
time ./keyhunt -m bsgs -t 8 -f tests/67.pub -r 40000000000000000:4000fffffffffffff
vbox2025z@cloudshell:~/keyhunt$ ./runpub0
[+] Version 0.2.230519 Satoshi Quest, developed by AlbertoBSD
[+] Threads : 8
[+] Mode BSGS sequential
[+] Opening file tests/67.pub
[+] Added 1 points from file
[+] Range 
[+] -- from : 0x40000000000000000
[+] -- to   : 0x4000fffffffffffff
[+] N = 0x100000000000
[+] Bloom filter for 4194304 elements : 14.38 MB
[+] Bloom filter for 131072 elements : 0.88 MB
[+] Bloom filter for 4096 elements : 0.88 MB
[+] Allocating 0.00 MB for 4096 bP Points
[+] processing 4194304/4194304 bP points : 100%     
[+] Making checkums .. ... done
[+] Sorting 4096 elements... Done!
[+] Thread 0x4000fe00000000000   n 120 seconds: ~29 Tkeys/s (29027106973286 keys/s)
End

real    2m34.333s
user    4m47.129s
sys     0m0.364s
tvbox2025z@cloudshell:~/keyhunt$ 

```
```
# net disconnect logs:
3rd or 4th times
[+] Version 0.2.230519 Satoshi Quest, developed by AlbertoBSD
[+] Threads : 8
[+] K factor 16
[+] Mode BSGS sequential
[+] Opening file tests/67.pub
[+] Added 1 points from file
[+] Range 
[+] -- from : 0x4c3b9600000000000
[+] -- to   : 0x50000000000000000
[+] N = 0x100000000000
[+] Bloom filter for 67108864 elements : 230.04 MB
[+] Bloom filter for 2097152 elements : 7.19 MB
[+] Bloom filter for 65536 elements : 0.88 MB
[+] Allocating 1.00 MB for 65536 bP Points
[+] processing 67108864/67108864 bP points : 100%     
[+] Making checkums .. ... done
[+] Sorting 65536 elements... Done!
[+] Thread 0x4c62e400000000000    in 390 seconds: ~452 Tkeys/s (452434938526903 [+] Thread 0x4c631e00000000000   


[+] Thread 0x4c6e3e00000000000    in 510 seconds: ~440 Tkeys/s (440011618005040 keys/s)
```

```
crunch 64 64 01234567890abcdef -s 0000000000000000000000000000000000000000000000040000000098b55b19 -t 00000000000000000000000000000000000000000
0000004@@@@@@@@@@@@@@@@ -e 000000000000000000000000000000000000000000000004ffffffffffffffff | ./brainflayer -v -t priv -x -b address.blf -o found.txt




```


```
crunch 64 64 01234567890abcdef -s 000000000000000000000000000000000000000000000004000000005ce40860 -t 00000000000000000000000000000000000000000
0000004@@@@@@@@@@@@@@@@ -e 000000000000000000000000000000000000000000000004ffffffffffffffff | ./brainflayer -v -t priv -x -b address.blf -o found.txt
```







https://www.youtube.com/watch?v=foil0hzl4Pg&pp=ygUWYmVzdCBicmFpbmZsYXllciBzcGVlZA%3D%3D


tvbox2025z@cloudshell:~/brainflayer$ crunch 64 64 01234567890abcdef -s 000000000000000000000000000000000000000000000004000000001dd70430 -t 00000000000000000000000000000000000000000
0000004@@@@@@@@@@@@@@@@ -e 000000000000000000000000000000000000000000000004ffffffffffffffff | ./brainflayer -v -t priv -x -b address.blf -o found.txt                               


Crunch will now generate the following amount of data: 18446744041168564176 bytes
17592186013382 MB
17179869153 GB
16777215 TB
16383 PB
Crunch will now generate the following number of lines: 18446744073208921040 
^CCrunch ending at 000000000000000000000000000000000000000000000004000000005ce40860
