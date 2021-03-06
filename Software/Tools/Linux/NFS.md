Edit /etc/auto.master
```
/net    -hosts
```

```
exportfs -ra
mount -o nfsvers=3 host:/path /local_path
```


1. [Setting Up NFS Server And Client On CentOS 7](http://www.unixmen.com/setting-nfs-server-client-centos-7/)
2. [autofs @CentOS](https://www.centos.org/docs/5/html/Deployment_Guide-en-US/s1-nfs-client-config-autofs.html)
3. [How to install and configure Autofs on CentOS 7 / Fedora 22 / Ubuntu 14.04](http://www.itzgeek.com/how-tos/linux/ubuntu-how-tos/how-to-install-and-configure-autofs-on-centos-7-fedora-22-ubuntu-14-04.html)
4. [Autofs @ archlinux](https://wiki.archlinux.org/index.php/Autofs)
5. [autofs @ Ubuntu](https://help.ubuntu.com/community/Autofs)
6. [How to use nsswitch.com to find Linux system information](http://searchitchannel.techtarget.com/feature/Using-nsswitchconf-to-find-Linux-system-information)
7. [How to do Linux NFS Performance Tuning and Optimization](http://www.slashroot.in/how-do-linux-nfs-performance-tuning-and-optimization)
8. [Optimizing NFS Performance](http://nfs.sourceforge.net/nfs-howto/ar01s05.html)
9. [NFS Server Performance and Tuning Guide for Sun Hardware](http://docs.oracle.com/cd/E19620-01/805-4448/6j47cnj0i/index.html)
10. [Using rpcdebug to debug Linux NFS client and server issues](http://prefetch.net/blog/index.php/2011/11/02/using-rpcdebug-to-debug-linux-nfs-client-and-server-issues/)
11. [NFS: Setting up a basic NFS file system share](http://bencane.com/2012/11/23/nfs-setting-up-a-basic-nfs-file-system-share/)
12. [NetworkTracing - troubleshoot NFS problems](http://wiki.linux-nfs.org/wiki/index.php/NetworkTracing)
13. [Mount NFS share using Virtualbox under NAT](http://www.matteomattei.com/nfs-mount-under-nat-on-virtualbox/)
