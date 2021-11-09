# **RSA 1**


# Description

```
I have a lot of big numbers. Here, have a few!
```

-----
big_numers.txt

**We know it's a easy rsa challenge, where we are given with n,e,c to solve this**

**I use dcode.fr for instantly**

[https://github.com/palanioffcl/CTF-Writeups/blob/main/Deconstruct%20CTF/rsa%20deconstruct.png](http://)

Here we use RsaCtfTool to solve :)

```
root@kali:~/RsaCtfTool# python3 RsaCtfTool.py -n 23519325203263800569051788832344215043304346715918641803 -e 71 \--uncipher 10400286653072418349777706076384847966640064725838262071

private argument is not set, the private key will not be displayed, even if recovered.



[*] Testing key /tmp/tmps9_oxcq2.

[*] Performing mersenne_primes attack on /tmp/tmps9_oxcq2.

 24%|███████████████████████████████████                                                                                                                  | 12/51 [00:00<00:00, 262144.00it/s]

[*] Performing smallq attack on /tmp/tmps9_oxcq2.

[*] Performing pastctfprimes attack on /tmp/tmps9_oxcq2.

100%|███████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████| 113/113 [00:00<00:00, 973216.33it/s]

[*] Performing fibonacci_gcd attack on /tmp/tmps9_oxcq2.

100%|█████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████| 9999/9999 [00:00<00:00, 264363.22it/s]

[*] Performing system_primes_gcd attack on /tmp/tmps9_oxcq2.

100%|████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████| 7007/7007 [00:00<00:00, 1218469.66it/s]

[*] Performing factordb attack on /tmp/tmps9_oxcq2.

[*] Attack success with factordb method !



Results for /tmp/tmps9_oxcq2:



Unciphered data :

HEX : 0x6473637b7430305f6d7563685f6d3474685f383839387d

INT (big endian) : 9621269132073872010525638902903988134500010392708266109

INT (little endian) : 11993657127041496499871362328745731192598296696556057444

utf-8 : dsc{t00_much_m4th_8898}

STR : b'dsc{t00_much_m4th_8898}'

```

## Flag


-----
`**dsc{t00_much_m4th_8898}**`
