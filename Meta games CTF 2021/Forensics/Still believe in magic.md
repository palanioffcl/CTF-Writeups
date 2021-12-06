#  MetaCTF 2021
## Still Believe in Magic? (150pts)
### Description: 
>We found [an archive with a file in it](https://metaproblems.com/f03e38955de03e3d860d32dfd20b132f/magic.tar.gz), but there was no file extension so we're not sure what it is. Can you figure out what kind of file it is and then open it?
### Included Files:
>[magic.tar.gz](https://github.com/team23ctf/writeups/blob/main/metactf2021/Still%20Believe%20in%20Magic%3F/magic.tar.gz)

### Procedure:

Its a tar.gz file we need to extract it inorder to view the file in it. Before doing that lets use the commands like cat , strings , file , inorder to avoid to face any consequences because of that file.

When we strings the file it has MACOSX from this we infer that it was zipped in a Mac Environment. Lets check its magic bytes.

### Magic Bytes:

Magic bytes is the byte which is in the very top of the file (header of the file)
 It is also a signature of that file.
 The Magic byte of the particular file is 504b or PK in ASCII when we google ot is a Archived ZIP file.
If we extract it it has a magic.txt file Letz open it up...
### Flag:
```
MetaCTF{was_it_a_magic_trick_or_magic_bytes?}
```
