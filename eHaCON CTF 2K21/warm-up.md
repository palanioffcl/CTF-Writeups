# Warmup

## Description

>By se3ing the file we infer that its a binary file 
>which is grouped by [8](8) and classified by [!](!)which gives a byte. 
>Here i use sed and replace the ! with spaces...

## Execution 

```
root@kali~$: sed -e "s/!/ /g" < warmup_modified.txt
```

## Result 

> Eventually converted the binary to ascii. Flag:


```
EHACON{4ll_7h3_b35T} 
```
