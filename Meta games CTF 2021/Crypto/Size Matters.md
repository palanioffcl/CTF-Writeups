# MetaCTF Games 2021

## Description:

RSA is a public key cryptosystem, where one can encrypt a message with one key and decrypt it with another. We've intercepted a secure message encrypted with RSA, as well as the key used to encrypt it. Since RSA keys have to be pretty big in order to be secure, we're pretty sure you can break this one. Give it a shot!

Ciphertext: 0x2526512a4abf23fca755defc497b9ab e: 257 n: 0x592f144c0aeac50bdf57cf6a6a6e135

# Procedure:

By seeing the n , e , c values we came to know that it's a RSA encrypted cipher.

Let's break the RSA using decode.fr or your own tool to decrypt.

After make all those things. Eventually we get the Flag😍

# Flag:
```
you_broke_rsa!
```

