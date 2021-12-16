# VR1210v-shell

Connect to the router via telnet  
```
$ telnet gateway 23
# enter username and password (same as web login)
```
once the prompt is shown, type in `sh`  
```
TP-Link(conf)# sh
```
a busybox shell is now available as root
```
# uname -a
Linux Archer VR1210v 3.18.20 #1 SMP Thu Dec 17 10:52:26 UTC 2020 [SDK 2.4.1] mips GNU/Linux

```
