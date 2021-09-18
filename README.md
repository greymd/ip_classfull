# ip_classfull

This script lists all classful CIDRs contained in the given CIDR.

For example,  10.0.0.0/15 (10.0.0.1 .. 10.1.255.255) covers 10.0.0.0/16 and 10.1.0.0/16.

```
$ ./ip_classfull 10.0.0.0/15
10.0.0.0/16
10.1.0.0/16
```

In this script, a classful CIDR is defined as a address with a prefix of `/8`, `/16`, `/24` or `/32`.

```
$ ./ip_classfull 172.16.0.0/22
172.16.0.0/24
172.16.1.0/24
172.16.2.0/24
172.16.3.0/24
```
