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
