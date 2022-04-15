# Enum4Linux

Enum4linux is **an enumeration tool capable of detecting and extracting data from Windows and Linux operating systems**, including those that are Samba (SMB) hosts on a network. Enum4linux is capable of discovering the following: Password policies on a target. The operating system of a remote target.


```

enum4linux -A 10.10.10.26


enum4linux -u guru -p cloudflare -n 10.10.10.x


enum4linux -u guru -p cloudflare -U 10.10.10.x


enum4linux -u guru -p cloudflare -o 10.10.10.x


enum4linux -u guru -p cloudflare -P 10.10.10.x


enum4linux -u guru -p cloudflare -G 10.10.10.x


enum4linux -u guru -p cloudflare -S 10.10.10.x


• -U -> Enumerate the users on the share


• -o -> Enumerate the Operating System of the share


• -P -> Enumerate the password policy of the share


• -G -> Enumerate the Group policy of the share


• -S -> Enumerate the Shared policy of the share


```



---

**Enum4Linux Wins Enumeration :**

-   enum4linux -u martin -p apple -U 10.10.10.12 -> Users Enumeration
    
-   enum4linux -u martin -p apple -o 10.10.10.12 -> OS Enumeration
    
-   enum4linux -u martin -p apple -P 10.10.10.12 -> Password Policy Information
    
-   enum4linux -u martin -p apple -G 10.10.10.12 -> Groups Information
    
-   enum4linux -u martin -p apple -S 10.10.10.12 -> Share Policy Information (SMB Shares Enumeration