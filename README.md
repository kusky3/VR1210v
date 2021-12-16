# VR1210v
 Accessing the undocumented TP-Link Archer VR1210v root shell 


* connect to the router via telnet  
```
$ telnet gateway 23
# enter username and password (same as web login)
```
* once the prompt is shown, type in `sh`  
```
TP-Link(conf)# sh
```
* a busybox root shell is now available
```
# uname -a
Linux Archer VR1210v 3.18.20 #1 SMP Thu Dec 17 10:52:26 UTC 2020 [SDK 2.4.1] mips GNU/Linux

```

### where do we go from here

* dump /bin/cli and find an exploit
