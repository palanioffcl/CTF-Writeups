# MetaCTF 2021

## Sharing Files and Passwords (150pts)

### Description: 

>FTP servers are made to share files, but if its communications are not encrypted, it might be sharing passwords as well. The password in [this pcap](https://metaproblems.com/2dd6443361555f266a8c2f54c50d01e9/ftp_challenge.pcapng) to get the flag

#  Procedure: 
Lets get into the pcap file and explore using wireshark and seeing the FTP Packets we get the password.

# Flag:
```
MetaCTF{ftp_is_better_than_dropbox}
```

  
