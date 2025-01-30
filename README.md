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
