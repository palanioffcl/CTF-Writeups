#  MetaCTF 2021
## Still Believe in Magic? (150pts)

### Description: 
>We found [an archive with a file in it](https://metaproblems.com/f03e38955de03e3d860d32dfd20b132f/magic.tar.gz), but there was no file extension so we're not sure what it is. Can you figure out what kind of file it is and then open it?

### Magic Bytes:

This is a list of file signatures, data used to identify or verify the content of a file. Such signatures are also known as magic numbers or Magic Bytes.
Lets look up the header files of the file, Its .tar.gz. Go ahead by extracting it and view the magic.txt. Hence we got the flag :) 

# Flag: 
```
MetaCTF{was_it_a_magic_trick_or_magic_bytes?}
```
