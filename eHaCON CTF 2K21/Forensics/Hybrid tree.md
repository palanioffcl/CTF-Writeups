# eHaCON CTF 2K21 

## forensics/hybrid-tree

>Tree has some secrets inside. Let's find if you can see.
> 
> Author: ircashem
> 
> [`Hybrid-tree`](hybrid-tree)

# Summary

> Basically it is an image forensics i tried steganography,
> metadata of the image file but nothing works
> Finally opened the file as text and obtained for the strings in the file. Finally got it :)

# Syntax 

```
root@kali:$  strings hybrid-tree.png | grep eHaCON
```

# Flag

```
EHACON{z1p_plu5_1m463}
```
