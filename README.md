# Autozerocert

script for automate installation of system-level burp certificate in android root device. also work with android device which unable to "adb root". burp certificate obtain from 127.0.0.1:8080


### Requirement

adb


### Example
```sh
$ ./autozerocert
--2020-12-15 03:56:00--  http://127.0.0.1:8080/cert
Connecting to 127.0.0.1:8080... connected.
HTTP request sent, awaiting response... 200 OK
Length: 973 [application/octet-stream]
Saving to: ‘cert’

cert                                                       100%[=======================================================================================================================================>]     973  --.-KB/s    in 0s      

2020-12-15 03:56:00 (271 MB/s) - ‘cert’ saved [973/973]

Not running as root. Try "adb root" first.
9a5ba575.0: 1 file pushed. 0.5 MB/s (1375 bytes in 0.003s)
certificate successfully installed

```

