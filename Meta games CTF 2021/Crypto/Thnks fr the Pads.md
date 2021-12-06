#  MetaCTF 2021

## Thnks fr the Pwds (100pts)

### Description: 

>On a red team engagement, you discover a text file on an administrator’s desktop with all of their passwords - you now have the keys to the kingdom!

During the engagement debrief, you explain what you found and how you were able to access so many systems. The administrator says that's impossible, because they encrypted all of the passwords in the file.

Here’s an example of one of their “encrypted” passwords: `TWV0YUNURntlbmNvZGluZ19pc19OMFRfdGhlX3NhbWVfYXNfZW5jcnlwdGlvbiEhfQ==`

See if you’re able to recover the Administrator's password.
 

# Procedure:

The == at the tail of the encrypted text we intializied that it's a base64 cioher lets decode

```
root@kali~$ TWV0YUNURntlbmNvZGluZ19pc19OMFRfdGhlX3NhbWVfYXNfZW5jcnlwdGlvbiEhfQ== | base64 
```

# Flag:
 
 ```
 MetaCTF{encoding_is_N0T_the_same_as_encryption!!}
 ```
