# hbbyrn (hobby runtime)

This project to play and learn about containers, low-level container runtimes, and more.

# create rootfs

```
# mkdir rootfs
# podman export $(podman create ubi8-micro)  | tar -C rootfs -xvf -
```

# start container
```
# go run main.go run /bin/bash
running [/bin/sh] as PID 1
bash-4.4# ls
bin  boot  dev  etc  home  lib  lib64  media  mnt  opt  proc  root  run  sbin  srv  sys  tmp  usr  var 
```

