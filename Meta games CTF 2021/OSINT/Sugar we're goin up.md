# MetaCTF 2021

## Sugar, We're Goin Up (125pts)

### Description: 

>In September 2021, GitLab upgraded the CVSSv3 score for a critical remote code execution vulnerability to 10.0, the highest possible score. Although a patch was released in April, numerous public-facing, unpatched GitLab instances remain vulnerable.

What is the CVE number for this critical, actively exploited vulnerability? The flag format will be `CVE-XXXX-XXXX`.

### G00gling:

By using Google we can search for a GitLab RCE vulnerability and check out anything recent.

Sure enough, the first [result](https://www.rapid7.com/blog/post/2021/11/01/gitlab-unauthenticated-remote-code-execution-cve-2021-22205-exploited-in-the-wild/) talks about a patch released in April and an upgraded CVSSv3 score.

Certainly, this is our intended CVE.



### Flag:
```
CVE-2021-22205
```
