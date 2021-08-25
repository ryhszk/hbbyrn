# hbbyrn (hobby runtime)

This project to play and learn about containers, low-level container runtimes, and more.

# create rootfs

```
# mkdir rootfs
# podman export $(podman create busybox) | tar -C rootfs -xvf - 
```

```
# go run main.go run /bin/sh
#
```
